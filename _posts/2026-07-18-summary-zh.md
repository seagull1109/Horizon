---
layout: default
title: "Horizon Summary: 2026-07-18 (ZH)"
date: 2026-07-18
lang: zh
---

> 从 33 条内容中筛选出 8 条重要资讯。

---

1. [首次在宜居带类地行星上发现大气层](#item-1) ⭐️ 9.0/10
2. [Kimi K3：Moonshot AI 的 2.8T 参数模型与鹈鹕基准测试](#item-2) ⭐️ 8.0/10
3. [Firefox 被编译为 WebAssembly](#item-3) ⭐️ 8.0/10
4. [Thinking Machines Lab 发布 Inkling 开源权重多模态模型](#item-4) ⭐️ 8.0/10
5. [Linus Torvalds 澄清 Linux 对 AI 的立场](#item-5) ⭐️ 8.0/10
6. [Stereo2Spatial：将立体声音乐转换为空间化双耳混音](#item-6) ⭐️ 8.0/10
7. [欧盟 AI 法案 OpenRAG：933 个法律结构化块与 BGE-M3 嵌入，存于一个 SQLite 文件中](#item-7) ⭐️ 8.0/10
8. [ExTernD：一种用于大语言模型的创新三元后训练量化方法](#item-8) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [首次在宜居带类地行星上发现大气层](https://www.bbc.com/news/articles/cy4kdd1e0ejo) ⭐️ 9.0/10

科学家首次在宜居带类地行星上发现了大气层，这是在寻找太阳系外宜居世界方面取得的重大突破。 这一发现意义重大，因为它标志着在寻找地外生命和宜居行星方面迈出了重要一步。它表明宜居带的类地行星可以保留大气层，这对于支持我们所知的生命至关重要。 该行星 LHS 1140b 距离地球 48 光年，围绕一颗红矮星运行。大气层是通过 JWST 光谱学检测到的，排除了它是迷你海王星的可能性。

hackernews · neversaydie · 7月17日 14:06 · [社区讨论](https://news.ycombinator.com/item?id=48947560)

**背景**: 宜居带，也称为金发姑娘区，是指围绕恒星运行的轨道范围，在该范围内行星表面可能存在液态水。这对于我们所知的生命至关重要。大多数之前在宜居带发现的系外行星要么是超级地球，要么是气态巨行星，这使得这次在宜居带发现拥有大气层的类地行星尤为意义重大。系外行星的大气层检测具有挑战性，通常依赖于光谱学等间接方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Habitable_zone">Habitable zone</a></li>
<li><a href="https://science.nasa.gov/exoplanets/habitable-zone/">The Habitable Zone - NASA Science</a></li>
<li><a href="https://www.britannica.com/science/habitable-zone">Habitable zone | Astrobiology, Exoplanets & Habitability | Britannica</a></li>

</ul>
</details>

**社区讨论**: 社区成员对这颗行星是否真正类地表示怀疑，一位评论者指出红矮星已知不稳定，LHS 1140b 可能更像迷你海王星。然而，另一位评论者引用了 JWST 发射光谱学，排除了迷你海王星的可能性。还有人讨论了未来探索这颗行星的可行性以及对费米悖论的影响。

**标签**: `#astronomy`, `#exoplanets`, `#space science`, `#habitable zone`, `#atmospheric detection`

---

<a id="item-2"></a>
## [Kimi K3：Moonshot AI 的 2.8T 参数模型与鹈鹕基准测试](https://simonwillison.net/2026/Jul/16/kimi-k3/#atom-everything) ⭐️ 8.0/10

Moonshot AI 宣布了 Kimi K3，一个 2.8 万亿参数的模型，声称是首个开放 3T 级模型，其自我报告的基准测试显示它大多优于 Claude Opus 4.8 max 和 GPT-5.5 high，目前可通过其网站和 API 使用，并承诺在 2026 年 7 月 27 日前发布开放权重版本。 这很重要，因为 Kimi K3 代表了中国 AI 发展的重大进步，可能在某些基准测试中挑战 Claude 和 GPT 等成熟模型，而其开放权重发布可能会让开发者和研究人员更容易获得最先进的 AI 技术。 Kimi K3 的定价为每百万输入 token 3 美元，每百万输出 token 15 美元，使其成为中国 AI 实验室发布的最昂贵的模型，并且在 token 效率方面有显著提升，比其前身 Kimi K2.6 少使用 21%的输出 token。

rss · Simon Willison · 7月16日 20:19 · [社区讨论](https://news.ycombinator.com/item?id=48947717)

**背景**: 大型语言模型（LLM）是经过海量文本数据训练以生成类人响应的 AI 系统。模型参数代表神经网络中的权重数量，通常参数越大的模型能力越强，但计算要求也越高。'鹈鹕基准测试'是 Simon Willison 创建的一个简单测试，用于比较不同 AI 模型如何处理创意图像生成任务，特别是创建一只骑自行车的鹈鹕的 SVG 图像。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you've been told</a></li>
<li><a href="https://huggingface.co/spaces/victor/pelican-benchmark">Pelican Benchmark - a Hugging Face Space by victor</a></li>
<li><a href="https://developer.nvidia.com/blog/scaling-language-model-training-to-a-trillion-parameters-using-megatron/">Scaling Language Model Training to a Trillion Parameters Using...</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调了鹈鹕基准测试的有效性问题，指出 Simon 的网站可能影响了模型训练数据，质疑不同模型之间的分词差异，并建议该基准测试没有测试重要的现代功能，如智能体工具调用。一些用户还指出需要进行多次运行以考虑模型输出的变异性。

**标签**: `#AI`, `#large language models`, `#model release`, `#benchmarking`, `#Kimi K3`

---

<a id="item-3"></a>
## [Firefox 被编译为 WebAssembly](https://simonwillison.net/2026/Jul/16/firefox-in-webassembly/#atom-everything) ⭐️ 8.0/10

Puter 成功将 Firefox 浏览器编译为 WebAssembly，使整个浏览器能够在另一个浏览器中运行。该项目利用了包括 Claude Opus 和 Fable 令牌在内的 AI 工具进行开发，并展示了先进的 WebAssembly 能力。 这一成就展示了 WebAssembly 的强大能力，并对浏览器架构和基于 Web 的应用程序具有潜在影响。它证明了像全功能浏览器这样的复杂软件可以在 Web 环境中运行，为 Web 开发开辟了新的可能性。 该项目使用了价值约 2.5 万美元的 Claude Opus 和 Fable 令牌进行开发，尽管订阅计划降低了实际成本。演示实现了端到端加密，并使用 Wisp 协议通过 Puter 的服务器代理所有流量，因为基于浏览器的代码无法打开任意网络连接。

rss · Simon Willison · 7月16日 23:34

**背景**: WebAssembly（WASM）是一种基于堆栈的虚拟机的二进制指令格式，设计为高级语言（如 C++、Rust 等）的编译目标，使这些语言能够在 Web 浏览器中实现接近原生的性能。Gecko 是开源的浏览器引擎，它为 Firefox 提供动力，以其强大的单进程支持而闻名，这使其适合此编译项目。Wisp 协议是一种低开销协议，设计用于通过单个 WebSocket 连接代理多个 TCP 和 UDP 套接字，对于这种浏览器中的浏览器实现至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/MercuryWorkshop/wisp-protocol">GitHub - MercuryWorkshop/ wisp - protocol : Wisp is a low-overhead...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Opus">Claude Opus</a></li>
<li><a href="https://en.wikipedia.org/wiki/Gecko">Gecko</a></li>

</ul>
</details>

**社区讨论**: 该项目在 Hacker News 上引发了大量讨论，团队在讨论期间不得不扩展服务器以处理流量。社区成员对这一技术成就表示惊叹，同时指出对代理方法的担忧及其广泛采用的可能成本。

**标签**: `#WebAssembly`, `#Browser`, `#Firefox`, `#AI`, `#WebDevelopment`

---

<a id="item-4"></a>
## [Thinking Machines Lab 发布 Inkling 开源权重多模态模型](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 8.0/10

Thinking Machines Lab 发布了 Inkling，一个拥有 9750 亿参数的开源权重多模态 Transformer 模型，在 450 万亿文本、图像、音频和视频 token 上训练，采用 Apache-2.0 许可证。他们还宣布了 Inkling-Small，一个 2760 亿参数、120 亿活跃参数的模型，仍在测试中。 这代表了可访问 AI 研究的重要进展，因为它提供了一个可与来自中国和其他开源替代品竞争的大规模开源权重多模态模型。Apache-2.0 许可证使其对 AI 社区的研究和商业应用都很有价值。 Inkling 是一个拥有 9750 亿总参数但每次仅激活 410 亿参数的 Mixture-of-Experts Transformer，使其计算效率高。模型文档很少，它被定位为用于微调的强大基础模型，而非前沿模型。

rss · Simon Willison · 7月16日 15:35

**背景**: Mixture-of-Experts (MoE) Transformer 是一种神经网络架构，集成了多个并行的专家子网络和一个门控机制，以选择性地处理 token，确保可扩展性和高效计算。与传统的 Transformer 不同，MoE 模型动态地将输入路由到模型组件的子集。开源权重模型是指其核心组件（训练参数）公开发布的 AI 模型，允许任何人下载和使用，这促进了 AI 开发中的透明度和可访问性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/mixture-of-experts-transformer">Mixture - of - Experts Transformer</a></li>
<li><a href="https://www.emergentmind.com/topics/mixture-of-experts-transformer-architecture">Mixture - of - Experts Transformer Architecture</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>

</ul>
</details>

**标签**: `#AI`, `#machine-learning`, `#open-source`, `#multimodal`, `#transformers`

---

<a id="item-5"></a>
## [Linus Torvalds 澄清 Linux 对 AI 的立场](https://simonwillison.net/2026/Jul/16/linus-torvalds/#atom-everything) ⭐️ 8.0/10

Linus Torvalds 表示 Linux 不是反 AI 项目，不同意的人可以 fork 或离开，认为 AI 是有用的工具。 作为 Linux 的顶级维护者，他的立场在开源社区中具有重要影响力，解决了 AI 在开源项目中整合的持续争议，可能影响未来的发展方向。 Torvalds 强调他愿意在这个问题上采取坚定立场，指出 AI 的实用性已无争议，怀疑它的人没有实际使用过。

rss · Simon Willison · 7月16日 13:26

**背景**: 在开源项目中，顶级维护者有权设定项目方向并做出关键决策。forking 是开源中的常见做法，开发者如果不同意原项目的方向，可以在开源许可下创建新版本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Fork_(software_development)">Fork (software development) - Wikipedia</a></li>
<li><a href="https://www.linuxfoundation.org/blog/open-source-maintainers-what-they-need-and-how-to-support-them">Open source maintainers : What they need and how to support them</a></li>

</ul>
</details>

**标签**: `#Linux`, `#AI`, `#Open-source`, `#Linus Torvalds`, `#Kernel development`

---

<a id="item-6"></a>
## [Stereo2Spatial：将立体声音乐转换为空间化双耳混音](https://www.reddit.com/r/MachineLearning/comments/1uzevbg/stereo2spatial_convert_stereo_music_tracks_to/) ⭐️ 8.0/10

一位开发者发布了 Stereo2Spatial，这是一个流匹配扩散模型，可将立体声音乐轨道转换为空间化双耳混音。该模型最初在变分自编码器（VAE）的潜在空间中开发，但后来转向原始波形以获得更好的质量，并集成了记忆令牌以实现稳定的长时间上下文生成，以及振幅提升以解决训练不稳定问题。 这代表了扩散模型和变分自编码器（VAE）在音频处理中的新颖应用，解决了现有音乐缺乏高质量空间音频的问题。开源发布和创新技术可能通过实现广泛的空间音频转换，对音乐和娱乐行业产生重大影响。 该模型在 2 个 A6000 GPU 上对 7,669 首曲目进行了约 20 天的训练，采用两阶段训练过程。波形版本，提供直接双耳输出，通过实施振幅提升（将音频轨道缩放到均方根值 0.33 并乘以 3）来克服训练不稳定性。该项目，包括一个 Windows 桌面应用程序，在 Apache 2.0 许可证下发布。

reddit · r/MachineLearning · /u/kittenkrazy · 7月17日 22:55

**背景**: 流匹配扩散模型是一种生成式人工智能，通过将简单分布转换为复杂分布来学习生成数据，常用于图像、视频，现在也用于音频。变分自编码器（VAE）是生成模型，学习输入数据的压缩概率表示（潜在空间），允许重建和生成。潜在空间是数据的低维表示，其中相似项目被放置得更近，从而实现高效的数据压缩和操作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2506.02070">[2506.02070] An Introduction to Flow Matching and Diffusion Models</a></li>
<li><a href="https://www.ibm.com/think/topics/variational-autoencoder">What is a Variational Autoencoder? | IBM</a></li>
<li><a href="https://en.wikipedia.org/wiki/Latent_space">Latent space</a></li>

</ul>
</details>

**标签**: `#audio-processing`, `#diffusion-models`, `#vae`, `#spatial-audio`, `#machine-learning`

---

<a id="item-7"></a>
## [欧盟 AI 法案 OpenRAG：933 个法律结构化块与 BGE-M3 嵌入，存于一个 SQLite 文件中](https://www.reddit.com/r/MachineLearning/comments/1uytlac/eu_ai_act_openrag_933_legally_structured_chunks/) ⭐️ 8.0/10

一个包含欧盟 AI 法案 933 个法律结构化块及 BGE-M3 嵌入的 SQLite 数据库已发布，用于 RAG 和法律 NLP 实验。 该资源对法律 AI 研究具有重要意义，为监管合规和法律 NLP 实验提供了一个高质量、结构化的数据集，满足了该领域的特定需求。 该语料库基于法律结构（条款、序言、定义、附件）而非简单的滑动窗口进行分块，包含 1024 维的 BGE-M3 嵌入，并提供评估结果，显示其性能优于基线方法。

reddit · r/MachineLearning · /u/Automatic-Forever-63 · 7月17日 08:18

**背景**: RAG（检索增强生成）是一种通过从外部知识库检索相关信息来增强大语言模型的技术。BGE-M3 是一种多语言嵌入模型，结合了密集、稀疏和多向量头，以改善语义检索和跨语言对齐。欧盟 AI 法案（法规(EU) 2024/1689）是欧盟境内人工智能的综合性法规。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/bge-m3-embedding">BGE M 3 - Embedding : Multilingual Retrieval Model</a></li>
<li><a href="https://huggingface.co/BAAI/bge-m3?ref=blog-ko.allganize.ai">BAAI/ bge - m 3 · Hugging Face</a></li>

</ul>
</details>

**社区讨论**: 作者请求技术反馈，特别是关于检索评估、结构化分块方法以及有用的额外基线。

**标签**: `#legal-nlp`, `#rag`, `#eu-ai-act`, `#dataset`, `#embeddings`

---

<a id="item-8"></a>
## [ExTernD：一种用于大语言模型的创新三元后训练量化方法](https://www.reddit.com/r/MachineLearning/comments/1uy2zb3/externd_expandedrank_ternary_decomposition/) ⭐️ 8.0/10

一篇研究论文介绍了 ExTernD，这是一种用于大语言模型（LLM）的三元后训练量化（PTQ）方法，该方法将权重矩阵分解为两个三元矩阵和一个对角缩放矩阵，旨在以最小的显存开销实现高精度。 这种方法可以通过仅使用 3 位权重实现高精度量化，从而显著提高大语言模型的部署效率，可能减少内存使用并加速推理，而不会造成显著的精度损失，这对于设备端人工智能应用至关重要。 核心创新是将原始矩阵分解为两个三元矩阵和一个对角缩放矩阵，允许内部秩任意增大以提高精度，而显存的轻微增加则通过利用三元数学运算来证明其合理性。

reddit · r/MachineLearning · /u/LMTLS5 · 7月16日 13:31

**背景**: 后训练量化（PTQ）是一种在模型训练后将高精度权重（例如 FP32）映射到较低精度表示（例如 INT8、INT4 或三元）以减小模型尺寸并提高推理速度的技术。三元量化仅使用三个值（例如-1、0、+1）来表示权重，可以显著减少内存和计算需求，但通常会导致精度下降。ExTernD 论文认为，三元 PTQ 中的固定矩阵大小是一个死胡同，并提出了分解方法来克服这一限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developers.google.com/edge/litert/conversion/tensorflow/quantization/post_training_quantization">Post-training quantization | Google AI Edge | Google for Developers</a></li>
<li><a href="https://developer.nvidia.com/blog/optimizing-llms-for-performance-and-accuracy-with-post-training-quantization/">Optimizing LLMs for Performance and Accuracy with Post-Training Quantization | NVIDIA Technical Blog</a></li>
<li><a href="https://docs.pytorch.org/TensorRT/ts/ptq.html">Post Training Quantization (PTQ) — Torch-TensorRT</a></li>

</ul>
</details>

**社区讨论**: 论文作者/u/LMTLS5 解释说，核心思想是通过分解矩阵来避免三元 PTQ 中固定矩阵大小的限制，通过增加内部秩可以实现任意高的精度，并且当利用三元数学时，轻微的显存增加是值得的。

**标签**: `#LLM`, `#quantization`, `#model-compression`, `#ternary`, `#PTQ`

---