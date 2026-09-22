# use cases

in the order i actually reach for it. the first three are where most of the wasted time lives, so they're first.

## 1. feasibility

"can this be built with what we have"

the skill turns that into: what's the one measurement that would kill this plan if it's missing. not a list of risks, one measurement. if nobody can name it the plan's not feasible yet and that's the finding, you don't hedge it.

concrete example from my own stuff. wanted to port a 3d engine to the browser via emscripten. the feasibility question wasn't "is wasm fast enough" it was "does `end_m01aa` load and render a room with smoke exiting zero." until that ran, everything else was speculation. once it ran, the port was feasible and the rest was just work.

what it asks:
- what's the smallest thing that has to work for this to be possible at all
- has that thing been run, and what did it output
- if it hasn't been run, why not, and what's stopping it

## 2. optimality

"which option's better"

the skill refuses to answer until the criterion's written down. latency, lines touched, blast radius, reversibility, what the user actually asked for, whatever it is. then it runs the check if it can. whichever option wins the criterion wins. it does not pick whichever one sounds better in the thread and it does not pick the midpoint.

if both options hold on the criterion it takes the one that's cheaper to reverse. if neither side can produce a referent in three rounds it escalates with both positions and the missing thing, one line each.

concrete example. sqlite vs postgres for a corpus store. the argument went in circles until somebody wrote "concurrent writers, 5 orchestrator connections, how many `database is locked` errors in an hour." that's a number you can measure. measured it. sqlite with a single writer queue won because the alternative touched 40 files and the number was 0 with the queue in place.

## 3. brainstorming

"give me options"

every option that comes out has to carry the thing that would prove it before it survives the round. if it can't name one it gets marked speculation and parked. it does not get shipped as "worth exploring" because that phrase is how you end up with 12 open threads and nothing built.

this is the one that changed my planning the most. a brainstorm used to produce a pile of ideas. now it produces a shorter pile where each one has a next step that's checkable. the parked ones are still there in case a referent shows up later.

## 4. your own plan or design

grill it before you build it. the questions come in one batch with defaults you can accept in one word, and there's always a "figure it out yourself" option. no softeners because there's nobody to spare. if it asks something that's already on screen that's a bug in the skill.

## 5. reviewing someone's "done"

another agent, a PR, a worker packet, a DM. "done" / "passing" / "verified" / "fixed" without the thing that proves it doesn't get accepted. it asks once. if the referent doesn't arrive the claim gets quarantined before anything's built on it.

for agents this is enforced at the harness level too via the Stop and SubagentStop hooks, so it works even if the skill isn't loaded in the subagent.

## 6. drafting a reply to someone's claim

you're in a dm, someone said something you don't buy, you want to push back without being a dick about it. the skill drafts in the voice from the records. stance first, one concrete question, a laugh after a hard line, exit valve for them because they're a person.

## 7. settling a disagreement between two agents

each side writes the criterion and the measurement that'd settle it. the check runs if it can. a judge that argued neither side reads both in both orders and writes evidence before verdict. escalates to you only if no referent can be produced in three rounds.

## 8. deciding whether to build the future now

speculative generality. a second backend, a different consumer, a schema change you can imagine. those are reasons to build the contract now. "this will scale" or "this'll pass" with no benchmark is not a reason to do anything. demand can be hypothetical, implementation and verification can't.

## when not to use it

- drawing a reluctant person out. use a soft-question skill.
- taste, naming, aesthetics. there's nothing to point at.
- every message. it fires on claims, not chatter.
- when you're the one who made the claim being judged. get someone else to run it.
