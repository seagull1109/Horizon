---
layout: default
title: "Horizon Summary: 2026-11-07 (EN)"
date: 2026-11-07
lang: en
---

> From 30 items, 6 important content pieces were selected

---

1. [Ant Ling Unveils Ling-3.2-flash: 560B/25B Native Multimodal MoE with 1M Context](#item-1) ⭐️ 9.0/10
2. [Higgs Realtime Duplex: 45B MoE Full-Duplex AI Model](#item-2) ⭐️ 9.0/10
3. [Libghostty 1.0 Release](#item-3) ⭐️ 8.0/10
4. [Undocumented Family Member Classifier in macOS](#item-4) ⭐️ 8.0/10
5. [US FAA to Phase Out Floppy Disks in Air Traffic Control by 2028](#item-5) ⭐️ 8.0/10
6. [Firecracker VM Escape: PwnEscape Part 2](#item-6) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Ant Ling Unveils Ling-3.2-flash: 560B/25B Native Multimodal MoE with 1M Context](https://www.reddit.com/r/MachineLearning/comments/1xpye7g/ant_ling_introduces_ling32flash_560b25b_native/) ⭐️ 9.0/10

Ant Ling has released Ling-3.2-flash, a native multimodal MoE model with 560B total parameters, 25B activated parameters, and a 1M-token context window, supporting text, image, and video inputs. The release of Ling-3.2-flash marks a significant advancement in machine learning, as it demonstrates high performance across various benchmarks and has the potential to impact a wide range of applications. Ling-3.2-flash achieves impressive results on benchmarks like MathVision, Humanity's Last Exam-MM, and BabyVision, among others, and supports PDF-to-code implementation and multi-agent collaboration.

reddit · r/MachineLearning · /u/the-hollow-soul · Nov 7, 05:21

**Background**: Multimodal MoE models combine multiple modalities like text, image, and video to process diverse types of data, while Mixture of Experts (MoE) is a neural network architecture that divides a problem space into homogeneous regions, allowing for efficient computation.

<details><summary>References</summary>
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

**Discussion**: The Reddit community has shown interest in the new model, with discussions focusing on its performance, potential applications, and comparisons with other models.

**Tags**: `#MachineLearning`, `#MultimodalLearning`, `#MoE`, `#AIResearch`, `#ModelEvaluation`

---

<a id="item-2"></a>
## [Higgs Realtime Duplex: 45B MoE Full-Duplex AI Model](https://www.reddit.com/r/MachineLearning/comments/1xpn5pv/higgs_realtime_duplex_a_45b_moe_fullduplex_model/) ⭐️ 9.0/10

Boson AI has released Higgs Realtime Duplex, a 45B MoE full-duplex model capable of real-time listening, watching, talking, and background processing, including tool calls and delegation. This model represents a significant advancement in AI and machine learning, potentially revolutionizing human-computer interaction by enabling more natural and efficient communication. The model processes audio and video data in 160 ms chunks, uses a text-pretrained LLM, and employs multi-teacher on-policy distillation for training.

reddit · r/MachineLearning · /u/Cali_Cobarde · Nov 6, 20:23

**Background**: Full-duplex models are designed to handle two-way communication simultaneously, which is a significant challenge in AI and machine learning.

<details><summary>References</summary>
<ul>
<li><a href="https://www.boson.ai/blog/higgs-realtime-duplex">Higgs Realtime Duplex: Face to Face, Working in the ...</a></li>
<li><a href="https://emergent.sh/news/boson-ai-higgs-realtime-duplex-45b-voice">Boson AI Higgs Realtime Duplex: 45B Voice-Video Model</a></li>
<li><a href="https://aicoder.com/news/news-20261105-boson-ai-higgs-realtime-duplex-45b-moe-full-duplex-omni-160ms">Boson AI Unveils Higgs Realtime Duplex: A 45B MoE Full-Duplex ...</a></li>

</ul>
</details>

**Discussion**: Community reactions are largely positive, with discussions focusing on the potential impact of the model on various industries and its technical capabilities.

**Tags**: `#AI`, `#MachineLearning`, `#FullDuplexModel`, `#NaturalLanguageProcessing`, `#AIResearch`

---

<a id="item-3"></a>
## [Libghostty 1.0 Release](https://mitchellh.com/writing/libghostty-1-0) ⭐️ 8.0/10

The Libghostty 1.0 release introduces a stable, portable C library for terminal emulation, extracted from the core of Ghostty, and garners positive community feedback and interest. This release is significant as it provides a robust terminal emulation solution that could influence the development of new coding tools and terminal emulators, potentially affecting developers and users of terminal-based applications. Libghostty 1.0 is portable, requires only libc, and can be built freestanding, with bindings available for multiple programming languages.

hackernews · mfiguiere · Nov 6, 23:30 · [Discussion](https://news.ycombinator.com/item?id=50399933)

**Background**: A terminal emulator is a program that emulates a video terminal, allowing users to interact with an operating system through a text-based interface. Libghostty is an open-source project that aims to provide a high-performance terminal emulator library.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Terminal_emulator">Terminal emulator - Wikipedia</a></li>
<li><a href="https://mitchellh.com/writing/libghostty-1-0">Libghostty 1.0 – Mitchell Hashimoto</a></li>
<li><a href="https://news.lavx.hu/article/libghostty-1-0-stabilizes-the-terminal-library-behind-ghostty">Libghostty 1.0 stabilizes the terminal library behind Ghostty</a></li>

</ul>
</details>

**Discussion**: Community feedback is overwhelmingly positive, with users praising the stability and performance of Libghostty, and expressing interest in its potential applications in new coding tools and terminal emulators.

**Tags**: `#Terminal Emulators`, `#Software Development`, `#Open Source`, `#Community Projects`, `#Technology`

---

<a id="item-4"></a>
## [Undocumented Family Member Classifier in macOS](https://8rank.ai/game/apple-intelligence-personal-knowledge-graph) ⭐️ 8.0/10

An analysis has uncovered an undocumented feature in Apple's macOS that classifies family members and constructs a personal knowledge graph. This feature raises concerns about privacy and how macOS collects and uses data, potentially impacting users' personal information. The feature is not documented, meaning it is not officially supported or acknowledged by Apple, and its presence was discovered through analysis.

hackernews · infwhispers · Nov 7, 09:46 · [Discussion](https://news.ycombinator.com/item?id=50403097)

**Background**: A personal knowledge graph is a visual representation of a person's relationships, activities, and information. macOS is an operating system developed by Apple Inc. for use on its Mac computers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=pmPA9_29VPg">Customizing the Mac Context Menu - YouTube</a></li>
<li><a href="https://www.tsuka.io/insights/the-purpose-of-interlinking-building-a-personal-knowledge-graph">The Purpose of Interlinking: Building a Personal Knowledge Graph</a></li>
<li><a href="https://archive.org/stream/Undocumented_DOS/Undocumented_DOS_djvu.txt">Full text of " Undocumented DOS"</a></li>

</ul>
</details>

**Discussion**: Community reactions range from concern about privacy to fascination with the technology, with some users considering a switch to alternative operating systems.

**Tags**: `#Apple`, `#macOS`, `#Privacy`, `#Data Collection`, `#Technology`

---

<a id="item-5"></a>
## [US FAA to Phase Out Floppy Disks in Air Traffic Control by 2028](https://www.reuters.com/world/us/us-faa-says-it-will-phase-out-floppy-disks-air-traffic-control-by-2028-2026-11-05/) ⭐️ 8.0/10

The US Federal Aviation Administration (FAA) has announced plans to phase out the use of floppy disks in air traffic control systems by 2028. This decision is significant as it marks a step towards modernizing air traffic control systems, potentially improving efficiency and safety in aviation. The FAA's current systems rely on legacy technology from the 1980s, using 1.44MB floppy disks for critical data storage.

hackernews · ChrisArchitect · Nov 6, 04:00 · [Discussion](https://news.ycombinator.com/item?id=50388001)

**Background**: Air traffic control systems have evolved significantly since the 1980s, with modern systems typically using more advanced storage solutions like solid-state drives (SSDs).

<details><summary>References</summary>
<ul>
<li><a href="https://www.theverge.com/transportation/1027511/faa-floppy-disks-sean-duffy-air-traffic-control-eids">The FAA is finally ditching floppy disks | The Verge</a></li>
<li><a href="https://www.pcmag.com/news/the-faa-is-still-using-floppy-disk-based-systems-but-thats-about-to-change">The FAA Is Still Using Floppy Disk -Based Systems , But... | PCMag</a></li>

</ul>
</details>

**Discussion**: Community discussions highlight concerns about the safety implications of using outdated technology and the need for a cautious yet progressive approach to modernization.

**Tags**: `#aviation`, `#air-traffic-control`, `#technology-modernization`, `#FAA`, `#floppy-disks`

---

<a id="item-6"></a>
## [Firecracker VM Escape: PwnEscape Part 2](https://pwn.ai/blog/firecracker-escape) ⭐️ 8.0/10

This blog post provides an in-depth analysis of a security vulnerability in Firecracker VMs, detailing the PwnEscape Part 2 exploit and its potential impact on virtualization security. The discovery of this vulnerability is significant as it highlights the security risks associated with virtualization technologies and underscores the importance of robust security measures in microVM environments. The analysis discusses the lack of a jailer in the configuration, which is a critical component for Firecracker's production containment, and the implications of not having proper privilege and resource restrictions in place.

hackernews · SerCe · Nov 6, 19:33 · [Discussion](https://news.ycombinator.com/item?id=50397219)

**Background**: Firecracker is an open-source virtualization technology designed for lightweight, secure, and fast microVMs. VM escape is a serious security concern as it allows an attacker to bypass the isolation of a virtual machine and potentially access the host system.

<details><summary>References</summary>
<ul>
<li><a href="https://firecracker-microvm.github.io/?trk">Firecracker</a></li>
<li><a href="https://fly.io/learn/firecracker-vm/">What Is a Firecracker microVM? · Learn</a></li>
<li><a href="https://github.com/firecracker-microvm/firecracker">GitHub - firecracker-microvm/firecracker: Secure and fast ... Firecracker MicroVM Review: Architecture, Setup, and Limitations Firecracker MicroVM Use Cases Explained — DevelopNSolve Firecracker MicroVM Sandboxing Features Explained What is a microVM? Firecracker vs containers (2026)</a></li>

</ul>
</details>

**Discussion**: Community discussions highlight concerns about the lack of detail in the article, the effectiveness of the Nova Microhypervisor approach, and the practical implications of the vulnerability for services relying on Firecracker VMs.

**Tags**: `#virtualization`, `#security`, `#Firecracker`, `#VM escape`, `#PwnEscape`

---