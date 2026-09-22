# optimality, before and after

## before (no skill)

> **user:** sqlite or postgres for the corpus store? the planner agent says sqlite, the reviewer agent says postgres.
>
> **agent:** Both are solid choices with different tradeoffs. SQLite offers simplicity and zero-config deployment, while PostgreSQL provides better concurrency and scalability. Given your use case, I'd lean towards PostgreSQL for its robust concurrent write handling, but SQLite could work if your write load is light. Would you like me to elaborate on either option?

that's the midpoint. it doesn't decide anything, it hedges toward one and offers to elaborate on both. the two agents are still disagreeing.

## after (prove-the-effort)

> **user:** sqlite or postgres for the corpus store? the planner agent says sqlite, the reviewer agent says postgres.
>
> **agent:** neither of them's written down what would decide it, so neither position counts yet. what's the criterion. i'll guess: concurrent writers, and "database is locked" errors per hour under the real orchestrator load. if that's it, what's the number today?
>
> **user:** 5 orchestrator connections, we've seen "database is locked" a few times but nobody counted
>
> **agent:** then the reviewer's position is a feeling and the planner's is a guess. count it. run the orchestrator for an hour with the 5 connections, grep the log for `locked`, paste the count. also: how many files does the postgres move touch?
>
> **user:** ok. 4 locked errors in the hour. postgres migration touches ~40 files.
>
> **agent:** sqlite with a single-writer queue. 4 lock errors an hour is a queue problem not a database problem, and a queue's 1 file not 40. if the count's still above 0 after the queue lands, that's when postgres becomes the answer. reviewer's position is parked with that condition attached, not rejected.
>
> **user:** reviewer says "but postgres is the industry standard for this"
>
> **agent:** that's not a criterion. the criterion was lock errors per hour and blast radius. sqlite plus queue wins both. if the reviewer's got a different criterion it needs to name it.

what changed: the criterion got written down before anybody argued. the check ran. whichever option won the criterion won. "industry standard" got rejected as a norm not a mechanism. the losing option got parked with the condition that'd revive it, so it's not gone, it's just waiting for a number.
