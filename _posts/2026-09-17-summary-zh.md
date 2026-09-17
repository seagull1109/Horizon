---
layout: default
title: "Horizon Summary: 2026-09-17 (ZH)"
date: 2026-09-17
lang: zh
---

> 从 32 条内容中筛选出 12 条重要资讯。

---

1. [恢复美国驾照条形码签名密钥](#item-1) ⭐️ 9.0/10
2. [GLM 自研推理基础设施突破](#item-2) ⭐️ 9.0/10
3. [4B 模型查询计划比 Postgres 快 81%](#item-3) ⭐️ 9.0/10
4. [突破三值 LLM 1.58 位限制](#item-4) ⭐️ 9.0/10
5. [华为加速 AI 芯片计划，目标百万芯片超级集群](#item-5) ⭐️ 9.0/10
6. [纳米尺度力学在类脑计算中的应用](#item-6) ⭐️ 9.0/10
7. [中国 UBTECH 开设工厂大规模生产类人机器人](#item-7) ⭐️ 9.0/10
8. [核聚变的临界时刻](#item-8) ⭐️ 9.0/10
9. [中国科学家研发出世界上最小的 CT 扫描仪](#item-9) ⭐️ 9.0/10
10. [NVIDIA 宣布支持 Rust 语言的 GPU 原生编程](#item-10) ⭐️ 8.0/10
11. [小米 Mimo 2.6 实时训练后仪表盘获社区好评](#item-11) ⭐️ 8.0/10
12. [Mustafa Suleyman 警告不要赋予 AI 模型权利](#item-12) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [恢复美国驾照条形码签名密钥](https://ryan.science/blog/keys-not-included) ⭐️ 9.0/10

美国驾照条形码中存在安全漏洞，允许恢复签名密钥，这可能会损害身份验证系统。 这一发现非常重要，因为它对身份验证过程的完整性构成威胁，可能会影响数百万个人，并突显了需要强大的网络安全措施。 该漏洞涉及从驾照条形码中恢复签名密钥，这可能使攻击者能够伪造签名并绕过身份验证检查。

hackernews · Ryan5453 · 9月17日 03:03 · [社区讨论](https://news.ycombinator.com/item?id=49735930)

**背景**: 驾照条形码包含编码信息，包括用于真实性验证的数字签名。签名密钥对于维护这些签名的完整性至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.barcodesinc.com/news/drivers-license-barcodes-decoded/">Driver ' s License Barcodes Decoded with Airtrack Scanner-</a></li>
<li><a href="https://en.wikipedia.org/wiki/Digital_signature">Digital signature - Wikipedia</a></li>
<li><a href="https://csrc.nist.gov/glossary/term/signing_key">signing key - Glossary | CSRC</a></li>

</ul>
</details>

**社区讨论**: 社区讨论突出了对公开密钥披露的担忧、量子计算威胁的潜在使用以及二级照片验证在防止欺诈中的重要性。

**标签**: `#cybersecurity`, `#identity verification`, `#vulnerability`, `#driver's license`, `#security research`

---

<a id="item-2"></a>
## [GLM 自研推理基础设施突破](https://z.ai/blog/glm-built-its-inference-infrastructure) ⭐️ 9.0/10

GLM 开发了自己的推理基础设施，使用超过 10 万台 AI 加速器集群，预计将显著提升其 GLM-5.3-Flash 模型的性能。 这一进展意义重大，因为它展示了 AI 基础设施的进步，可能导致推理服务更快、更高效，这可能影响依赖 AI 技术的各个行业。 该基础设施建立在大型 AI 加速器集群上，这是朝着构建强大和可扩展的 AI 基础设施迈出的重要一步。

hackernews · whiteros_e · 9月17日 08:27 · [社区讨论](https://news.ycombinator.com/item?id=49737922)

**背景**: AI 加速器是专门设计的硬件，用于加速 AI 算法的处理，尤其是神经网络，这是现代 AI 应用的基础。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_accelerator">Neural processing unit - Wikipedia</a></li>
<li><a href="https://www.synopsys.com/glossary/what-is-an-ai-accelerator.html">What is an AI Accelerator? – How It Works | Synopsys</a></li>
<li><a href="https://snyk.io/articles/what-is-an-ai-accelerator-and-how-does-it-work/">What is an AI accelerator, and how does it work? | Snyk</a></li>
<li><a href="https://blogs.nvidia.com/blog/difference-deep-learning-training-inference-ai/">What’s the Difference Between Deep Learning Training and ...</a></li>
<li><a href="https://www.cloudflare.com/learning/ai/inference-vs-training/">AI inference vs. training: What is AI inference? - Cloudflare</a></li>
<li><a href="https://www.digitalocean.com/resources/articles/ai-inference-vs-training">AI Inference vs Training: Key Differences Explained</a></li>
<li><a href="https://www.ibm.com/think/topics/ai-accelerator">What is an AI accelerator? - IBM</a></li>
<li><a href="https://www.supermicro.com/en/glossary/ai-accelerator">What Is an AI Accelerator? - Supermicro</a></li>

</ul>
</details>

**社区讨论**: 社区讨论突出了对基础设施的可扩展性和性能的担忧，一些人认为美国芯片出口限制可能是推动国内 AI 基础设施发展的动力。

**标签**: `#AI Infrastructure`, `#Machine Learning`, `#Inference Services`, `#Chinese Tech`, `#AI Accelerators`

---

<a id="item-3"></a>
## [4B 模型查询计划比 Postgres 快 81%](https://rohanbansal.com/qorl) ⭐️ 9.0/10

一个 4B 模型实现了比 Postgres 快 81%的查询计划，展示了使用机器学习技术在数据库优化方面的重大突破。 这一突破可能彻底改变数据库性能，可能导致更高效的数据处理和复杂查询的改进的可扩展性。 该模型使用离策略蒸馏和代理强化学习进行训练，展示了人工智能在优化数据库查询性能方面的潜力。

hackernews · polyphilz · 9月16日 18:50 · [社区讨论](https://news.ycombinator.com/item?id=49731285)

**背景**: 查询优化是数据库系统的一个关键方面，涉及为查询生成高效的执行计划。机器学习越来越多地应用于增强这些过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.explainx.ai/blog/training-4b-model-postgres-query-optimization-rl-rohan-bansal-2026">Training a 4B Model to Beat Postgres With RL (2026 ...</a></li>
<li><a href="https://best-ai.org/ai-news/qorl-a-4b-ai-model-outperforms-postgres-query-optimizer-by-81-cofgbk">QORL: A 4B AI Model Outperforms Postgres Query Optimizer by ...</a></li>
<li><a href="https://msinformationtech.blogspot.com/2026/09/how-to-boost-sql-performance-by-81.html">How to Boost SQL Performance by 81% Using a 4B Model</a></li>

</ul>
</details>

**社区讨论**: 社区讨论突出了模型在大型数据集上的性能问题和对过度拟合的担忧，以及进一步研究自适应查询计划的必要性。

**标签**: `#Database Optimization`, `#Machine Learning in Databases`, `#Query Performance`, `#AI in Software Engineering`, `#Database Systems`

---

<a id="item-4"></a>
## [突破三值 LLM 1.58 位限制](https://arxiv.org/abs/2609.16338) ⭐️ 9.0/10

一篇研究论文介绍了 BITCOS，这是一种针对三值 LLM 的分布自适应布局，打破了 1.58 位的限制，可能带来更高效的硬件实现。 这一突破可能显著影响三值 LLM 领域的硬件效率和性能，可能导致更节能且强大的 AI 模型。 BITCOS 通过利用实际权重中有 51%的时间为 0 的事实来实现这一点，从而实现更紧凑的存储和更快的推理。

hackernews · matt_d · 9月16日 20:59 · [社区讨论](https://news.ycombinator.com/item?id=49732931)

**背景**: 三值计算使用的是三进制系统，有三种可能的值（0、1 和 2），而不是二进制系统的两个值（0 和 1）。LLM 是大型语言模型，用于处理和生成人类语言。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ternary_computer">Ternary computer - Wikipedia</a></li>
<li><a href="https://thisvsthat.io/binary-computing-vs-ternary-computing">Binary Computing vs. Ternary Computing - What's the ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/1.58-bit_large_language_model">1.58-bit large language model - Wikipedia</a></li>
<li><a href="https://www.emergentmind.com/topics/ternaryllm">TernaryLLM: Low-Bit Language Models</a></li>
<li><a href="https://www.emergentmind.com/topics/ternarylm">TernaryLM: Efficient Ternary LLM Quantization</a></li>
<li><a href="https://explainx.ai/blog/bitcos-ternary-llm-1-48-bit-packing-2026">BITCOS: Breaking the 1.58-Bit Barrier for Ternary LLMs</a></li>
<li><a href="https://arxiv.org/abs/2609.16338">[2609.16338] Breaking the 1.58-bit Barrier for Ternary LLMs</a></li>
<li><a href="https://aicrier.com/post/k6m2nihlstrut9khdvis">BITCOS breaks 1.58-bit barrier for ternary LLMs — AICrier</a></li>

</ul>
</details>

**社区讨论**: 社区讨论突出了潜在的效率提升，一些人质疑三值量化的实用性，而其他人则认为它适合 ASIC 优化的模型。

**标签**: `#Machine Learning`, `#Ternary Computing`, `#LLMs`, `#Hardware Efficiency`, `#AI Research`

---

<a id="item-5"></a>
## [华为加速 AI 芯片计划，目标百万芯片超级集群](https://www.reddit.com/r/Futurology/comments/1wir9qb/huawei_just_sped_up_its_ai_chip_plans_and_wants/) ⭐️ 9.0/10

华为加速了其 AI 芯片计划，960DT 芯片预计于 2027 年第一季度推出，960PR 芯片预计于 2027 年第三季度推出，旨在连接多达 100 万处理器，以与英伟达竞争。 这一举措意义重大，因为它可能会重塑 AI 和芯片行业的竞争格局，有可能缩小与英伟达的差距，并增强中国在 AI 硬件方面的自给自足能力。 新的 Atlas 960 SuperPoD 提高了大型模型的训练和推理性能，华为的互连技术可以将多达 100 万 AI 芯片连接成庞大的超级集群。

reddit · r/Futurology · /u/cat_scrivener42 · 9月17日 11:23

**背景**: Ascend 960 系列是华为挑战英伟达在 AI 芯片领域主导地位的举措。Atlas 960 SuperPoD 是为高性能计算和 AI 应用而设计的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gadgetsnow.indiatimes.com/tech-news/huawei-introduces-powerful-ai-chips-ascend-960dt-and-960pr-set-to-challenge-nvidia-by-2027/articleshow/134303006.cms">Huawei Introduces Powerful AI Chips : Ascend 960 DT And 960 PR Set...</a></li>
<li><a href="https://www.globaltimes.cn/page/202609/1370739.shtml">Huawei unveils Ascend 960 SuperPoD as AI ... - Global Times</a></li>
<li><a href="https://www.tipranks.com/news/huawei-sets-two-ascend-960-ai-chip-launches-for-2027-to-challenge-nvidia">Huawei Sets Two Ascend 960 AI Chip Launches for... - TipRanks.com</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一，一些人怀疑连接 100 万芯片的可行性，而另一些人则赞扬华为的雄心和创新能力。

**标签**: `#Huawei`, `#AI Chips`, `#Tech News`, `#Industry Competition`, `#Supercomputing`

---

<a id="item-6"></a>
## [纳米尺度力学在类脑计算中的应用](https://www.reddit.com/r/Futurology/comments/1wiqw2a/nanoscale_mechanics_could_enable_braininspired/) ⭐️ 9.0/10

一种新型设备利用纳米尺度上的可重构运动来模拟神经元放电行为，可能带来更高效的计算。 这一突破可能彻底改变计算效率，通过实现低功耗、高性能的计算设备，影响各个行业。 该设备利用纳米尺度力学来模拟神经元的放电，可能减少对复杂电子组件的需求。

reddit · r/Futurology · /u/Miserable_Phase_2519 · 9月17日 11:03

**背景**: 纳米力学是研究纳米尺度机械性质的科学，而类脑计算旨在模仿人脑的处理能力，以实现更高效的计算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nanomechanics">Nanomechanics - Wikipedia</a></li>
<li><a href="https://news.mit.edu/2026/nanoscale-mechanics-could-enable-brain-inspired-computing-0916">Nanoscale mechanics could enable brain-inspired computing</a></li>
<li><a href="https://lifeboat.com/blog/2026/09/nanoscale-mechanics-could-enable-brain-inspired-computing">Nanoscale mechanics could enable brain-inspired computing</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的评论表明人们对这项技术表现出极高的兴趣，讨论了其潜在影响和未来应用。

**标签**: `#Brain-Inspired Computing`, `#Nanotechnology`, `#Neurotechnology`, `#Computing Efficiency`, `#Innovative Technology`

---

<a id="item-7"></a>
## [中国 UBTECH 开设工厂大规模生产类人机器人](https://www.reddit.com/r/Futurology/comments/1whw8v9/chinas_ubtech_opens_plant_making_a_humanoid_robot/) ⭐️ 9.0/10

UBTECH 在中国开设了一家新工厂，年产量可达 10,000 台工业类人机器人，每 10 分钟生产一台。 这一里程碑标志着机器人制造业的重大飞跃，可能改变行业并为自动化增加铺平道路。 该工厂采用先进的自动化和机器人技术，包括精密机械和人工智能集成，以实现如此高的生产率。

reddit · r/Futurology · /u/Gari_305 · 9月16日 12:46

**背景**: 类人机器人是设计来模仿人类的机器人，应用于制造业、医疗保健和服务行业。它们通常具有拟人化设计和用于交互的高级传感器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Humanoid_robots">Humanoid robot - Wikipedia</a></li>
<li><a href="https://www.askdifference.com/humanoid-vs-robot/">Humanoid vs. Robot — What's the Difference?</a></li>
<li><a href="https://droidage.com/blog/what-is-a-humanoid-robot/">What Is a Humanoid Robot? Types, Applications, and Leading ...</a></li>
<li><a href="https://www.xavier-parts.com/humanoid-robot-parts-explained-materials/">Humanoid Robot Parts Explained: Materials, Actuators, Sensors, And ...</a></li>
<li><a href="https://robochronicle.com/2026/03/04/the-humanoid-supply-chain-map-2026-edition/">The Humanoid Supply Chain Map (2026 Edition) - robochronicle.com</a></li>
<li><a href="https://www.fictiv.com/articles/humanoid-robotics-manufacturing-impact">Humanoid Robots in Manufacturing: Transforming Industrial Automation</a></li>
<li><a href="https://www.humanoidsdaily.com/news/inside-ubtech-s-10-000-unit-super-factory-how-robots-are-building-humanoids-in-liuzhou">Inside UBTECH’s 10,000-Unit Super Factory: How Robots Are ...</a></li>
<li><a href="https://www.ndtv.com/feature/one-robot-every-10-minutes-inside-chinas-futuristic-humanoid-factory-12058222">One Robot Every 10 Minutes: Inside China's Futuristic ...</a></li>
<li><a href="https://www.explainx.ai/blog/ubtech-humanoid-robot-factory-liuzhou-2026">UBTECH Humanoid Robot Factory Explained (2026) | explainx.ai Blog</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的讨论突出了对这些机器人可能对就业市场和未来工作产生的影响的兴趣，一些人表达了对就业转移的担忧。

**标签**: `#Robotics`, `#Automation`, `#UBTECH`, `#Humanoid Robots`, `#Manufacturing`

---

<a id="item-8"></a>
## [核聚变的临界时刻](https://www.reddit.com/r/Futurology/comments/1wirkmk/nuclear_fusions_moment_of_truth/) ⭐️ 9.0/10

核聚变领域的初创公司正获得创纪录的投资，引发了对其实现商业化可行性的时间表乐观性的讨论。 这一趋势标志着能源领域的重大转变，可能带来更清洁、更丰富的能源来源，并可能影响全球能源政策和市场。 这些投资是能源领域增长趋势的一部分，一些科学家质疑实现商业化核聚变电力的时间表是否过于乐观。

reddit · r/Futurology · /u/Gari_305 · 9月17日 11:38

**背景**: 核聚变是一种两个轻原子核结合形成较重原子核的过程，释放出大量能量。它是太阳和星星的能量来源，被认为是解决世界能源需求的一种潜在方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cnduk.org/how-do-nuclear-weapons-work/">How do nuclear weapons work ? - CND</a></li>
<li><a href="https://www.tiktok.com/discover/fusion-reactor-science-explained">Fusion Reactor Science Explained | TikTok</a></li>
<li><a href="https://en.wikipedia.org/wiki/Nuclear_fusion">Nuclear fusion - Wikipedia</a></li>
<li><a href="https://precision-ceramics.com/eu/types-of-nuclear-fusion/">Exploring the Different Types of Nuclear Fusion Understanding the Difference Between Nuclear Fission and ... Nuclear fusion - Wikipedia Nuclear Fusion Reactor Designs: Types, Progress, and Timeline Nuclear Fusion | MIT Technology Roadmaps Nuclear Fusion Power - World Nuclear Association Approaches to Fusion | U.S. Fusion Energy</a></li>
<li><a href="https://www.ft.com/content/ef511d46-a689-4868-9654-15b96a71586d?syn-25a6b1a6=1">Nuclear fusion's moment of truth - Financial Times</a></li>
<li><a href="https://news.linxi.com.au/news/fusion-start-ups-draw-record-investment-as-scientists-question-timelines">Fusion start-ups attract record investment amid timeline doubts | Linxi ...</a></li>
<li><a href="https://nuclear.news/2026-07-20-global-nuclear-fusion-investments-reach-record-high-2025.html">Global Nuclear Fusion Investments Reach Record $4.48 Billion in 2025</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的讨论反映了乐观和怀疑的混合情绪，一些用户对时间表的可行性表示担忧，而另一些用户则强调了潜在的突破。

**标签**: `#nuclear_fusion`, `#energy_technology`, `#breakthrough`, `#futurology`, `#investment`

---

<a id="item-9"></a>
## [中国科学家研发出世界上最小的 CT 扫描仪](https://www.reddit.com/r/Futurology/comments/1whmkxx/chinese_scientists_build_worlds_smallest_ct/) ⭐️ 9.0/10

中国科学家研发出世界上最小的 CT 扫描仪，仅重 6 公斤，这是医学影像技术的一项重大突破。 这一创新有望通过使医学影像更加便捷和便携，特别是偏远或服务不足的地区，从而彻底改变医学影像。 该扫描仪体积小、重量轻，适合在救护车和其他移动医疗环境中使用。

reddit · r/Futurology · /u/scmp_news · 9月16日 04:07

**背景**: CT 扫描仪，即计算机断层扫描仪，使用 X 射线创建身体内部结构的详细横断面图像。它在医学诊断中得到广泛应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://expertmri.com/ct-scans-explained-with-the-help-of-donuts-and-sliced-bread/">CT scans explained, with the help of donuts and sliced... - Expert Mri</a></li>
<li><a href="https://www.brookingshealth.org/videos/ct-and-mri-help-diagnose-cause-abdominal-pain-nadine-poppinga">CT and MRI Help Diagnose Cause of Abdominal Pain [Nadine Poppinga]</a></li>

</ul>
</details>

**社区讨论**: Reddit 社区表现出兴奋和怀疑的混合情绪，一些人质疑扫描仪的图像质量，而另一些人则赞扬其提高医疗可及性的潜力。

**标签**: `#Medical Technology`, `#CT Scanner`, `#Innovation`, `#Healthcare`, `#Science`

---

<a id="item-10"></a>
## [NVIDIA 宣布支持 Rust 语言的 GPU 原生编程](https://developer.nvidia.com/blog/introducing-cuda-rust-two-tracks-for-writing-gpu-kernels/) ⭐️ 8.0/10

NVIDIA 宣布支持在 Rust 语言中直接进行 GPU 编程，这一举措使得开发者能够用 Rust 编写 GPU 内核，可能彻底改变 GPU 编程方式，并推动 Rust 在高性能计算领域的应用。 这一宣布意义重大，因为它可能导致 GPU 编程更加高效，并推动 Rust 在高性能计算领域的广泛应用，从而改变 GPU 编程和编程语言行业的格局。 新支持包括两个路径：cuda-oxide 用于传统的 SIMT 内核编译到 PTX，以及 cutile-rs 用于在稳定的 Rust 上进行瓦片式编程。这标志着从传统的 CUDA C++和 CUDA Python 方法转向。

hackernews · nonmaskable · 9月16日 11:15 · [社区讨论](https://news.ycombinator.com/item?id=49724881)

**背景**: GPU 编程涉及编写在图形处理单元（GPU）上运行的代码以加速任务。Rust 是一种系统编程语言，以其性能和安全著称。将 Rust 与 GPU 编程相结合可能提供新的效率和安全性水平。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/introducing-cuda-rust-two-tracks-for-writing-gpu-kernels/">Introducing CUDA Rust: Two Tracks for Writing GPU Kernels</a></li>
<li><a href="https://www.listmyai.com/blog/nvidia-announces-native-gpu-programming-rust-2026">Nvidia announces native GPU programming in Rust: What ...</a></li>
<li><a href="https://www.explainx.ai/blog/nvidia-cuda-rust-gpu-kernels-2026">CUDA Rust: Native GPU Kernels in Rust (NVIDIA, 2026 ...</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一，一些人对于 Rust 在 GPU 编程中的潜力表示热情，而另一些人则对 CUDA 的专有性质和潜在的供应商锁定表示担忧。

**标签**: `#Nvidia`, `#Rust`, `#GPU Programming`, `#High-Performance Computing`, `#Programming Languages`

---

<a id="item-11"></a>
## [小米 Mimo 2.6 实时训练后仪表盘获社区好评](https://mimo.xiaomi.com/rl/) ⭐️ 8.0/10

社区对小米的 Mimo 2.6 实时训练后仪表盘进行了评测，对其性能和性价比给予了积极反馈。 积极的反馈表明了其实用价值和在软件工程领域的潜在影响，因为用户分享了他们的使用体验并将其与其他模型进行了比较。 仪表盘提供强化学习训练后运行的实时跟踪，与部署管道无缝集成。

hackernews · krackers · 9月16日 20:09 · [社区讨论](https://news.ycombinator.com/item?id=49732270)

**背景**: AI 中的实时训练后仪表盘允许在模型训练完成后监控和分析其性能，确保它们达到预期标准并能够有效部署。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://topaihubs.com/articles/xiaomi-mimo-2-6-live-post-training-dashboards-revolutionize-ai-model-monitoring">Xiaomi Mimo 2.6 Live: Post-Training Dashboards Revolutionize ...</a></li>
<li><a href="https://aiweekly.co/alerts/xiaomi-publishes-live-post-training-dashboard-for-mimo-26-rl-run-streams-real">Xiaomi opens live RL post-training dashboard for Mimo 2.6</a></li>
<li><a href="https://aiwiki.ai/wiki/post-training">Post-training - AI Wiki</a></li>

</ul>
</details>

**社区讨论**: 用户对模型的表现和成本表示满意，有些人指出其处理复杂任务的能力和具有竞争力的价格。

**标签**: `#Xiaomi`, `#AI`, `#Software Engineering`, `#Machine Learning`, `#Technology Review`

---

<a id="item-12"></a>
## [Mustafa Suleyman 警告不要赋予 AI 模型权利](https://simonwillison.net/2026/Sep/16/mustafa-suleyman/) ⭐️ 8.0/10

Mustafa Suleyman 警告不要将 AI 模型视为具有权利或福利的实体，强调意识在道德体系中的重要性。 这一观点具有重要意义，因为它为 AI 伦理的持续讨论做出了贡献，这对于 AI 的负责任开发和部署至关重要。 Suleyman 认为，意识是道德体系的基础，在没有意识的情况下赋予 AI 模型权利或福利是不合理的。

rss · Simon Willison · 9月16日 16:00

**背景**: AI 伦理是 AI 研究中的一个关键领域，关注 AI 系统的道德和社会影响。AI 中的意识是指 AI 系统具有意识和主观体验的可能性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Artificial_consciousness">Artificial consciousness - Wikipedia</a></li>
<li><a href="https://oecs.mit.edu/pub/zf1nbs6d/">Consciousness and AI — OECS</a></li>
<li><a href="https://aisecurityandsafety.org/en/glossary/model-welfare/">Model Welfare — Definition & Implications for AI Safety</a></li>
<li><a href="https://aiwiki.ai/wiki/model_welfare">Model welfare - AI Wiki</a></li>
<li><a href="https://www.anthropic.com/research/exploring-model-welfare">Exploring model welfare \ Anthropic</a></li>
<li><a href="https://www.researchgate.net/publication/392285614_Model_welfare_in_large-scale_language_models_critical_analysis_of_functional_consistency_ethics">Model welfare in large-scale language models: critical ...</a></li>
<li><a href="https://arxiv.org/html/2406.05392v2">Deconstructing The Ethics of Large Language Models from Long ...</a></li>
<li><a href="https://arxiv.org/html/2406.05392v1">Deconstructing The Ethics of Large Language Models from Long ...</a></li>

</ul>
</details>

**社区讨论**: 社区讨论集中在 Suleyman 警告的影响上，一些人同意 AI 模型不应被赋予权利，而另一些人则主张采取更细致的方法。

**标签**: `#ai-ethics`, `#generative-ai`, `#ai`, `#microsoft`, `#llms`

---