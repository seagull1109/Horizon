---
layout: default
title: "Horizon Summary: 2026-06-25 (EN)"
date: 2026-06-25
lang: en
---

> From 55 items, 6 important content pieces were selected

---

1. [Anthropic Accuses Alibaba of Claude AI Theft](#item-1) ⭐️ 8.0/10
2. [OpenAI unveils first custom AI chip](#item-2) ⭐️ 8.0/10
3. [Superhuman Generals.io Agent with Self-Play RL](#item-3) ⭐️ 8.0/10
4. [HDD-RoPE Positional Embedding Method](#item-4) ⭐️ 8.0/10
5. [DeepSWE: New Code Benchmark](#item-5) ⭐️ 8.0/10
6. [LLM Inference Pricing Comparison Reveals Caching Surprises](#item-6) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Anthropic Accuses Alibaba of Claude AI Theft](https://www.reuters.com/world/china/anthropic-says-alibaba-illicitly-extracted-claude-ai-model-capabilities-2026-06-24/) ⭐️ 8.0/10

Anthropic has accused Alibaba of illicitly extracting Claude AI model capabilities through distillation attacks, sparking a legal dispute between the companies. This dispute highlights growing tensions in the AI industry over intellectual property protection and raises questions about the ethics of model training and competition in the global AI market. Distillation attacks involve repeatedly querying a proprietary model to extract its knowledge and train competing models, which Anthropic claims violates their intellectual property rights and terms of service.

hackernews · htrp · Jun 24, 19:48 · [Discussion](https://news.ycombinator.com/item?id=48664814)

**Background**: Claude is a series of large language models developed by Anthropic, released as an AI chatbot in March 2023. Distillation attacks are security threats where attackers steal knowledge from proprietary models by using input-output pairs to train new competing models. This case reflects broader concerns about AI ethics, intellectual property, and corporate competition in the rapidly evolving AI landscape.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/detecting-and-preventing-distillation-attacks">Detecting and preventing distillation attacks \ Anthropic</a></li>
<li><a href="https://medium.com/@tahirbalarabe2/understanding-llm-distillation-attacks-929306ca38cd">Understanding LLM Distillation Attacks | by Tahir | Medium</a></li>
<li><a href="https://cloud.google.com/blog/topics/threat-intelligence/distillation-experimentation-integration-ai-adversarial-use">GTIG AI Threat Tracker: Distillation, Experimentation, and (Continued) Integration of AI for Adversarial Use | Google Cloud Blog</a></li>

</ul>
</details>

**Discussion**: The community debate is divided, with some criticizing Anthropic's claims as hypocritical given their own use of public data for training, while others defend the company's position on protecting intellectual property. There's also discussion about the technical aspects of distillation attacks and their implications for AI development and regulation.

**Tags**: `#AI Ethics`, `#Intellectual Property`, `#Corporate Competition`, `#Legal Disputes`, `#AI Model Training`

---

<a id="item-2"></a>
## [OpenAI unveils first custom AI chip](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 8.0/10

OpenAI has unveiled its first custom AI inference chip called 'Jalapeno', developed in partnership with Broadcom, designed to optimize performance for large language models like ChatGPT and Codex. This represents a significant vertical integration move for OpenAI as it expands beyond consumer products to become a player in AI infrastructure, potentially reducing costs and improving efficiency for its AI services. The Jalapeno chip was developed from design to production in just nine months, with some aspects of the design and optimization process accelerated by OpenAI's own models, though specific details about this were limited in the announcement.

hackernews · jamdesk · Jun 24, 17:47 · [Discussion](https://news.ycombinator.com/item?id=48663324)

**Background**: AI inference chips are specialized processors designed to efficiently run AI models during the inference phase (when the model makes predictions), as opposed to training. Companies like Google (with TPUs), AWS (with Inferentia), and others have been developing custom chips to optimize AI workloads, reduce costs, and improve performance. Inference optimization techniques include KV caching, batching, and specialized hardware architectures to handle the unique computational demands of large language models.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip | OpenAI</a></li>
<li><a href="https://www.cnbc.com/2026/06/24/openai-and-broadcom-reveal-jalapeno-first-ai-chip-in-partnership.html">OpenAI and Broadcom reveal Jalapeno, first AI chip in partnership</a></li>
<li><a href="https://developer.nvidia.com/blog/mastering-llm-techniques-inference-optimization/">Mastering LLM Techniques: Inference Optimization | NVIDIA Technical Blog</a></li>

</ul>
</details>

**Discussion**: Community members expressed interest in the nine-month development timeline, questioning how much OpenAI's models actually contributed to the acceleration. Others noted the chip is manufactured by TSMC and discussed competing approaches like Taalas, which burns LLM models directly into silicon for potentially greater efficiency gains.

**Tags**: `#AI hardware`, `#custom chips`, `#OpenAI`, `#semiconductor`, `#inference optimization`

---

<a id="item-3"></a>
## [Superhuman Generals.io Agent with Self-Play RL](https://www.reddit.com/r/MachineLearning/comments/1uei2yg/i_made_a_superhuman_generalsio_agent_with/) ⭐️ 8.0/10

A self-play reinforcement learning agent for Generals.io achieved superhuman performance and reached #1 on the human 1v1 leaderboard by implementing JAX and Vision Transformer architecture instead of previous CNN-based approaches. This represents a significant technical achievement in reinforcement learning for imperfect-information games, demonstrating that scaling through computational efficiency rather than human priors can lead to breakthrough performance in strategic games. The agent was trained using behavior cloning, RL fine-tuning and reward shaping, with the key improvements being the complete reimplementation in JAX (replacing NumPy/Torch) and the adoption of Vision Transformer architecture over CNN.

reddit · r/MachineLearning · /u/shrekofspeed · Jun 24, 16:18

**Background**: Generals.io is a real-time strategy game with imperfect information, where players cannot see the entire map. Self-play reinforcement learning is a technique where agents learn by playing against themselves, creating a powerful feedback loop for improvement. Vision Transformers are neural network architectures that adapt transformer models originally designed for natural language processing to computer vision tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Self-play_(reinforcement_learning_technique)">Self-play (reinforcement learning technique)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vision_transformer">Vision transformer</a></li>
<li><a href="https://en.wikipedia.org/wiki/JAX_(software)">JAX (software) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The Reddit post indicates substantial community interest in the technical approach and open-source implementation, with particular focus on the JAX simulator and the Vision Transformer architecture's application to imperfect-information real-time strategy games.

**Tags**: `#reinforcement-learning`, `#self-play`, `#generals.io`, `#vision-transformer`, `#JAX`

---

<a id="item-4"></a>
## [HDD-RoPE Positional Embedding Method](https://www.reddit.com/r/MachineLearning/comments/1uelcm9/high_dimensional_dynamic_rotary_positional/) ⭐️ 8.0/10

Researchers have developed HDD-RoPE, a novel positional embedding method that breaks position information into multidimensional chunks instead of the traditional two-dimensional approach, showing faster convergence rates in transformer models compared to xPos. This advancement could significantly improve training efficiency for transformer models, potentially reducing computational resources needed for large language model training and enabling faster model development cycles. HDD-RoPE breaks chunks into any size (e.g., 4-dimensional chunks corresponding to 6 axes of rotation) and makes rotation along each axis data-dependent, allowing the model to learn positions within various constructs like paragraphs or sentences.

reddit · r/MachineLearning · /u/mikayahlevi · Jun 24, 18:16

**Background**: Positional encoding is essential in transformer models to address their permutation invariance and enable understanding of sequential relationships. Traditional RoPE breaks queries and keys into groups of two and rotates each pair at a predefined rate, allowing models to learn relative position by observing changes in basis between queries and keys.

<details><summary>References</summary>
<ul>
<li><a href="https://iclr-blogposts.github.io/2025/blog/positional-embedding/">Positional Embeddings in Transformer Models: Evolution from Text to Vision Domains | ICLR Blogposts 2025</a></li>
<li><a href="https://machinelearningmastery.com/a-gentle-introduction-to-positional-encoding-in-transformer-models-part-1/">A Gentle Introduction to Positional Encoding in Transformer Models, Part 1 - MachineLearningMastery.com</a></li>
<li><a href="https://en.wikipedia.org/wiki/Transformer_models">Transformer models</a></li>

</ul>
</details>

**Tags**: `#transformers`, `#positional-embeddings`, `#machine-learning`, `#research`, `#nlp`

---

<a id="item-5"></a>
## [DeepSWE: New Code Benchmark](https://www.reddit.com/r/MachineLearning/comments/1ue0hlp/deepswe_new_benchmark_looking_at_how_well_todays/) ⭐️ 8.0/10

DeepSWE introduces a new contamination-free benchmark that evaluates how well today's frontier models can write code across diverse repositories with real-world complexity. This benchmark addresses important limitations in existing evaluation frameworks and provides a more accurate assessment of frontier coding agents' capabilities, potentially reshaping how we evaluate AI coding performance. DeepSWE features tasks written from scratch (not adapted from existing commits), spans 91 repositories across 5 languages, uses prompts that are half the length of SWE-bench Pro's but require 5.5x more code, and employs hand-written verifiers that test software behavior rather than implementation details.

reddit · r/MachineLearning · /u/we_are_mammals · Jun 24, 02:03

**Background**: Code generation benchmarks are essential for evaluating AI coding capabilities, but many existing benchmarks suffer from contamination issues where models may have seen solutions during pretraining. Software engineering evaluation has become increasingly important as AI coding agents like Devin become more prevalent in development workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://deepswe.datacurve.ai/">DeepSWE</a></li>
<li><a href="https://benchlm.ai/benchmarks/deepSwe">DeepSWE Benchmark 2026: 8 pass@1 rows | BenchLM.ai</a></li>
<li><a href="https://venturebeat.com/technology/deepswe-blows-up-the-ai-coding-leaderboard-crowns-gpt-5-5-and-finds-claude-opus-exploiting-a-benchmark-loophole">DeepSWE blows up the AI coding leaderboard, crowns GPT-5.5, and finds Claude Opus exploiting a benchmark loophole | VentureBeat</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion shows moderate engagement with several insightful comments about the benchmark's methodology and implications, though specific viewpoints aren't detailed in the provided content.

**Tags**: `#benchmark`, `#code-generation`, `#software-engineering`, `#evaluation`, `#AI`

---

<a id="item-6"></a>
## [LLM Inference Pricing Comparison Reveals Caching Surprises](https://www.reddit.com/r/MachineLearning/comments/1ueavxn/i_compiled_llm_inference_pricing_across_7/) ⭐️ 8.0/10

A comprehensive pricing comparison of LLM inference across 7 providers shows dramatic cost differences for cached inputs, with some cache hits being tens of times cheaper than cache misses. This analysis is significant for developers and businesses deploying LLM applications, as caching policies can have a greater impact on costs than the headline token price, especially for agents with large system prompts, RAG pipelines, and multi-turn conversations. The comparison reveals that the same model can vary by multiple times in cost depending on the provider, and while some providers clearly expose caching options, others barely document them. The spreadsheet tracks input/output token pricing, context windows, cached input pricing, and supported models across providers.

reddit · r/MachineLearning · /u/Technomadlyf · Jun 24, 11:28

**Background**: LLM inference pricing refers to the cost of running AI models through APIs, typically measured per token (a unit of text). Context window is the maximum amount of text a model can consider at once when generating output. Caching allows providers to store frequently used inputs, dramatically reducing costs when those inputs are reused.

<details><summary>References</summary>
<ul>
<li><a href="https://epoch.ai/data-insights/llm-inference-price-trends">LLM inference prices have fallen rapidly but unequally across tasks | Epoch AI</a></li>
<li><a href="https://featherless.ai/blog/llm-api-pricing-comparison-2026-complete-guide-inference-costs">LLM API Pricing Comparison 2026: The Complete Guide to Inference Costs - Featherless</a></li>
<li><a href="https://developer.nvidia.com/blog/llm-inference-benchmarking-how-much-does-your-llm-inference-cost/">LLM Inference Benchmarking: How Much Does Your LLM Inference Cost? | NVIDIA Technical Blog</a></li>

</ul>
</details>

**Discussion**: The Reddit post generated discussion about real-world implications of caching policies, with users sharing their experiences with different providers and suggesting additional metrics to consider beyond token pricing, such as throughput, cold-start times, and reliability.

**Tags**: `#LLM`, `#pricing`, `#inference`, `#cost-optimization`, `#caching`

---