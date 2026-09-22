---
layout: default
title: "Horizon Summary: 2026-09-22 (EN)"
date: 2026-09-22
lang: en
---

> From 32 items, 6 important content pieces were selected

---

1. [Framework-Free Prototype Learner for Local LLMs](#item-1) ⭐️ 9.0/10
2. [MiMo v2.6 Release](#item-2) ⭐️ 8.0/10
3. [Transformers Explained Visually](#item-3) ⭐️ 8.0/10
4. [Jev Introduces New LLM Format: System One Models](#item-4) ⭐️ 8.0/10
5. [Cloudflare Python Workers Generally Available](#item-5) ⭐️ 8.0/10
6. [Enhancing Kimi Delta Attention Mechanism](#item-6) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Framework-Free Prototype Learner for Local LLMs](https://www.reddit.com/r/MachineLearning/comments/1wmn76r/i_built_a_frameworkfree_prototype_learner_that/) ⭐️ 9.0/10

A framework-free prototype learner named Jayce has been developed, which allows local language models (LLMs) to learn and correct facts more efficiently than traditional methods, up to 4 times faster than backpropagation. This innovation addresses the challenge of catastrophic forgetting in LLMs, potentially improving their efficiency and ability to adapt to new tasks without losing previously learned information. Jayce uses Adaptive Prototype Memory (APM) to learn and correct facts, shifting prototypes in real-time when a model makes a mistake, and operates offline on consumer hardware.

reddit · r/MachineLearning · /u/kavanutz · Sep 21, 19:44

**Background**: Local language models (LLMs) are designed to understand and generate language specific to a particular region or language, while catastrophic forgetting occurs when a model forgets previously learned information when learning new tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/noorulain-nn/Original-FSIC-APM">GitHub - noorulain-nn/Original-FSIC- APM · GitHub</a></li>
<li><a href="https://arxiv.org/abs/2504.01241">[2504.01241] Catastrophic Forgetting in LLMs: A Comparative Analysis Across Language Tasks</a></li>
<li><a href="https://www.emergentmind.com/topics/catastrophic-forgetting-in-language-models">Catastrophic Forgetting in LLMs</a></li>

</ul>
</details>

**Discussion**: The Reddit community has shown significant interest in the project, with discussions focusing on the potential impact of Jayce on the field of machine learning and its efficiency compared to backpropagation.

**Tags**: `#MachineLearning`, `#LocalLanguageModel`, `#CatastrophicForgetting`, `#AdaptivePrototypeMemory`, `#LLMInnovation`

---

<a id="item-2"></a>
## [MiMo v2.6 Release](https://mimo.xiaomi.com/mimo-v2-6) ⭐️ 8.0/10

Xiaomi has released MiMo v2.6, featuring detailed insights into the model's training and performance discussions. The new version includes two natively omnimodal models: MiMo V2.6-Pro and MiMo V2.6-Flash. The release of MiMo v2.6 is significant as it represents a major update to Xiaomi's AI technology, potentially impacting the AI industry with improved performance and methodology. It also fosters community engagement and discussion about the future of AI. MiMo v2.6-Pro is the most capable model to date, while MiMo V2.6-Flash offers a balance between intelligence, efficiency, and cost. The model's training cost was reported to be just $3.5M.

hackernews · volf_ · Sep 21, 20:12 · [Discussion](https://news.ycombinator.com/item?id=49792730)

**Background**: MiMo is a family of large language models developed by Xiaomi. It is used as the key AI model in Xiaomi's 'Human x Car x Home' ecosystem, providing AI services for various applications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Xiaomi_MiMo">Xiaomi MiMo - Wikipedia</a></li>
<li><a href="https://mimo.mi.com/models/en-US/mimo-v2.6-flash">Xiaomi MiMo Home</a></li>
<li><a href="https://mimo.xiaomi.com/mimo-v2-6">MiMo-V2.6 | Xiaomi</a></li>

</ul>
</details>

**Discussion**: Community discussions highlight the transparency of Xiaomi's model training, with users appreciating the detailed insights and the live dashboard shared during training. There is also a debate on the potential of China in the AI race due to its energy infrastructure.

**Tags**: `#AI`, `#Model Release`, `#Technology Update`, `#Community Discussion`, `#Machine Learning`

---

<a id="item-3"></a>
## [Transformers Explained Visually](https://poloclub.github.io/transformer-explainer/) ⭐️ 8.0/10

A new visually-explained guide to transformers, a key concept in machine learning and AI, has been released, offering a detailed look at the architecture and mechanisms behind this foundational technology. This guide is significant as it helps demystify complex concepts in machine learning, making them more accessible to a broader audience and potentially advancing the field through increased understanding and adoption of transformers. The guide provides an in-depth look at the attention mechanism, multi-head attention, and feed-forward networks, which are core components of the transformer architecture.

hackernews · aray07 · Sep 21, 19:43 · [Discussion](https://news.ycombinator.com/item?id=49792342)

**Background**: Transformers are a type of deep learning model that has become fundamental in natural language processing and other machine learning tasks, known for their ability to process and generate sequences efficiently.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Transformer_(deep_learning)">Transformer (deep learning) - Wikipedia</a></li>
<li><a href="https://aws.amazon.com/what-is/transformers-in-artificial-intelligence/">What are Transformers? - Transformers in Artificial Intelligence Explained - AWS</a></li>
<li><a href="https://www.ibm.com/think/topics/transformer-model">What is a Transformer Model? | IBM</a></li>

</ul>
</details>

**Discussion**: Community comments highlight the guide's effectiveness in explaining complex aspects of transformers, with discussions ranging from the attention mechanism to the practical applications of the technology.

**Tags**: `#Machine Learning`, `#AI`, `#Deep Learning`, `#Transformers`, `#Neural Networks`

---

<a id="item-4"></a>
## [Jev Introduces New LLM Format: System One Models](https://simonwillison.net/2026/Sep/21/jev/) ⭐️ 8.0/10

TypeSafe AI has introduced Jev, a new type of LLM known as 'System One models' or 'decision models', which outputs floating point numbers for categorization, yes/no questions, ratings, and confidence scores. This new approach to LLMs could significantly impact decision-making systems, potentially leading to more efficient and accurate decision support tools across various industries. Jev operates by accepting text inputs and returning floating point numbers, making it faster and more cost-effective than traditional LLMs, which charge for both input and output tokens.

rss · Simon Willison · Sep 21, 23:09

**Background**: LLMs (Large Language Models) are AI systems capable of understanding and generating human-like text. They have been widely used in natural language processing tasks, but have limitations in decision-making contexts.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.typesafe.ai/concepts/system-one">System One - TypeSafe AI</a></li>
<li><a href="https://systemonemodels.org/guides/what-is-a-system-one-model/">What is a System One model? | System One Models</a></li>
<li><a href="https://www.explainx.ai/blog/what-is-a-system-one-model-ai-explained-2026">System One Model: What It Means in AI (2026 Explainer) | explainx.ai ...</a></li>
<li><a href="https://dev.to/aairom/shrinking-giants-a-word-on-floating-point-precision-in-llm-domain-for-faster-cheaper-models-48c1">Shrinking Giants: A Word on Floating-Point Precision in LLM ...</a></li>
<li><a href="https://www.glyphmath.com/articles/floating-point-ai-reliability/">Floating-Point Arithmetic and AI System Reliability</a></li>
<li><a href="https://medium.com/decisionforce/understanding-mathematics-behind-floating-point-precisions-24c7aac535e3">Understanding Mathematics behind floating-point precisions</a></li>
<li><a href="https://huggingface.co/blog/sora-2/jev-ai-vs-llms-when-should-you-use-a-decision-mode">Jev AI vs LLMs: When Should You Use a Decision Model Instead of a Chat Model?</a></li>
<li><a href="https://www.aiinterviewagents.com/blog/jev-vs-llm-models">Jev vs LLMs: when a decision model beats a text model | AI Interview Agents</a></li>
<li><a href="https://apimaster.ai/blog/jev-vs-llm">Jev vs LLMs: Where a Decision Model Beats Prompting a Cheap Model | APIMaster.AI</a></li>

</ul>
</details>

**Discussion**: Community discussions highlight the potential of Jev for decision-making tasks, but also raise concerns about its black-box nature and potential biases.

**Tags**: `#LLM`, `#AI`, `#Decision Making`, `#Machine Learning`, `#TypeSafe AI`

---

<a id="item-5"></a>
## [Cloudflare Python Workers Generally Available](https://simonwillison.net/2026/Sep/21/cloudflare-python-worker/) ⭐️ 8.0/10

Cloudflare has announced the general availability of Python Workers, enabling developers to run Python code in their server-side Workers after a two-year preview period. This marks a significant expansion of Cloudflare's developer platform, offering Python support alongside existing languages like JavaScript, and is likely to attract developers seeking more language flexibility in cloud services. Python code is run via Pyodide, compiled to WebAssembly, in Cloudflare's V8-based workerd runtime, with limitations such as non-functional multiprocessing and threading in the WebAssembly VM.

rss · Simon Willison · Sep 21, 22:25

**Background**: Cloudflare Workers are serverless computing environments that allow developers to run code in response to events without managing servers. WebAssembly is a low-level programming language designed for efficient execution by modern web browsers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly - Wikipedia</a></li>
<li><a href="https://blog.cloudflare.com/python-workers/">Bringing Python to Workers using Pyodide and WebAssembly | Cloudflare Blog</a></li>
<li><a href="https://almarklein.org/python_and_webassembly.html">Python and WebAssembly</a></li>
<li><a href="https://pyodide.com/">Home - Pyodide</a></li>
<li><a href="https://blog.cloudflare.com/python-workers-ga/">Python Workers are now generally available | Cloudflare Blog</a></li>
<li><a href="https://developers.cloudflare.com/workers/languages/python/how-python-workers-work/">How Python Workers Work · Cloudflare Workers docs</a></li>
<li><a href="https://blog.cloudflare.com/python-workers/">Bringing Python to Workers using Pyodide and WebAssembly | Cloudflare Blog</a></li>

</ul>
</details>

**Discussion**: The community discussion is expected to focus on the benefits of Python support in Cloudflare Workers, potential use cases, and comparisons with other cloud services.

**Tags**: `#Cloudflare`, `#Python`, `#WebAssembly`, `#Cloud Services`, `#Developer Tools`

---

<a id="item-6"></a>
## [Enhancing Kimi Delta Attention Mechanism](https://www.reddit.com/r/MachineLearning/comments/1wn5uv9/understanding_and_enhancing_kimi_delta_attention_r/) ⭐️ 8.0/10

The paper introduces Complex KDA, an extension of Kimi Delta Attention that supports 2D rotations and demonstrates its potential in audio continuation and language modelling. This development is significant as it enhances the expressivity of Kimi Delta Attention, potentially leading to more advanced applications in machine learning and AI. Complex KDA allows for 2D rotations in a single step, requires an extended gate range, and has a specific learning rate range. It can express orthogonal diagonal-plus-rank-one matrices and track certain groups.

reddit · r/MachineLearning · /u/Yossarian_1234 · Sep 22, 10:34

**Background**: Kimi Delta Attention is a linear attention mechanism that enhances the use of finite memory states in recurrent neural networks. It is part of the Kimi Linear architecture.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/papers/2510.26692">Kimi Linear: Expressive & Efficient Attention</a></li>
<li><a href="https://arxiv.org/pdf/2510.26692">Kimi Linear: An Expressive, Efficient Attention Architecture</a></li>
<li><a href="https://www.linkedin.com/pulse/attention-memory-what-kda-changes-long-context-binod-kumar-5inef">Attention Is Not Memory: What KDA Changes About Long-Context...</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion shows a high level of interest and engagement, with comments focusing on the technical details and potential applications of Complex KDA.

**Tags**: `#MachineLearning`, `#NeuralNetworks`, `#AttentionMechanisms`, `#Research`, `#AI`

---