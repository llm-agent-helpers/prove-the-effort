# evolving the dataset

this repo's a build output. the source is a `spec.md` plus a `records.jsonl` in [from-evidence](https://github.com/bodencrouch/from-evidence), and `build.py` renders everything in here from those two files. if you edit `SKILL.md` directly the next build overwrites it. edit the spec instead.

## what a record looks like

one record is one stretch of a real exchange where the pattern happened. fields:

- `id`: `r-NNN`
- `topic`: one line, what was being argued
- `partner`: role of the other side (systems-engineer, engine-developer, etc). never a name.
- `turns`: the exchange, `self` and `partner` labelled
- `moves`: which moves from the spec showed up (states_stance, demands_evidence, concedes_point, ...)
- `outcome`: conceded / redirected / escalated / dropped
- `quality`: 1 to 5, how clean an example of the pattern it is
- `why_it_worked_or_failed`: one or two sentences, hand written, what actually made it go the way it went

that last field is the one that matters and it's the one nobody wants to write. write it anyway. it's what the skill learns from.

## adding one

```
/evolve
```

paste the exchange. it'll extract the moves, ask you for the why, add the record, rebuild, re-run the evaluator, and tell you what changed in the phrase bank and the exemplar set. if the record leaks a held-out line it'll refuse and tell you which one.

or by hand: append to `datasets/debate/records.jsonl`, bump the version in `dataset.json`, `python3 scripts/build.py`, `python3 scripts/evaluate.py`.

## what the evaluator checks

- phrase bank coverage: are the high-frequency `self` lines from q≥4 records reflected in SKILL.md
- anti-pattern markers: does SKILL.md contain any of the tell-tale phrases it says never to use (it shouldn't, the "don't" section quotes them but the rest of the file shouldn't emit them)
- held-out leak: are any lines from the 15 held-out records quoted verbatim in the built artifact. threshold is 5 words, shorter than that is chat noise not a leak.
- citations: does every benefit in the spec cite a record id or a paper

it does not check whether the skill actually behaves. that's the circular problem, see [how-it-decides.md](how-it-decides.md). response-based eval's on the list.

## the spec

`datasets/debate/spec.md`. sections, all required unless marked:

- identity: skill_name, one_line, why_it_helps, trigger_description, when_not_to_use
- benefits: each one cites a record or a paper
- language / behaviour / communication style / demeanor / motivations
- moves: opening, escalation, repair, exit, each with record ids
- core rules (optional, max 6)
- inline exemplars (optional, max 8, `r-NNN:lo-hi` turn ranges)
- agent protocol (optional, becomes PROTOCOL.md)
- phrase bank: the lines to reuse, from `self` turns only
- anti-patterns: the "don't" list with tell-tale phrases
- held-out exemplars: which record ids are held out

skill_name can't match anything in the phrase bank. that's a validator. it's how the name ended up being prove-the-effort and not prove-me-wrong.

## voice

nothing in the generated output should read like an llm wrote it. no em-dashes in prose (quotes from the records keep theirs, they're data). no "**What it does.**" bold labels. no "Thesis:" openers. no "if you remember one thing" closers. lowercase where i'd write lowercase. if you're adding to the spec and it starts sounding like a blog post, stop and read a few records first.
