# why this exists

i kept watching the same thing happen across engine rewrites, editor rewrites, RE toolchains, mod build pipelines, basically every project i touched for a couple years. a decision moves forward on a claim nobody can produce evidence for. a benchmark that never ran. a worst case nobody bothered to name. "we'll refactor it later" with no receipt. and then weeks later the receipt still doesn't exist, the refactor's a haunted mansion, and someone has to write the code again from scratch.

the thing that actually saved time in discord dms and PR reviews turned out to be really small. ask for the one concrete thing that would move you, and stop the loop when it doesn't show up. like 9 out of 10 times it shows up and the disagreement's gone in five words. the 10th time, the fact that it didn't show up *is* the finding. the plan's not feasible yet, or the option's not optimal, or the "done" isn't done.

this skill is that instinct turned into something an agent can run against a plan, a PR, a dm, or another agent, without turning into a soft-curious interview.

## why grill-me wasn't it

grill-me was the earlier skill. it's a good tool for drawing a reluctant person out, soft why questions, curiosity frames, safety valves like "just curious, no big deal". it's the wrong tool for pressure testing a technical claim because those safety valves close the thread before the referent lands. against a model there's nobody to spare. against your own plan there's nobody to spare either. what you actually want is the harder shape. state a stance, one concrete question, hold, concede fast.

i went and counted. in 59k llm-facing turns from my own logs, zero occurrences of the discord softeners. "prove it / run it" showed up 238 times. "you said" 150. "stop asking" 251. that's the register. grill-me was built from the wrong half of the data.

prove-the-effort is that harder shape plus the speculative generality rule from a separate policy i'd been running: build the futures now, but only when demand can be named and implementation can be verified. demand can be hypothetical. implementation and verification can't.

## why feasibility, optimality, brainstorming are up top

because that's where the waste actually is. most of the effort that gets thrown away on a project doesn't get thrown away fixing bugs. it gets thrown away earlier:

when a plan's being written and nobody names the measurement that would kill it.
when options are being compared and nobody writes down the criterion that decides.
when a brainstorm ships "worth exploring" options that carry nothing that could prove them.

if the skill only fires on "done" claims the waste is already sunk by the time it runs. so those three shapes move the pressure earlier, into the plan, the compare, the brainstorm. they're at the top of the use case list on purpose.

## why one skill, one agent, one command

names rot when there's more than one. this thing went through prove-me-wrong, find-the-gap, cut-the-waste, worth-building before landing here. every one of those was describing a piece of it. prove-the-effort is what it actually does. every host runs the same skill, spawns the same subagent, enforces the same hooks. one dataset feeds all of it. `/evolve` adds a record and rebuilds everywhere. nothing's host specific except where the file lives.
