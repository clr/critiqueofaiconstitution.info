---
title: About Us
permalink: /about/
---

### Casey Rosenthal
Software engineer, architect, and leader known for writing the definition of [Chaos Engineering](https://principlesofchaos.org/), building and managing the Chaos Engineering Team at Netflix, starting the conferences on the subject, getting the industry to adopt the process, and literally writing the book on the subject [Chaos Engineering: System Resiliency in Practice](https://amzn.to/3bjsRJ9). CEO/Cofounder of several startups, all focused on reliability and security. Worked at two hyperscalars: At Netflix, was simultaneously the Engineering Manager of the Chaos Engineering Team, the Traffic Engineering Team, and others. At Oracle, created the Safety program as executed by the Cloud Safety team for all of OCI. Extensive experiences with distributed systems, artificial intelligence, translating novel algorithms and academia into working models. Matriculated at Harvard, Ursinus College, Worcester Polytechnic Institute, University of Pennsylvania, Ohio University, University of Southern Maine, Lund University in Sweden studying Computer Science, Philosophy, and Safety Systems.

### Courtney Nash
Seasoned tech industry expert with 25+ years in editing, content creation, acquisition, research, strategy, and execution. As someone who used to study the neuroscience behind how people learn, I'm now paying close attention to the interaction between computers and humans, and their often unexamined consequences. Currently running the VOID, a research company making the software industry better, safer, and more resilient.Previously was Director of strategic content for O'Reilly Media.

### Why Us?

We are trained in the field of Resilience Engineering. We study things like nuclear power plants, air traffic control systems, hospitals, aircraft carriers—critical and complex systems where human lives are at stake, yet accidents are rare.

We have too much to say about Resilience Engineering as it pertains to AI, so we will highlight just three things that have a bearing on how we interpret the development of AI systems:

1. The practice of Safety benefits from people being given good context in environments where they can collaborate. The inverse is also true: when people are deprived of relevant information or encouraged to work in isolation, safety suffers. This is particularly relevant when considering the current crop of AI code development tools, for example, which tend to isolate software engineers rather than bringing them into an environment where they can learn from each other and align perspectives.
2. People familiar with danger tend to build safer systems. This one can be somewhat counter-intuitive, because without research to back this up, it might seem that people who are far away from danger are safer. In practice, people who are adjacent to danger often have the context and skill development that allows them to better avoid the negative outcomes of dangerous systems. This invites system safety design to expose operators of complex systems to the edges of system performance, without actually eliciting the undesirable outcomes. This is certainly a tricky line to walk in practice. You will see that this has a bearing on how we consider things like guardrails, which we generally see as an anti-pattern (a symptom of poor design) in long-running critical systems.
3. When we analyze incidents in Safety—events that resulted in undesirable outcomes— we generally reject the positivist view that there is an objective 'truth' of how the incident deterministically unfolded. Instead we see analysis as a choice to construct narratives that either focus attention on human failings (didn't pay attention, could have used better judgment, should have tested before pushing to production, etc) or we can focus attention on deficiencies in the design of the system. Approaching an incident as a design problem is always more conducive to learning than blaming a human for what they could/should/would have done, and learning is always more conducive to Safety.

The themes above are woven into the analysis that follows. Finally, it should be noted that LLMs will not be used to assist with this document, for the same reason we don't think LLMs should assist in editing the Constitution, described in the "Strange AI Loops" section of the critique.
