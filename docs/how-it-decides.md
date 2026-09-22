# how it decides

which rule came from which evidence. two sources: my own debate records (112 discord stretches, 53 non-discord, held-out set of 15 for leak checking) and a stack of papers on debate, critique, clarifying questions, and multi-agent collaboration. mostly 2018 to 2024, gpt-3/4 era on purpose because that's when the field was still measuring things instead of vibing.

## the counts from the records

- exchanges that stayed engaged had a concrete referent 76% of the time
- exchanges that resolved ended in a concession 74% of the time
- every exchange that got dropped had the stance restated without a new referent. 100%.
- in 59k llm-facing turns, zero discord softeners ("just curious", "no big deal", "sorry for asking"). "prove it / run it" showed up 238 times. "you said" 150. "stop asking" 251.

that last one's why grill-me was mid. it was built from the discord half where softeners exist because there's a person to spare. against a model the register is completely different and it's the register i actually want in a tool.

## rule by rule

**stance first.** irving 2018 (ai safety via debate): debate only beats a single advocate when the judge can verify the smallest unit of a claim. no stance, no unit to verify. the records back it, every exchange that opened with "what do you think" went nowhere.

**one concrete referent per turn.** khan 2024 (debating with more persuasive llms): verified quotes are what makes debate work, not persuasiveness. michael 2023 (debate helps supervise unreliable experts): the honest side's main failure mode is missing evidence, not losing to a liar. so the fix is force the evidence to exist.

**hold, then fold fast.** huang 2023 (large language models cannot self-correct reasoning yet): self-correction without an external oracle loses accuracy. gou 2023 (CRITIC): critique without tools collapses to baseline or worse. so hold while it's a principle, fold the second it's a measurement. the records: 74% of resolved exchanges ended in a five-word concession.

**null move is legal.** if you always have to find a flaw you'll manufacture one, and the records show that's when threads went from productive to bitter. "fair, that holds" is a legal outcome, and it's in there a lot.

**stop rule.** 100% of dropped records had the stance restated with no new referent. so on the second restatement, stop. name it in one line, park it, move.

**batch the questions.** aliannejadi 2019 (qulac) and 2020 (clariq): a well-chosen clarifying question roughly doubles retrieval precision, a badly chosen one zeroes it. kuhn 2022 (CLAM): the gain is in asking on the right subset, not asking more. so batch them, give defaults, only ask what's actually ambiguous.

## the agent-to-agent rules

**independent first.** du 2023 (multiagent debate): same-model agents that read each other first converge on a confident wrong answer. form your own answer from evidence, then read theirs.

**never "are you sure".** xie 2023, sharma 2023 (sycophancy): "are you sure" flips llm answers without any new evidence. it's not a question, it's a pressure. banned.

**defend by re-deriving.** same sycophancy papers. if you fold because someone pushed you're not doing debate, you're doing compliance.

**different-backbone judge.** panickssery 2024 (llm evaluators recognize and favor their own generations), MAD table 6: judges favour their own outputs. so the fidelity judge runs on a different model than the author. sonnet judges what opus wrote.

**round cap three.** liang 2023 (MAD): most of the gain is in the first two rounds, after that it's noise or drift. three is the cap.

**executable feedback.** hong 2023 (MetaGPT), wu 2023 (AutoGen): "check the execution result" beats any amount of reasoning about whether it would work. run it if it runs here.

## speculative generality

this one's not from a paper, it's from a policy i'd been running separately. future *demand* can be hypothetical. a second consumer, a different backend, a schema change you can imagine, those are reasons to build the contract now. future *implementation* and *verification* can't be hypothetical. "this will scale" needs a benchmark. "this'll pass" needs the test to exist. the papers above back the second half (executable feedback, verified quotes), the first half's just how i want to build.

## what's not solved

evaluation's circular right now. `evaluate.py` checks the built SKILL.md for phrases that `build.py` wrote into it. that proves the pipeline ran, not that the skill behaves. the fix is a response harness: run the skill against held-out records, have a different-backbone judge score the outputs. it's on the list.

## the papers

irving, christiano, amodei 2018. ai safety via debate.
khan et al 2024. debating with more persuasive llms leads to more truthful answers.
michael et al 2023. debate helps supervise unreliable experts.
huang et al 2023. large language models cannot self-correct reasoning yet.
gou et al 2023. CRITIC: large language models can self-correct with tool-interactive critiquing.
aliannejadi et al 2019. asking clarifying questions in open-domain information-seeking conversations (qulac).
aliannejadi et al 2020. convai3: generating clarifying questions for open-domain dialogue systems (clariq).
kuhn, gal, farquhar 2022. CLAM: selective clarification for ambiguous questions.
du et al 2023. improving factuality and reasoning in language models through multiagent debate.
liang et al 2023. encouraging divergent thinking in large language models through multi-agent debate (MAD).
xie et al 2023. ask again, then fail: large language models' vacillations in judgement.
sharma et al 2023. towards understanding sycophancy in language models.
panickssery et al 2024. llm evaluators recognize and favor their own generations.
hong et al 2023. MetaGPT: meta programming for multi-agent collaborative framework.
wu et al 2023. AutoGen: enabling next-gen llm applications via multi-agent conversation.
huang et al 2017. learning to ask good questions (responsiveness signal: follow-ups built on the last answer).
