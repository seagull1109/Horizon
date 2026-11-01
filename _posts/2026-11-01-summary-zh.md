---
layout: default
title: "Horizon Summary: 2026-11-01 (ZH)"
date: 2026-11-01
lang: zh
---

> 从 25 条内容中筛选出 8 条重要资讯。

---

1. [Linux 中严重的 TCP Use-After-Free 漏洞 CVE-2026-98432](#item-1) ⭐️ 9.0/10
2. [通过从 RAM 拼写无线电信号泄露空气隔离计算机的秘密](#item-2) ⭐️ 9.0/10
3. [ChatGPT 账户接管漏洞被揭露](#item-3) ⭐️ 9.0/10
4. [两阶段深度学习新生儿脑部疾病检测](#item-4) ⭐️ 9.0/10
5. [Soft-MTP：多令牌预测的进步](#item-5) ⭐️ 9.0/10
6. [HackerTube：由 Hacker News 评论推荐的 YouTube 替代品](#item-6) ⭐️ 8.0/10
7. [Memdoor 在 LiveCodeBench Hard 上与 Fable 5 实现性能 parity](#item-7) ⭐️ 8.0/10
8. [LSREP：纵向状态回放协议](#item-8) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Linux 中严重的 TCP Use-After-Free 漏洞 CVE-2026-98432](https://atlasum.net/blog/cve-2026-98432-linux-ipv4-tcp-uaf) ⭐️ 9.0/10

Linux 中存在一个严重的 TCP Use-After-Free 漏洞（CVE-2026-98432），CVSS 评分为 9.8，表明漏洞严重。该漏洞影响 IPv4 TCP 握手，可能允许远程代码执行。 这个漏洞很重要，因为它影响了广泛的 Linux 系统，并可能导致任意代码执行。这强调了及时打补丁和更新 Linux 生态系统安全的重要性。 该漏洞需要多个 CPU 核心来利用，使得单核心或核心绑定到单个核心的系统不太容易受到攻击。缓解策略包括禁用 MPTCP 和安装最新的内核补丁。

hackernews · oger · 10月31日 19:16 · [社区讨论](https://news.ycombinator.com/item?id=50319143)

**背景**: Use-After-Free（UAF）漏洞发生在程序在释放内存后继续使用该内存位置的情况下，可能导致任意代码执行。TCP 是网络的核心协议，负责在 IP 网络上设备之间的通信。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cybersecuritynews.com/use-after-free-vulnerability/">What is Use-After-Free Vulnerability? - Impact and Mitigation</a></li>
<li><a href="https://cwe.mitre.org/data/definitions/416.html">CWE - CWE-416: Use After Free (5.0) - Mitre Corporation</a></li>
<li><a href="https://atlasum.net/blog/cve-2026-98432-linux-ipv4-tcp-uaf">Linux's October 2026 TCP Use - After - Free : CVE-2026-98432 — Atlas</a></li>

</ul>
</details>

**社区讨论**: 社区讨论突出了 MPTCP 启用系统的影响和全面打补丁的需求。同时，也存在关于缓解策略有效性和未来漏洞潜力的辩论。

**标签**: `#Linux`, `#Security Vulnerability`, `#TCP`, `#CVE-2026-98432`, `#Use-After-Free`

---

<a id="item-2"></a>
## [通过从 RAM 拼写无线电信号泄露空气隔离计算机的秘密](https://arxiv.org/abs/2409.02292) ⭐️ 9.0/10

一篇研究论文详细介绍了通过从 RAM 拼写无线电信号泄露空气隔离计算机秘密的新方法，凸显了网络安全方面的重大担忧。 此方法挑战了空气隔离系统的安全性，这些系统传统上被认为是安全的，因为它们与网络的隔离，并对保护敏感数据和 AI 控制有影响。 攻击需要在计算机上安装恶意软件，并且需要 7 米内的软件定义无线电（SDR）天线，视线清晰，以实现每秒 100 位的传输速率。

hackernews · hapax_legomena · 11月1日 01:46 · [社区讨论](https://news.ycombinator.com/item?id=50322022)

**背景**: 空气隔离系统旨在与互联网和其他网络隔离，以防止未经授权的访问和数据泄露。无线电频率攻击涉及利用无线通信漏洞来拦截或破坏信号。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Air_gap_(networking)">Air gap (networking) - Wikipedia</a></li>
<li><a href="https://dev.to/gargpadmakar/air-gapped-systems-explained-architecture-security-limitations-real-world-use-cases-2chi">Air-Gapped Systems Explained: Architecture, Security ...</a></li>
<li><a href="https://www.sentinelone.com/cybersecurity-101/cybersecurity/what-is-an-air-gap/">What is an Air Gap? Benefits and Best Practices - SentinelOne</a></li>
<li><a href="https://itenterpriser.com/knowledge-base/what-rf-attacks-are-and-how-to-defend-against-them/">What RF Attacks Are and How to Defend Against Them Radio Frequency 101: Can You Really Hack a Radio Signal? What is an RF cyber attack? - crfs.com Radio-Frequency Attacks: Securing the OSI Stack Radiofrequency Hacking Techniques – Physics of Cybersecurity Radio-Frequency Attacks: Securing the OSI Stack Frequency Jamming: A Technical Guide to Signal Interference</a></li>
<li><a href="https://www.sei.cmu.edu/blog/radio-frequency-101-can-you-really-hack-a-radio-signal/">Radio Frequency 101: Can You Really Hack a Radio Signal?</a></li>

</ul>
</details>

**社区讨论**: 社区讨论突出了对攻击可行性的担忧，其对 AI 控制的含义，以及在其他环境中使用类似方法的潜力。

**标签**: `#cybersecurity`, `#air-gapped systems`, `#radio frequency attacks`, `#information leakage`, `#research breakthrough`

---

<a id="item-3"></a>
## [ChatGPT 账户接管漏洞被揭露](https://simonwillison.net/2026/Oct/31/how-we-took-over-chatgpt-accounts/) ⭐️ 9.0/10

Parameter Labs 发现 ChatGPT 的 HTML 预览实现中存在一个复杂的漏洞，可能导致未经授权访问用户账户。 这个漏洞凸显了 AI 安全的重要性以及人工智能应用中需要采取强大网络安全措施的需求。 该漏洞利用了 MathLive JavaScript 库和绕过内容安全策略（CSP）规则来执行任意 JavaScript 并窃取私人数据。

rss · Simon Willison · 10月31日 23:15

**背景**: ChatGPT 中的 HTML 预览允许用户在平台上查看和交互自定义 HTML 内容。沙箱是一种用于隔离不受信任代码的安全技术。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://elsolitario.org/en/2026/10/31/chatgpt-vulnerability-mathlive-account-takeover/">ChatGPT Vulnerability: How It Worked - elsolitario.org</a></li>
<li><a href="https://labs.cloudsecurityalliance.org/research/csa-research-note-chatgpt-share-link-session-hijack-20261031/">One Click Into Someone Else’s ChatGPT: Cross-Frame Messaging ...</a></li>

</ul>
</details>

**社区讨论**: 社区对漏洞的严重性意见不一，一些人认为这是一个重大的威胁，而另一些人则认为这是过度反应。

**标签**: `#AI Security`, `#ChatGPT`, `#OpenAI`, `#Exploit`, `#Cybersecurity`

---

<a id="item-4"></a>
## [两阶段深度学习新生儿脑部疾病检测](https://www.reddit.com/r/MachineLearning/comments/1xkcy83/hierarchical_detection_of_neonatal_brain/) ⭐️ 9.0/10

一种两阶段深度学习框架被开发出来，用于从 MRI 图像中分层检测新生儿脑部疾病，旨在提高诊断准确性。 这一突破可以显著提高新生儿脑部疾病的诊断，从而改善治疗效果，并可能挽救生命。 该框架采用两阶段方法，首先将大脑分割成感兴趣的区域，然后对这些区域进行分类以检测疾病。

reddit · r/MachineLearning · /u/rottoneuro · 10月31日 15:21

**背景**: 新生儿脑部疾病是严重影响新生儿的严重疾病，通常需要早期检测和干预。MRI 是诊断这些疾病的关键成像方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hal.science/hal-05218773v1/document">Deep Learning Framework for Managing Inter-Reader Variability in...</a></li>
<li><a href="https://arxiv.org/abs/2604.17118">[2604.17118] A Two - Stage Deep Learning Framework for...</a></li>
<li><a href="https://www.emergentmind.com/topics/deepap">DeepAP: Deep Learning for Aperture Photometry</a></li>
<li><a href="https://www.frontiersin.org/journals/neuroimaging/articles/10.3389/fnimg.2026.1981436/full">Hierarchical detection of neonatal brain ... - Frontiers</a></li>
<li><a href="https://link.springer.com/article/10.1007/s00247-023-05620-x">An automatic and accurate deep learning-based neuroimaging ...</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12359275/">AI-Driven Neonatal MRI Interpretation: A Systematic Review of ...</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0146000525001028">Neonatal neuroimaging: from research to bedside practice</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S234128792500300X">Recommendations for the use of brain MRI in the neonatal ...</a></li>
<li><a href="https://www.mrineonatalbrain.com/">MRI of the Neonatal Brain - Mary A Rutherford</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的讨论突出了这项研究的潜在影响，评论从对技术进步的兴奋到对临床环境中实际实施的担忧，观点各异。

**标签**: `#neonatal brain pathology`, `#deep learning`, `#MRI`, `#neuroimaging`, `#machine learning`

---

<a id="item-5"></a>
## [Soft-MTP：多令牌预测的进步](https://www.reddit.com/r/MachineLearning/comments/1xjnz40/multitoken_prediction_done_right_r/) ⭐️ 9.0/10

一种名为 Soft-MTP 的新方法被引入到多令牌预测中，通过从 MTP 梯度中提取 KL 自蒸馏信号，改进了现有方法，并提供了一种实用的实现。 这一突破提高了多令牌预测的效率和准确性，这对于自然语言处理任务至关重要，可能导致语言模型和推测解码的改进。 Soft-MTP 涉及一行代码更改，以删除噪声梯度残留，仅回传 KL 自蒸馏信号，并重用现有的 NTP 和 MTP 交叉熵计算。

reddit · r/MachineLearning · /u/jayden_teoh_ · 10月30日 18:53

**背景**: 多令牌预测是自然语言处理的关键组成部分，特别是在语言模型中，它有助于根据先前令牌的上下文预测下一个令牌。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2508.15807v1">[2508.15807v1] KL-based self-distillation for large language ... Knowledge Distillation - GeeksforGeeks [2206.08491] Revisiting Self-Distillation - arXiv.org Understanding Self-Distillation and Privileged Information ... Knowledge Distillation: Teacher-Student Loss Explained Knowledge distillation - Wikipedia Self-Distillation in Deep Learning</a></li>
<li><a href="https://arxiv.org/abs/2610.38331">[2610.38331] Multi - Token Prediction Done Right</a></li>

</ul>
</details>

**社区讨论**: Reddit 社区对这一主题表现出兴趣，讨论可能包括对 Soft-MTP 的有效性和潜在应用的见解和辩论。

**标签**: `#MachineLearning`, `#NaturalLanguageProcessing`, `#PreTraining`, `#ResearchBreakthrough`

---

<a id="item-6"></a>
## [HackerTube：由 Hacker News 评论推荐的 YouTube 替代品](https://karpathy.bearblog.dev/hacker-tube/) ⭐️ 8.0/10

HackerTube，一个类似 YouTube 的平台，已上线，从 2007 年起从 Hacker News 评论中获取视频，提供独特的内容消费体验。 这个平台通过利用社区驱动的内容挑战了传统的内容推荐模式，可能会重塑用户与在线视频内容互动的方式。 该平台使用 Google Cloud 的 API 密钥查询 YouTube 的视频元数据，并在 VPS 服务器上运行，展示了其创建的技术细节。

hackernews · karpathy · 10月31日 19:56 · [社区讨论](https://news.ycombinator.com/item?id=50319510)

**背景**: Hacker News 是一个专注于计算机科学和创业的社会新闻网站，以其社区驱动的内容推荐而闻名。HackerTube 利用这种模式来推荐视频内容。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/?ref=dtf.ru">Hacker News</a></li>
<li><a href="https://www.newyorker.com/news/letter-from-silicon-valley/the-lonely-work-of-moderating-hacker-news">The Lonely Work of Moderating Hacker News | The New Yorker</a></li>
<li><a href="https://www.udemy.com/topic/algorithms/">Top Algorithms Courses Online - Updated [October 2026]</a></li>

</ul>
</details>

**社区讨论**: 社区反馈普遍积极，用户赞赏没有点击诱饵，并且有机会在传统的算法之外发现新内容。

**标签**: `#Content Curation`, `#YouTube Alternative`, `#Hacker News`, `#Community Curated`, `#Online Video`

---

<a id="item-7"></a>
## [Memdoor 在 LiveCodeBench Hard 上与 Fable 5 实现性能 parity](https://github.com/guregodevo/memdoor/tree/main/examples/workflows/team-solve) ⭐️ 8.0/10

一支由 5 个 Qwen3.8-27B 模型组成的团队在 LiveCodeBench Hard 基准测试中与 Fable 5 实现了性能 parity，这表明 AI 模型在本地具有显著的性能潜力。 这一进展展示了 AI 模型在本地环境中的能力，可能减少对基于云的服务依赖，并提高隐私和效率。 Qwen3.8-27B 模型以其混合注意力模式和大型上下文窗口而闻名，这有助于其在编码任务上表现出色。

hackernews · guregodevo · 10月31日 22:46 · [社区讨论](https://news.ycombinator.com/item?id=50320995)

**背景**: LiveCodeBench Hard 是一个评估 AI 模型在编码挑战上的严格基准，而 Qwen3.8-27B 是一个以其先进架构和性能而闻名的 AI 模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.mindstudio.ai/blog/nanbeige4-3-33b-benchmark-comparison">Nanbeige4.3-33B Benchmarks: How It Beats Qwen 3 . 8 - 27 B and ...</a></li>
<li><a href="https://codersera.com/blog/how-to-run-qwen-3-8-locally-2026/">How to Run Qwen 3 . 8 Locally: 27 B on 16–24GB GPUs (2026)</a></li>
<li><a href="https://typilot.com/blog/qwen3-8-27b-run-locally">Qwen 3 . 8 - 27 B : Run It Locally in Ollama | Typilot</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调了对外部云服务的依赖，以及本地 AI 模型提高效率和隐私的潜力。

**标签**: `#AI Research`, `#Machine Learning`, `#Model Performance`, `#Benchmarking`, `#AI Development`

---

<a id="item-8"></a>
## [LSREP：纵向状态回放协议](https://www.reddit.com/r/MachineLearning/comments/1xkzwz9/lsrep_a_longitudinal_statereplay_protocol_for/) ⭐️ 8.0/10

一名本科生研究者推出了 LSREP，一种用于评估对话记忆系统的协议，并在 ICE v2 系统上讨论了其应用，揭示了关于记忆持久性和检索的发现。 LSREP 在评估对话记忆系统方面的创新方法可能通过提供对时间上记忆持久性和检索的更全面理解，对人工智能/机器学习领域产生重大影响。 LSREP 结合了按时间顺序回放、生命周期计划、重复探测、演变的参考答案和机制保真度检查来评估对话记忆系统。

reddit · r/MachineLearning · /u/Deepnar_S · 11月1日 10:38

**背景**: 对话记忆系统是人工智能/机器学习的关键组成部分，使机器能够在对话过程中保留和利用信息。评估这些系统对于理解其能力和局限性至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.16730">LSREP: A Longitudinal State-Replay Protocol for Evaluating ...</a></li>
<li><a href="https://arxiv.org/pdf/2609.16730">LSREP: A Longitudinal State-Replay Protocol for Evaluating ...</a></li>
<li><a href="https://kblip.com/research/lsrep-a-longitudinal-state-replay-protocol-for-evaluating-kH7T8ff">LSREP: A Longitudinal State-Replay Protocol for Evaluating ...</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的讨论表明，对研究方法的正面反馈和对 ICE v2 系统局限性的担忧并存。

**标签**: `#Conversational Memory`, `#AI Research`, `#Machine Learning`, `#Evaluation Protocols`, `#Natural Language Processing`

---