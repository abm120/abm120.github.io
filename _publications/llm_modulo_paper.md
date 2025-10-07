---
title: "Position: LLMs can’t plan, but can help planning in LLM-modulo frameworks"
collection: publications
category: papers
permalink: /publication/llm_modulo
excerpt: 'This work proposes a novel neuro-symbolic approach for reliable planning with LLMs by having external model-based verifiers and critics in a bi-directional interaction regime.'
date: 2024-02-05
venue: 'International Conference on Machine Learning as Spotlight'
paperurl: 'https://openreview.net/forum?id=Th8JPEmH4z'
citation: 'Kambhampati, S., Valmeekam, K., Guan, L., Verma, M., Stechly, K., Bhambri, S., ... & Murthy, A. B. (2024, June). Position: LLMs can’t plan, but can help planning in LLM-modulo frameworks. In Forty-first International Conference on Machine Learning.'
---

There is considerable confusion about the role of Large Language Models (LLMs) in planning and reasoning tasks. On one side are over-optimistic claims that LLMs can indeed do these tasks with just the right prompting or self-verification strategies. On the other side are perhaps over-pessimistic claims that all that LLMs are good for in planning/reasoning tasks are as mere translators of the problem specification from one syntactic format to another, and ship the problem off to external symbolic solvers. In this position paper, we take the view that both these extremes are misguided. We argue that auto-regressive LLMs cannot, by themselves, do planning or self-verification (which is after all a form of reasoning), and shed some light on the reasons for misunderstandings in the literature. We will also argue that LLMs should be viewed as universal approximate knowledge sources that have much more meaningful roles to play in planning/reasoning tasks beyond simple front-end/back-end format translators. We present a vision of {\bf LLM-Modulo Frameworks} that combine the strengths of LLMs with external model-based verifiers in a tighter bi-directional interaction regime. We will show how the models driving the external verifiers themselves can be acquired with the help of LLMs. We will also argue that rather than simply pipelining LLMs and symbolic components, this LLM-Modulo Framework provides a better neuro-symbolic approach that offers tighter integration between LLMs and symbolic components, and allows extending the scope of model-based planning/reasoning regimes towards more flexible knowledge, problem and preference specifications.
