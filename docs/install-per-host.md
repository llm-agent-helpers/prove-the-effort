# install per host

one skill, one agent, one hooks file. the only thing that differs is where each host looks for them.

## claude code

**as a plugin** (gets skill + agent + hooks + slash command all at once):

```bash
git clone https://github.com/bodencrouch/prove-the-effort ~/.claude/plugins/prove-the-effort
```

then in claude code, `/plugin` and enable it, or add to `~/.claude/settings.json`:

```json
{ "enabledPlugins": { "prove-the-effort": true } }
```

**as loose files** (if you don't want the plugin system):

```bash
git clone https://github.com/bodencrouch/prove-the-effort /tmp/pte
mkdir -p ~/.claude/skills ~/.claude/agents
cp -r /tmp/pte/skills/prove-the-effort ~/.claude/skills/
cp /tmp/pte/agents/prove-the-effort-reviewer.md ~/.claude/agents/
```

for the hooks you'll have to add them to `~/.claude/settings.json` by hand, copy the `hooks` block from `hooks/hooks.json`. the plugin path does this for you.

**the hooks.** two of them, both prompt-based. `SubagentStop` fires when a subagent returns and blocks if its final message claims done/passing/verified without a referent. `Stop` does the same for the main agent. they're what make the agent-to-agent rule work even when the skill isn't loaded in the subagent.

if you've got a `~/.agents` setup with a sync script (i do), put the skill there and let the sync carry it into `~/.claude`.

## codex

```bash
git clone https://github.com/bodencrouch/prove-the-effort ~/.codex/plugins/prove-the-effort
```

`.codex-plugin/plugin.json` points at the same `skills/`, `agents/`, `hooks/` and `commands/` dirs. invoke with `$prove-the-effort`.

## cursor

```bash
git clone https://github.com/bodencrouch/prove-the-effort /tmp/pte
mkdir -p .cursor/rules
cp /tmp/pte/.cursor/rules/*.mdc .cursor/rules/
```

the `.mdc` is `alwaysApply: true`, so it's on for every file. if you only want it on plan/design docs change the glob. cursor doesn't have subagents or hooks so the agent-to-agent half doesn't apply, you just get the six rules and the feasibility/optimality/brainstorm shapes.

## gemini cli / antigravity

```bash
git clone https://github.com/bodencrouch/prove-the-effort ~/.gemini/extensions/prove-the-effort
```

`gemini-extension.json` sets `contextFileName` to `AGENTS.md`, which has the full rule set. activate with `activate_skill prove-the-effort`.

## opencode

```bash
git clone https://github.com/bodencrouch/prove-the-effort ~/.config/opencode/plugins/prove-the-effort
```

`opencode.json` loads `AGENTS.md` and the skill file as instructions. use the `skill` tool to call it.

## windsurf

```bash
git clone https://github.com/bodencrouch/prove-the-effort /tmp/pte
cp /tmp/pte/.windsurf/rules.md .windsurfrules
```

windsurf's rules file is a single flat markdown, so `.windsurf/rules.md` is the condensed version. same six rules, same three shapes.

## copilot cli

no dedicated adapter yet. drop `AGENTS.md` into your repo root, copilot reads it.

## verifying it's on

say "prove the effort" or "is this feasible" or "grill me" in any host and it should open with a stance, not a question. if it opens with "what do you think" it's not loaded.

for the hooks in claude code: spawn a subagent, have it return "done" with no evidence. it should get blocked with the unbacked claim named and the referent it'd need.
