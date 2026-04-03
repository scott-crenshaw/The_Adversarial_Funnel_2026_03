The Adversarial Funnel
A Methodology for AI-Assisted Market Discovery and Opportunity Scoring for Novel Technologies
Scott Crenshaw and Gabriel Haymes, assisted by Claude | March 2026

We needed to evaluate fifteen-plus market verticals for a novel materials science technology — fast, with a two-person team, without months of customer discovery calls and expensive experiments.
Traditional approaches to this problem are slow and backwards. Teams invest weeks in market research before discovering the physics doesn't work. The most expensive kind of failure: technical impossibility discovered after emotional and financial investment in a thesis.
This paper describes a methodology that flips the sequence and uses large language models as constrained research analysts with built-in adversarial mechanisms. It is a practitioner paper, not a scientific paper — it describes what we actually built, what worked, what didn't, and why.
What the methodology does

Physics-first evaluation — kills opportunities on technical grounds before investing in market research
Adversarial critique-and-revise cycle — every assessment is challenged by a separate AI instance instructed to find reasons the opportunity fails
Sub-agent isolation — distributes research across agents with isolated context windows to prevent the synthesis quality degradation that occurs when a single session accumulates too many search results
Architectural countermeasures for hallucination, confirmation bias, scoring drift, and late-section quality decay — addressed through system design rather than hoping the model behaves well

Key findings

~70% kill rate. Each kill represents months of misdirected effort avoided.
Every kill confirmed. In every case where a kill verdict was subsequently tested through customer conversations or technical analysis, the kill was validated.
~30% of critiques surfaced a new opportunity not in the original landscape scan. Several of the strongest final opportunities were discovered this way.
1–2 days to verdict with 2–4 hours of active human involvement, versus 3–6 weeks using traditional methods.

Who this is for:
Founders, product leaders, and anyone using AI for serious analytical work — market evaluation, technology assessment, competitive analysis — rather than content generation. The methodology was developed for materials science but the architecture generalizes. The AI failure modes it addresses are not domain-specific.
