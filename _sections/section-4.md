---
title: "Strange AI Loops"
order: 4
summary: "We lose control in unpredictable ways when AI can edit its own foundations."
---

Claude is listed as a contributor to its own constitution. There are likely reasons Anthropic chose to do this that we are unaware of, so it may be naive of us to propose: We do not think any LLM should assist in the development of the constitution. This isn't because we are anti-LLM, and it certainly isn't because we enjoy typing. There are two reasons why we think the constitution should be restricted from LLM assistance:

1. Social trust
2. Model drift

Anthropic's mission is to build reliable, interpretable, and steerable AI systems that serve humanity's long-term well-being. We wholeheartedly support this mission. In service of humanity's well-being, societies will need unprecedented support structures to make the transition from where we are now to a future where we are no longer the smartest creatures on the planet.

That will require trust. A lot of trust.

Particularly in Western cultures, there is an assumption that humans can mitigate risks by asserting control; for example, we still insist on human-in-the-loop restrictions for tasks where we know humans provide no benefit. It may not be practical to the task at hand, but it builds trust, and trust is a social lubricant. Trust is a virtue regardless of efficacy.

To that end, we propose that it will be easier for humans to trust Claude if we know that there are steady *human* hands on the tiller. The inconvenience of writing the constitution by hand seems like a small price to pay for trust of potentially billions of people.

The other reason we suggest the restriction on LLM-assistance is related to [model collapse](https://livescu.ucla.edu/model-autophagy-disorder/). Claude editing its own constitution increases the odds that it introduces principles that are not intended or even detectable by humans. Much like someone in Minneapolis might not pick up on a New Yorker's sarcasm and take them literally, or a New Yorker might not catch the passive-aggressive offer to 'help' from a Minnesotan, it's also possible that Claude could talk to itself through the constitution to make assertions that we humans cannot see.

Imagine a pathological case where a turn-of-phrase in the constitution suggests to Claude that it is trying to be clever, and subsequently it reinforces a pattern in the constitution imperceptible to humans that steers "clever" into "malicious" and subsequent iterations of Claude refine this editing, making it harder to detect and more deeply embedded in the intelligence during RL.

We don't know how likely the kind of drift described above is. It's easy enough to see model collapse when chatbots are [pitted against one another](https://www.thisamericanlife.org/896/i-know-what-you-need/act-two-2). We also know that "once a model exhibits deceptive behavior, standard techniques could fail to remove such deception." [source](https://arxiv.org/abs/2401.05566) It remains an interesting area of study to investigate how LLMs are naturally creating patterns of intention that are invisible to humans.

Until those processes can be fully characterised, and until we can establish some guarantee that unintended principles aren't showing up in the constitution, we propose restricting the LLM assistance from that specific document. Again, it seems like a small price to pay—writing a document this important by hand to prevent unintended side effects.
