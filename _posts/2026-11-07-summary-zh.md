---
layout: default
title: "Horizon Summary: 2026-11-07 (ZH)"
date: 2026-11-07
lang: zh
---

> 从 30 条内容中筛选出 6 条重要资讯。

---

1. [Ant Ling 发布 Ling-3.2-flash：560B/25B 原生多模态 MoE，最大 1M 上下文窗口](#item-1) ⭐️ 9.0/10
2. [Higgs 实时双工：45B MoE 全双工 AI 模型](#item-2) ⭐️ 9.0/10
3. [Libghostty 1.0 版本发布](#item-3) ⭐️ 8.0/10
4. [MacOS 中的未公开家庭成员分类器](#item-4) ⭐️ 8.0/10
5. [美国 FAA 将于 2028 年淘汰空中交通管制中的软盘](#item-5) ⭐️ 8.0/10
6. [Firecracker 虚拟机逃逸：PwnEscape 第二部分](#item-6) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Ant Ling 发布 Ling-3.2-flash：560B/25B 原生多模态 MoE，最大 1M 上下文窗口](https://www.reddit.com/r/MachineLearning/comments/1xpye7g/ant_ling_introduces_ling32flash_560b25b_native/) ⭐️ 9.0/10

Ant Ling 发布了 Ling-3.2-flash，这是一个具有 560B 总参数、25B 激活参数和 1M 上下文窗口的原生多模态 MoE 模型，支持文本、图像和视频输入。 Ling-3.2-flash 的发布标志着机器学习领域的一项重大进步，因为它在各种基准测试中表现出色，并有可能影响广泛的领域。 Ling-3.2-flash 在 MathVision、Humanity's Last Exam-MM、BabyVision 等基准测试中取得了令人印象深刻的成果，并支持 PDF 转代码实现和多智能体协作。

reddit · r/MachineLearning · /u/the-hollow-soul · 11月7日 05:21

**背景**: 多模态 MoE 模型结合文本、图像和视频等多种模态来处理不同类型的数据，而混合专家（MoE）是一种神经网络架构，将问题空间划分为同质区域，从而实现高效的计算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2605.27431">[2605.27431] Tackling Multimodal Learning Challenges with ...</a></li>
<li><a href="https://www.ibm.com/think/topics/mixture-of-experts">What is mixture of experts? - IBM</a></li>
<li><a href="https://www.perplexity.ai/search/What-does-MoE-Fvz8kOb7TgyIiMUuU6gkMA">What does MoE mean in terms of AI training</a></li>
<li><a href="https://www.hivenet.com/post/mixture-of-experts-llm-gpu-memory">Mixture of Experts Explained: MoE , Memory & GPUs | Hivenet</a></li>
<li><a href="https://www.c-sharpcorner.com/article/what-is-mixture-of-experts-moe-architecture">What Is Mixture-of-Experts ( MoE ) Architecture</a></li>
<li><a href="https://dev.to/emperorakashi20/context-windows-explained-why-1m-tokens-changes-how-you-architect-ai-applications-fe6">Context Windows Explained: Why 1M Tokens Changes How You ...</a></li>
<li><a href="https://www.teacherandtask.com/blog/what-is-context-window-1m-tokens-explained">What Is the Context Window? 1M and 2M Tokens Explained (2026 ...</a></li>
<li><a href="https://devtk.ai/en/blog/llm-context-window-explained/">LLM Context Windows Explained: 4K to 1M Tokens (2026)</a></li>

</ul>
</details>

**社区讨论**: Reddit 社区对这款新模型表示了兴趣，讨论主要集中在其性能、潜在应用以及与其他模型的比较上。

**标签**: `#MachineLearning`, `#MultimodalLearning`, `#MoE`, `#AIResearch`, `#ModelEvaluation`

---

<a id="item-2"></a>
## [Higgs 实时双工：45B MoE 全双工 AI 模型](https://www.reddit.com/r/MachineLearning/comments/1xpn5pv/higgs_realtime_duplex_a_45b_moe_fullduplex_model/) ⭐️ 9.0/10

Boson AI 发布了 Higgs 实时双工，这是一个 45B MoE 的全双工模型，能够实现实时监听、观看、说话，并在后台进行包括工具调用和委托在内的处理。 该模型代表了人工智能和机器学习领域的一项重大进步，有望通过实现更自然、高效的交流方式而彻底改变人机交互。 模型以 160 毫秒的块处理音频和视频数据，使用基于文本的预训练 LLM，并采用多教师策略蒸馏进行训练。

reddit · r/MachineLearning · /u/Cali_Cobarde · 11月6日 20:23

**背景**: 全双工模型旨在同时处理双向通信，这在人工智能和机器学习领域是一个重大挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.boson.ai/blog/higgs-realtime-duplex">Higgs Realtime Duplex: Face to Face, Working in the ...</a></li>
<li><a href="https://emergent.sh/news/boson-ai-higgs-realtime-duplex-45b-voice">Boson AI Higgs Realtime Duplex: 45B Voice-Video Model</a></li>
<li><a href="https://aicoder.com/news/news-20261105-boson-ai-higgs-realtime-duplex-45b-moe-full-duplex-omni-160ms">Boson AI Unveils Higgs Realtime Duplex: A 45B MoE Full-Duplex ...</a></li>

</ul>
</details>

**社区讨论**: 社区反应普遍积极，讨论主要集中在该模型对各个行业的影响潜力及其技术能力。

**标签**: `#AI`, `#MachineLearning`, `#FullDuplexModel`, `#NaturalLanguageProcessing`, `#AIResearch`

---

<a id="item-3"></a>
## [Libghostty 1.0 版本发布](https://mitchellh.com/writing/libghostty-1-0) ⭐️ 8.0/10

Libghostty 1.0 版本发布，引入了一个稳定、可移植的 C 语言终端仿真库，直接从 Ghostty 的核心提取，并获得了积极的社区反馈和兴趣。 此次发布意义重大，因为它提供了一个强大的终端仿真解决方案，可能会影响新编码工具和终端仿真器的开发，从而影响基于终端的应用程序的开发者和用户。 Libghostty 1.0 是可移植的，仅需要 libc，可以独立构建，并为多种编程语言提供绑定。

hackernews · mfiguiere · 11月6日 23:30 · [社区讨论](https://news.ycombinator.com/item?id=50399933)

**背景**: 终端仿真器是一种程序，可以模拟视频终端，使用户可以通过基于文本的界面与操作系统交互。Libghostty 是一个开源项目，旨在提供一个高性能的终端仿真器库。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Terminal_emulator">Terminal emulator - Wikipedia</a></li>
<li><a href="https://mitchellh.com/writing/libghostty-1-0">Libghostty 1.0 – Mitchell Hashimoto</a></li>
<li><a href="https://news.lavx.hu/article/libghostty-1-0-stabilizes-the-terminal-library-behind-ghostty">Libghostty 1.0 stabilizes the terminal library behind Ghostty</a></li>

</ul>
</details>

**社区讨论**: 社区反馈普遍积极，用户称赞 Libghostty 的稳定性和性能，并表达了对其在新编码工具和终端仿真器中潜在应用的兴趣。

**标签**: `#Terminal Emulators`, `#Software Development`, `#Open Source`, `#Community Projects`, `#Technology`

---

<a id="item-4"></a>
## [MacOS 中的未公开家庭成员分类器](https://8rank.ai/game/apple-intelligence-personal-knowledge-graph) ⭐️ 8.0/10

一项分析揭示了苹果 MacOS 中的一项未公开功能，该功能可对家庭成员进行分类并构建个人知识图谱。 这一功能引发了关于隐私以及 MacOS 如何收集和使用数据的担忧，可能影响用户的个人信息。 该功能未进行文档记录，意味着它不是苹果官方支持或承认的功能，其存在是通过分析发现的。

hackernews · infwhispers · 11月7日 09:46 · [社区讨论](https://news.ycombinator.com/item?id=50403097)

**背景**: 个人知识图谱是对一个人的关系、活动和信息的视觉表示。MacOS 是由苹果公司开发的用于其 Mac 电脑的操作系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=pmPA9_29VPg">Customizing the Mac Context Menu - YouTube</a></li>
<li><a href="https://www.tsuka.io/insights/the-purpose-of-interlinking-building-a-personal-knowledge-graph">The Purpose of Interlinking: Building a Personal Knowledge Graph</a></li>
<li><a href="https://archive.org/stream/Undocumented_DOS/Undocumented_DOS_djvu.txt">Full text of " Undocumented DOS"</a></li>

</ul>
</details>

**社区讨论**: 社区反应从对隐私的担忧到对技术的着迷，一些用户甚至考虑切换到其他操作系统。

**标签**: `#Apple`, `#macOS`, `#Privacy`, `#Data Collection`, `#Technology`

---

<a id="item-5"></a>
## [美国 FAA 将于 2028 年淘汰空中交通管制中的软盘](https://www.reuters.com/world/us/us-faa-says-it-will-phase-out-floppy-disks-air-traffic-control-by-2028-2026-11-05/) ⭐️ 8.0/10

美国联邦航空管理局（FAA）宣布计划于 2028 年逐步淘汰空中交通管制系统中使用的软盘。 这一决定意义重大，因为它标志着向现代化空中交通管制系统迈出的步伐，可能提高航空业的效率和安全性。 FAA 的当前系统依赖于 20 世纪 80 年代的遗留技术，使用 1.44MB 的软盘进行关键数据存储。

hackernews · ChrisArchitect · 11月6日 04:00 · [社区讨论](https://news.ycombinator.com/item?id=50388001)

**背景**: 自 20 世纪 80 年代以来，空中交通管制系统已经发生了显著变化，现代系统通常使用更先进的存储解决方案，如固态硬盘（SSD）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theverge.com/transportation/1027511/faa-floppy-disks-sean-duffy-air-traffic-control-eids">The FAA is finally ditching floppy disks | The Verge</a></li>
<li><a href="https://www.pcmag.com/news/the-faa-is-still-using-floppy-disk-based-systems-but-thats-about-to-change">The FAA Is Still Using Floppy Disk -Based Systems , But... | PCMag</a></li>

</ul>
</details>

**社区讨论**: 社区讨论突出了使用过时技术对安全性的影响，以及需要谨慎但进步的方法来推进现代化。

**标签**: `#aviation`, `#air-traffic-control`, `#technology-modernization`, `#FAA`, `#floppy-disks`

---

<a id="item-6"></a>
## [Firecracker 虚拟机逃逸：PwnEscape 第二部分](https://pwn.ai/blog/firecracker-escape) ⭐️ 8.0/10

这篇博客文章深入分析了 Firecracker 虚拟机中的安全漏洞，详细介绍了 PwnEscape 第二部分漏洞利用及其对虚拟化安全可能产生的影响。 这一漏洞的发现具有重要意义，因为它突显了虚拟化技术相关的安全风险，并强调了在微虚拟机环境中采取强大安全措施的重要性。 分析讨论了配置中缺少 jailer，这是 Firecracker 生产隔离的关键组件，以及没有适当权限和资源限制的后果。

hackernews · SerCe · 11月6日 19:33 · [社区讨论](https://news.ycombinator.com/item?id=50397219)

**背景**: Firecracker 是一种开源的虚拟化技术，旨在为轻量级、安全、快速的微虚拟机设计。虚拟机逃逸是一个严重的安全问题，因为它允许攻击者绕过虚拟机的隔离，并可能访问宿主系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://firecracker-microvm.github.io/?trk">Firecracker</a></li>
<li><a href="https://fly.io/learn/firecracker-vm/">What Is a Firecracker microVM? · Learn</a></li>
<li><a href="https://github.com/firecracker-microvm/firecracker">GitHub - firecracker-microvm/firecracker: Secure and fast ... Firecracker MicroVM Review: Architecture, Setup, and Limitations Firecracker MicroVM Use Cases Explained — DevelopNSolve Firecracker MicroVM Sandboxing Features Explained What is a microVM? Firecracker vs containers (2026)</a></li>

</ul>
</details>

**社区讨论**: 社区讨论突出了对文章中缺乏细节的关注，Nova 微虚拟机方法的有效性，以及该漏洞对依赖 Firecracker 虚拟机的服务的实际影响。

**标签**: `#virtualization`, `#security`, `#Firecracker`, `#VM escape`, `#PwnEscape`

---