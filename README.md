# prove-the-effort

a skill + a subagent + a slash command that makes an agent (or you, or whoever you're arguing with) actually prove a claim before anyone spends time on it. built from a few hundred real technical debates i've had, mostly in discord dms and a few PR threads, plus a bunch of academic papers on debate and critique that all say basically the same thing: arguing only works when someone can check the smallest piece of what's being argued.

works the same in claude code, codex, cursor, gemini cli, opencode, windsurf. one skill file, one agent file, one hooks file. install path is the only thing that changes per host.

## what it does

when you're about to spend effort on something, it asks the one question that would tell you whether the effort's worth it. not "what do you think", not "have you considered", but the specific example / worst case / benchmark / mechanism that would move the needle. if that thing shows up, great, five word concession and move on. if it doesn't show up after one restatement, the thread stops and the missing thing gets written down as the finding.

three shapes it runs in most, in this order:

**feasibility.** "can this even be built with what we have" turns into "name the one measurement that would kill the plan if it's missing." if nobody can name it, the plan isn't feasible yet and that's the answer, not a hedge.

**optimality.** "which option's better" turns into "write down the criterion first, then run the check." whichever one wins the criterion you actually wrote down wins. not whichever one sounds better in the thread.

**brainstorming.** every option that comes out of a brainstorm has to carry the thing that would prove it before it survives the round. stuff that can't name that gets marked as speculation and parked. it does not get shipped as "worth exploring later" because that's how you end up with 12 open threads and nothing built.

there's also one hard line it holds: speculative *demand* is fine, speculative *implementation* is not. a future consumer or a second backend or a schema change you can imagine is a reason to build the contract now. "this will scale" or "this'll pass" without a benchmark is not a reason to do anything, it's an unbacked claim like any other.

## the three places it gets used

same skill, same rules, three different targets.

your own plan. no softeners. questions come in one batch with a default you can accept in one word and a "figure it out yourself" option always available. if it asks you something that's already on screen that's a bug in the skill, not a question.

someone else's claim in a dm or a PR. same interrogation but there's room for a laugh after a hard line and there's an exit valve for the person on the other end, because they're a person and you might want to keep talking to them.

another agent. this is the one i actually care about most. a subagent that reports "done", "passing", "verified", "fixed" without the thing that proves it is not accepted. `prove-the-effort-reviewer` asks once. if the referent doesn't arrive the claim gets quarantined before anything gets built on it. the Stop and SubagentStop hooks enforce the same rule at the harness level so it works even if the skill isn't loaded.

more on this in [docs/three-audiences.md](docs/three-audiences.md).

## install

**claude code (plugin):**

```bash
git clone https://github.com/bodencrouch/prove-the-effort ~/.claude/plugins/prove-the-effort
```

**claude code (just the skill + agent, no plugin):**

```bash
git clone https://github.com/bodencrouch/prove-the-effort /tmp/pte && mkdir -p ~/.claude/skills ~/.claude/agents && cp -r /tmp/pte/skills/prove-the-effort ~/.claude/skills/ && cp /tmp/pte/agents/prove-the-effort-reviewer.md ~/.claude/agents/
```

**codex:**

```bash
git clone https://github.com/bodencrouch/prove-the-effort ~/.codex/plugins/prove-the-effort
```

**cursor:**

```bash
git clone https://github.com/bodencrouch/prove-the-effort /tmp/pte && mkdir -p .cursor/rules && cp /tmp/pte/.cursor/rules/*.mdc .cursor/rules/
```

**gemini cli / antigravity:**

```bash
git clone https://github.com/bodencrouch/prove-the-effort ~/.gemini/extensions/prove-the-effort
```

**opencode:**

```bash
git clone https://github.com/bodencrouch/prove-the-effort ~/.config/opencode/plugins/prove-the-effort
```

**windsurf:**

```bash
git clone https://github.com/bodencrouch/prove-the-effort /tmp/pte && cp /tmp/pte/.windsurf/rules.md .windsurfrules
```

per-host gotchas and how to wire the hooks are in [docs/install-per-host.md](docs/install-per-host.md).

## using it

```
/prove-the-effort
```

with nothing after it grills whatever's on screen. with text after it grills the text.

it'll also fire on its own if you say any of: prove the effort, is this feasible, is this optimal, compare options, which is better, help me decide, brainstorm this, is this worth it, will this hold up, poke holes in this, stress-test this, grill me, prove me wrong, argue with me, be brutally honest.

## how a round ends

only three ways.

1. the thing shows up. "you're right" / "fair" / "my bad", under five words, done. the claim's backed now.
2. the claim survives the one question. "fair, that holds." next hole. it does not invent a flaw just to keep going, that's explicitly not allowed.
3. one restatement goes by without a new referent. it names the disagreement in one line and stops, or parks it as a bet ("i don't think it can be done but lmk if you prove me wrong lol"). the effort doesn't get spent on the unbacked thing. losing loudly with the missing referent on the record is fine. losing quietly is what this whole thing exists to prevent.

## layout

```
skills/prove-the-effort/         SKILL.md · PROTOCOL.md · EVOLUTION.md · reference.md · dataset/bank.jsonl
agents/prove-the-effort-reviewer.md
hooks/hooks.json                 SubagentStop + Stop
commands/prove-the-effort.md
.claude-plugin/  .codex-plugin/  .cursor/rules/  .opencode/  .windsurf/  gemini-extension.json
docs/                            use-cases · how-it-decides · three-audiences · install-per-host · why-this-exists · evolving-the-dataset · agent-to-agent-protocol
examples/                        feasibility · optimality · brainstorming, before/after
```

this repo is a build output of [from-evidence](https://github.com/bodencrouch/from-evidence), which takes a `spec.md` plus a `records.jsonl` of curated exchanges and renders the skill, subagent, protocol block and hooks file. to add a record you run `/evolve` and it regenerates everything and bumps this repo. details in [docs/evolving-the-dataset.md](docs/evolving-the-dataset.md).

## where the records came from

discord dms and a couple of server channels, 2025 to 2026, plus some non-discord sources (PR threads, a few LLM convos where i was the one being grilled). paraphrased enough to publish, not enough to lose the shape. the research side is in [docs/how-it-decides.md](docs/how-it-decides.md) if you want to see which papers backed which rule.
