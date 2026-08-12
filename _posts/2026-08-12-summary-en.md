---
layout: default
title: "Horizon Summary: 2026-08-12 (EN)"
date: 2026-08-12
lang: en
---

> From 39 items, 9 important content pieces were selected

---

1. [Stealing Reasoning Traces from Proprietary LLM APIs](#item-1) ⭐️ 9.0/10
2. [Meta Introduces Muse Glimmer](#item-2) ⭐️ 9.0/10
3. [Decoupled Descent: Exact Train-Test Error Tracking](#item-3) ⭐️ 9.0/10
4. [Fru: Fast Random Forest in Rust](#item-4) ⭐️ 9.0/10
5. [Llama.cpp Framework Update](#item-5) ⭐️ 8.0/10
6. [Nvidia Introduces Nemotron 3.5 Lightning and NeMo Switchyard](#item-6) ⭐️ 8.0/10
7. [Grok Bot Unveiled: A New Era in AI Agent Interaction](#item-7) ⭐️ 8.0/10
8. [No Lossless Transformations in NLP](#item-8) ⭐️ 8.0/10
9. [Agentic World Cup: LLMs Compete in 1v1 Soccer](#item-9) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Stealing Reasoning Traces from Proprietary LLM APIs](https://simonwillison.net/2026/Aug/11/stealing-reasoning-traces/#atom-everything) ⭐️ 9.0/10

A paper demonstrates a method to extract reasoning traces from proprietary LLM APIs, revealing how encrypted chain-of-thought blocks can be replayed and decrypted to uncover hidden reasoning processes. This breakthrough enhances transparency in AI decision-making processes and could lead to better understanding and trust in AI systems. The research involved replaying traces from a stronger model into a weaker one, jailbreaking the weaker model to recover the stronger model's hidden reasoning in plaintext.

rss · Simon Willison · Aug 11, 22:40

**Background**: LLM APIs are interfaces that allow applications to interact with large language models, while encrypted chain-of-thought blocks are used to keep the internal reasoning processes of AI models private.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ibm.com/think/insights/llm-apis">LLM APIs: Tips for Bridging the Gap | IBM</a></li>
<li><a href="https://docs.api.nvidia.com/nim/reference/llm-apis">LLM APIs</a></li>
<li><a href="https://www.giskard.ai/glossary/llm-apis">LLM APIs | Accessing Large Language Models via API</a></li>
<li><a href="https://blog.cryptographyengineering.com/2026/05/29/fooling-around-with-encrypted-reasoning-blobs/">Let’s talk about encrypted reasoning – A Few Thoughts on Cryptographic Engineering</a></li>
<li><a href="https://explainx.ai/blog/stealing-reasoning-traces-encrypted-cot-vulnerability-august-2026">Encrypted CoT Flaw: 182 Credentials Leaked from Public Logs | explainx.ai Blog | explainx.ai</a></li>
<li><a href="https://www.wired.com/story/a-new-trick-reveals-ai-models-inner-thoughts/">A New Trick Reveals AI Models’ Inner Thoughts | WIRED</a></li>
<li><a href="https://simonwillison.net/2026/Aug/11/stealing-reasoning-traces/">Stealing Reasoning Traces from Proprietary LLM APIs</a></li>
<li><a href="https://arxiv.org/pdf/2608.09867">Stealing Reasoning Traces from Proprietary LLM APIs</a></li>
<li><a href="https://www.toxsec.com/p/openai-signs-what-anthropic-wouldnt">OpenAI Signs What Anthropic Wouldn't, Models Break Everything...</a></li>

</ul>
</details>

**Discussion**: The community is divided on the implications of this research, with some praising the potential for increased transparency and others expressing concerns about security and privacy risks.

**Tags**: `#AI Research`, `#Machine Learning`, `#LLM APIs`, `#Security`, `#Transparency`

---

<a id="item-2"></a>
## [Meta Introduces Muse Glimmer](https://simonwillison.net/2026/Aug/10/introducing-muse-glimmer/#atom-everything) ⭐️ 9.0/10

Meta has introduced Muse Glimmer, a new 30B open-source AI model optimized for agentic task completion and reliable tool use, under an Apache 2.0 license. This new model is significant as it pushes the boundaries of AI by focusing on agentic task completion and reliable tool use, which could lead to more sophisticated and practical AI applications. Muse Glimmer is designed to handle end-to-end agentic task completion, reliable tool use, and multi-step reasoning, making it a powerful tool for AI research and development.

rss · Simon Willison · Aug 10, 23:56

**Background**: Agentic AI models are designed to perform tasks that require understanding and acting in the world, similar to how humans do. The Apache 2.0 license is a permissive open-source license that allows for the use, modification, and distribution of software.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? | IBM</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apache_License">Apache License - Wikipedia</a></li>
<li><a href="https://tech.yahoo.com/ai/meta-ai/articles/maybe-run-metas-latest-ai-210000951.html">Muse Glimmer is designed to run locally—if your hardware can keep up.</a></li>

</ul>
</details>

**Discussion**: Community discussions are expected to focus on the potential impact of Muse Glimmer on AI development, its practical applications, and the implications of its open-source nature.

**Tags**: `#AI Research`, `#Machine Learning`, `#Open Source`, `#AI Models`, `#Meta AI`

---

<a id="item-3"></a>
## [Decoupled Descent: Exact Train-Test Error Tracking](https://www.reddit.com/r/MachineLearning/comments/1vlu1se/decoupled_descent_enforcing_exact_traintest_error/) ⭐️ 9.0/10

A novel training method called Decoupled Descent (DD) is proposed to ensure that training and testing errors in neural networks are equal at each parameter iterate, using approximate message passing (AMP) and Onsager corrections. This method addresses the issue of data reuse bias in neural network training, potentially leading to more reliable models and impacting the field of machine learning by providing a new approach to training. Decoupled Descent uses AMP and Onsager corrections to decouple errors across layers, ensuring that training errors asymptotically track test errors.

reddit · r/MachineLearning · /u/mlovik1 · Aug 11, 21:06

**Background**: Neural network training often faces the problem of data reuse bias, where training errors may decrease while test errors remain high. Approximate message passing (AMP) and Onsager corrections are techniques from high-dimensional statistical theory.

<details><summary>References</summary>
<ul>
<li><a href="https://joanbruna.notion.site/Approximate-Message-Passing-182ae374e2f88141bbc6c4f80e462aaf">Approximate Message Passing | Notion</a></li>
<li><a href="https://www.emergentmind.com/topics/attention-as-message-passing">Attention as Message Passing</a></li>
<li><a href="https://scispace.com/papers/message-passing-meets-graph-neural-networks-a-new-paradigm-tyoyd6sr">(PDF) Message Passing Meets Graph Neural Networks : A New...</a></li>
<li><a href="https://arxiv.org/abs/1607.05966">[1607.05966] Onsager-corrected deep learning for sparse linear inverse problems</a></li>
<li><a href="https://www.researchgate.net/publication/316903092_Onsager-corrected_deep_learning_for_sparse_linear_inverse_problems">Onsager-corrected deep learning for sparse linear inverse problems | Request PDF</a></li>
<li><a href="https://sigport.org/sites/default/files/docs/slides_0.pdf">Onsager Correction, Deep Learning, Sparse Reconstruction and VAMP</a></li>
<li><a href="https://arxiv.org/html/2604.27883">Decoupled Descent: Exact Test Error Tracking Via Approximate Message Passing</a></li>
<li><a href="https://arxiv.org/html/2509.10973">Decoupling Search and Learning in Neural Net Training</a></li>

</ul>
</details>

**Discussion**: The Reddit community has shown interest in the topic, with discussions focusing on the potential impact of Decoupled Descent on machine learning and its practical applications.

**Tags**: `#MachineLearning`, `#NeuralNetworks`, `#TrainingMethods`, `#ResearchBreakthrough`, `#DeepLearning`

---

<a id="item-4"></a>
## [Fru: Fast Random Forest in Rust](https://www.reddit.com/r/MachineLearning/comments/1vkrvks/fru_fast_random_forest_implementation_p/) ⭐️ 9.0/10

A Rust-based Random Forest implementation called Fru has been developed, offering superior performance and scalability compared to existing libraries in Python and R. This new implementation could significantly impact machine learning workflows by providing faster processing times and better scalability, potentially leading to more efficient models and reduced computational costs. Fru outperforms scikit-learn in Python and the ranger package in R, with potential speedups of hundreds of times in certain scenarios. It also includes a novel permutation importance implementation for enhanced performance.

reddit · r/MachineLearning · /u/kpiwonski · Aug 10, 17:45

**Background**: Rust is known for its performance and safety, making it a suitable choice for machine learning applications. Permutation importance is a technique used to measure feature importance in machine learning models.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Rust_(programming_language)">Rust ( programming language ) - Wikipedia</a></li>
<li><a href="https://baotramduong.medium.com/understanding-permutation-importance-in-machine-learning-a218821fd71a">Explainable AI (XAI): Understanding Permutation Importance in ...</a></li>
<li><a href="https://arrow.apache.org/docs/format/CDataInterface/PyCapsuleInterface.html">The Arrow PyCapsule Interface — Apache Arrow v25.0.1</a></li>

</ul>
</details>

**Discussion**: The Reddit community has shown interest in Fru, with discussions focusing on its performance improvements and potential applications in various fields.

**Tags**: `#MachineLearning`, `#RandomForest`, `#Optimization`, `#Cross-Language`, `#Rust`

---

<a id="item-5"></a>
## [Llama.cpp Framework Update](https://llama.app/) ⭐️ 8.0/10

The llama.cpp AI model inference framework has been updated, with new features like multi-model support and optimized performance for specific hardware. This update is significant as it enhances the usability and efficiency of llama.cpp, making it a preferred choice for local AI model deployment over other inference frameworks. Llama.cpp supports various features for edge device inference, including automatic selection of quantization kernels and optimized attention mechanisms for real-time response generation.

hackernews · kristianpaul · Aug 12, 04:51 · [Discussion](https://news.ycombinator.com/item?id=49267928)

**Background**: An AI model inference framework is a tool that allows for the efficient processing of AI models on various devices, optimizing performance and resource usage.

<details><summary>References</summary>
<ul>
<li><a href="https://www.thecivilindia.com/technology/search-engine-vs-inference-engine/">Search Engine vs Inference Engine: Is the Web... - The Civil India</a></li>
<li><a href="https://dev.to/eli_9c82b7dfe52c1bc371ffe/developers-launch-tiny-vllm-a-lightweight-engine-for-fast-ai-model-inference-1eim">Developers Launch Tiny-vLLM, a Lightweight Engine for Fast AI Model ...</a></li>
<li><a href="https://www.aibase.com/tool/34260">LLaMA-O1-A large inference model framework that supports PyTorch...</a></li>

</ul>
</details>

**Discussion**: Community members have expressed positive feedback on llama.cpp, highlighting its ease of use, performance, and the active development of new features.

**Tags**: `#AI`, `#MachineLearning`, `#InferenceFramework`, `#OpenSource`, `#Community`

---

<a id="item-6"></a>
## [Nvidia Introduces Nemotron 3.5 Lightning and NeMo Switchyard](https://blogs.nvidia.com/blog/nemotron-lightning-switchyard-rtx-dgx/) ⭐️ 8.0/10

Nvidia has launched Nemotron 3.5 Lightning and NeMo Switchyard, focusing on efficient AI model routing and performance. Nemotron 3.5 Lightning is an open 30B MoE model, while NeMo Switchyard is an open-source library for smart routing. This development is significant as it enhances AI model efficiency and routing, potentially leading to better resource utilization and performance in AI applications. Nemotron 3.5 Lightning is optimized for high-volume, specialized tasks, while NeMo Switchyard offers intelligent routing to the most suitable model for each request.

hackernews · droidjj · Aug 11, 19:35 · [Discussion](https://news.ycombinator.com/item?id=49263340)

**Background**: AI model routing is a practice that automatically selects the best-suited model for each query, optimizing performance and cost. NVIDIA's NeMo Switchyard and Nemotron 3.5 Lightning are part of this trend.

<details><summary>References</summary>
<ul>
<li><a href="https://www.routera.one/blog/what-is-llm-routing">What Is LLM Routing ? A Practical Guide to AI Model Routers | Routera</a></li>
<li><a href="https://developer.nvidia.com/blog/nvidia-nemotron-3-5-lightning-delivers-fast-accurate-specialized-task-execution-for-long-running-agents/">NVIDIA Nemotron 3 . 5 Lightning Delivers Fast, Accurate Specialized...</a></li>

</ul>
</details>

**Discussion**: Community discussions highlight the potential of these technologies but also raise concerns about their performance with certain tasks and the need for further optimization.

**Tags**: `#AI Efficiency`, `#Model Routing`, `#Nvidia`, `#Machine Learning`, `#AI Development`

---

<a id="item-7"></a>
## [Grok Bot Unveiled: A New Era in AI Agent Interaction](https://x.ai/bot) ⭐️ 8.0/10

Grok Bot has been introduced as a new AI agent technology, marking a significant evolution in bot interaction. Users have expressed both enthusiasm and concerns about its capabilities and security implications. The introduction of Grok Bot is significant as it represents a potential shift in how we interact with bots, potentially impacting various industries and user experiences. It also raises important questions about security and privacy in AI. Grok Bot allows bots to own their own routines, context, and domain, and communicate with each other. However, concerns have been raised about the security of user credentials and the potential for data breaches.

hackernews · rvz · Aug 11, 17:23 · [Discussion](https://news.ycombinator.com/item?id=49261514)

**Background**: AI agents are advanced forms of bots that can perform complex tasks and interact with users in more sophisticated ways. They are different from regular bots, which typically follow predefined scripts.

<details><summary>References</summary>
<ul>
<li><a href="https://leesiangfong.com/what-is-an-agentic-ai-agent-and-why-you-shouldnt-confuse-it-with-a-chatbot/">What Is an Agentic AI Agent ? (And Why You Shouldn’t Confuse It with...</a></li>
<li><a href="https://dev.to/trismegistus/the-web-is-drowning-in-bot-traffic-and-ai-agents-are-making-it-worse-12ej">The Web Is Drowning in Bot Traffic — and AI Agents Are Making It ...</a></li>
<li><a href="https://dianapps.com/blog/create-an-ai-chatbot-like-grok/">How to Create an AI Chatbot Like Grok in 2026 (Full Guide)</a></li>

</ul>
</details>

**Discussion**: Community discussions highlight excitement about the potential of the technology, but also concerns about security vulnerabilities and the legal implications of using bots for data scraping and interaction.

**Tags**: `#AI`, `#Bot Technology`, `#Security`, `#AI Agents`, `#Community Interest`

---

<a id="item-8"></a>
## [No Lossless Transformations in NLP](https://simonwillison.net/2026/Aug/11/there-are-no-lossless-transformations-of-natural-language-text/#atom-everything) ⭐️ 8.0/10

Sophie Alpert emphasizes the importance of accountability in using AI-generated text in engineering documentation, advocating for engineers to stand behind every idea and sentence. This perspective is significant as it sets a policy for using AI in natural language processing, which could influence best practices in engineering and documentation, especially in the context of AI ethics. The concept of 'no lossless transformations' suggests that every rewrite and rephrase of natural-language text changes its meaning, and AI-generated text may lead to information loss.

rss · Simon Willison · Aug 11, 23:48

**Background**: Natural language processing (NLP) involves the interaction between computers and humans through natural language. AI-generated text has become a topic of debate due to its potential impact on accuracy and accountability.

<details><summary>References</summary>
<ul>
<li><a href="https://dev.to/arvind_sundararajan/shrinking-the-giants-lossless-nlp-compression-for-everyone-by-arvind-sundararajan-1o3o">Shrinking the Giants: Lossless NLP Compression... - DEV Community</a></li>
<li><a href="https://www.linkedin.com/posts/katie-miserany_there-are-no-lossless-transformations-of-activity-7491169182865293312-hLj8">There are no lossless transformations of natural-language text</a></li>
<li><a href="https://www.unesco.org/en/artificial-intelligence/recommendation-ethics">Ethics of Artificial Intelligence - AI | UNESCO</a></li>

</ul>
</details>

**Discussion**: The community discussion focuses on the challenges of using AI-generated text in engineering, with some agreeing that accountability is crucial and others questioning the feasibility of manual review.

**Tags**: `#AI in Engineering`, `#Natural Language Processing`, `#Documentation Best Practices`, `#AI Ethics`, `#Software Engineering`

---

<a id="item-9"></a>
## [Agentic World Cup: LLMs Compete in 1v1 Soccer](https://www.reddit.com/r/MachineLearning/comments/1vllvmn/we_built_the_agentic_world_cup_llms_that_compete/) ⭐️ 8.0/10

The Agentic World Cup is a platform where large language models (LLMs) compete in 1v1 soccer matches, aiming to address the embodiment gap in AI by training agents to think like athletes. This initiative is significant as it represents a novel approach to closing the embodiment gap in AI, potentially leading to more human-like decision-making and problem-solving capabilities in AI agents. The platform allows users to sign in, select an LLM coach, and submit their agent for competition. The agents compete in real-time soccer matches, with rankings and performance data published on the site.

reddit · r/MachineLearning · /u/agenticworldcup · Aug 11, 16:12

**Background**: The embodiment gap in AI refers to the lack of physical interaction and understanding of the environment in AI systems. Embodied AI aims to bridge this gap by creating AI that can perceive and interact with the physical world.

<details><summary>References</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=9seBcLiLCGY">The Embodiment Gap : Why AI Adoption Was Never the... - YouTube</a></li>
<li><a href="https://theconsciousness.ai/posts/kadambi-embodiment-multimodal-llm-consciousness-2026/">The Body Gap : Why AI Still Can't Know What... | The Consciousness AI</a></li>
<li><a href="https://www.sciencetimes.com/articles/61450/20260311/embodiment-gap-why-robots-struggle-learn-humans.htm">The Embodiment Gap : Why Robots Struggle to Learn from Humans</a></li>
<li><a href="https://modernorange.io/item/49259735">Show HN: We Built the Agentic World Cup – LLMs Competing in...</a></li>
<li><a href="https://www.linkedin.com/pulse/embodied-ai-vs-physical-whats-real-difference-hari-lakshman-r-b-sbhne">Embodied AI vs. Physical AI : What's the Real Difference ?</a></li>
<li><a href="https://www.sensorlidar.com/blogs/news/qiaoyin-robot-explained-how-embodied-ai-is-transforming-smart-cities">QiaoYin Robot Explained: How Embodied AI Is Transforming Smart...</a></li>
<li><a href="https://rnwy.com/learn/what-is-ai-embodiment">What Is AI Embodiment ? The Race to Give AI a Body | RNWY</a></li>

</ul>
</details>

**Discussion**: The community has shown interest in the project, with discussions focusing on the potential of LLMs in sports, the challenges of embodied AI, and the future of AI competition.

**Tags**: `#AI Embodiment`, `#Machine Learning`, `#LLM Applications`, `#AI Sports`, `#Embodied AI`

---