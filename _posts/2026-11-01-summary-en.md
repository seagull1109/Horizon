---
layout: default
title: "Horizon Summary: 2026-11-01 (EN)"
date: 2026-11-01
lang: en
---

> From 25 items, 8 important content pieces were selected

---

1. [Critical TCP Use-After-Free in Linux CVE-2026-98432](#item-1) ⭐️ 9.0/10
2. [Leaking Secrets from Air-Gapped Computers by Spelling Radio Signals from RAM](#item-2) ⭐️ 9.0/10
3. [ChatGPT Account Takeover Exploit Exposed](#item-3) ⭐️ 9.0/10
4. [Two-Stage Deep Learning for Neonatal Brain Pathology Detection](#item-4) ⭐️ 9.0/10
5. [Soft-MTP: Advancing Multi-Token Prediction](#item-5) ⭐️ 9.0/10
6. [HackerTube: YouTube Alternative Curated by HN Comments](#item-6) ⭐️ 8.0/10
7. [Memdoor Achieves Parity with Fable 5 on LiveCodeBench Hard](#item-7) ⭐️ 8.0/10
8. [LSREP: A Longitudinal State-Replay Protocol](#item-8) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Critical TCP Use-After-Free in Linux CVE-2026-98432](https://atlasum.net/blog/cve-2026-98432-linux-ipv4-tcp-uaf) ⭐️ 9.0/10

A critical TCP Use-After-Free vulnerability (CVE-2026-98432) has been identified in Linux, with a CVSS score of 9.8, indicating a high severity. This vulnerability affects the IPv4 TCP handshake and could potentially allow remote code execution. This vulnerability is significant as it affects a wide range of Linux systems and has the potential to lead to arbitrary code execution. It underscores the importance of timely patching and security updates in the Linux ecosystem. The vulnerability requires multiple CPU cores to exploit, making systems with a single core or packet processing pinned to a single core less susceptible. Mitigation strategies include disabling MPTCP and applying the latest kernel patches.

hackernews · oger · Oct 31, 19:16 · [Discussion](https://news.ycombinator.com/item?id=50319143)

**Background**: A Use-After-Free (UAF) vulnerability occurs when a program continues to use a memory location after it has been freed, potentially leading to arbitrary code execution. TCP is a core protocol in networking, facilitating communication between devices over an IP network.

<details><summary>References</summary>
<ul>
<li><a href="https://cybersecuritynews.com/use-after-free-vulnerability/">What is Use-After-Free Vulnerability? - Impact and Mitigation</a></li>
<li><a href="https://cwe.mitre.org/data/definitions/416.html">CWE - CWE-416: Use After Free (5.0) - Mitre Corporation</a></li>
<li><a href="https://atlasum.net/blog/cve-2026-98432-linux-ipv4-tcp-uaf">Linux's October 2026 TCP Use - After - Free : CVE-2026-98432 — Atlas</a></li>

</ul>
</details>

**Discussion**: Community discussions highlight concerns about the impact on systems with MPTCP enabled and the need for comprehensive patching. There is also a debate on the effectiveness of mitigation strategies and the potential for future vulnerabilities.

**Tags**: `#Linux`, `#Security Vulnerability`, `#TCP`, `#CVE-2026-98432`, `#Use-After-Free`

---

<a id="item-2"></a>
## [Leaking Secrets from Air-Gapped Computers by Spelling Radio Signals from RAM](https://arxiv.org/abs/2409.02292) ⭐️ 9.0/10

A research paper details a novel method to leak secrets from air-gapped computers by spelling radio signals from RAM, highlighting a significant cybersecurity concern. This method challenges the security of air-gapped systems, which are traditionally considered secure due to their isolation from networks, and has implications for protecting sensitive data and AI containment. The attack requires malware on the computer and a Software Defined Radio (SDR) antenna within 7 meters, with clear line of sight, to achieve a data transfer rate of 100 bits per second.

hackernews · hapax_legomena · Nov 1, 01:46 · [Discussion](https://news.ycombinator.com/item?id=50322022)

**Background**: Air-gapped systems are designed to be isolated from the internet and other networks to prevent unauthorized access and data breaches. Radio frequency attacks involve exploiting wireless communication vulnerabilities to intercept or disrupt signals.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Air_gap_(networking)">Air gap (networking) - Wikipedia</a></li>
<li><a href="https://dev.to/gargpadmakar/air-gapped-systems-explained-architecture-security-limitations-real-world-use-cases-2chi">Air-Gapped Systems Explained: Architecture, Security ...</a></li>
<li><a href="https://www.sentinelone.com/cybersecurity-101/cybersecurity/what-is-an-air-gap/">What is an Air Gap? Benefits and Best Practices - SentinelOne</a></li>
<li><a href="https://itenterpriser.com/knowledge-base/what-rf-attacks-are-and-how-to-defend-against-them/">What RF Attacks Are and How to Defend Against Them Radio Frequency 101: Can You Really Hack a Radio Signal? What is an RF cyber attack? - crfs.com Radio-Frequency Attacks: Securing the OSI Stack Radiofrequency Hacking Techniques – Physics of Cybersecurity Radio-Frequency Attacks: Securing the OSI Stack Frequency Jamming: A Technical Guide to Signal Interference</a></li>
<li><a href="https://www.sei.cmu.edu/blog/radio-frequency-101-can-you-really-hack-a-radio-signal/">Radio Frequency 101: Can You Really Hack a Radio Signal?</a></li>

</ul>
</details>

**Discussion**: Community discussions highlight concerns about the practicality of the attack, its implications for AI containment, and the potential for similar methods to be used in other contexts.

**Tags**: `#cybersecurity`, `#air-gapped systems`, `#radio frequency attacks`, `#information leakage`, `#research breakthrough`

---

<a id="item-3"></a>
## [ChatGPT Account Takeover Exploit Exposed](https://simonwillison.net/2026/Oct/31/how-we-took-over-chatgpt-accounts/) ⭐️ 9.0/10

Parameter Labs discovered a sophisticated exploit in ChatGPT's HTML preview implementation, potentially enabling unauthorized access to user accounts. This exploit highlights the importance of AI security and the need for robust cybersecurity measures in AI applications. The exploit leveraged the MathLive JavaScript library and a bypass of Content Security Policy (CSP) rules to execute arbitrary JavaScript and exfiltrate private data.

rss · Simon Willison · Oct 31, 23:15

**Background**: HTML previews in ChatGPT allow users to view and interact with custom HTML content within the platform. Sandboxing is a security technique used to isolate untrusted code.

<details><summary>References</summary>
<ul>
<li><a href="https://elsolitario.org/en/2026/10/31/chatgpt-vulnerability-mathlive-account-takeover/">ChatGPT Vulnerability: How It Worked - elsolitario.org</a></li>
<li><a href="https://labs.cloudsecurityalliance.org/research/csa-research-note-chatgpt-share-link-session-hijack-20261031/">One Click Into Someone Else’s ChatGPT: Cross-Frame Messaging ...</a></li>

</ul>
</details>

**Discussion**: The community is divided on the severity of the vulnerability, with some arguing it's a significant threat while others believe it was an overreaction.

**Tags**: `#AI Security`, `#ChatGPT`, `#OpenAI`, `#Exploit`, `#Cybersecurity`

---

<a id="item-4"></a>
## [Two-Stage Deep Learning for Neonatal Brain Pathology Detection](https://www.reddit.com/r/MachineLearning/comments/1xkcy83/hierarchical_detection_of_neonatal_brain/) ⭐️ 9.0/10

A two-stage deep learning framework has been developed for hierarchical detection of neonatal brain pathologies from MRI images, aiming to improve diagnosis accuracy. This breakthrough could significantly enhance the diagnosis of neonatal brain pathologies, leading to better treatment outcomes and potentially saving lives. The framework employs a two-stage approach, first segmenting the brain into regions of interest and then classifying these regions for disease detection.

reddit · r/MachineLearning · /u/rottoneuro · Oct 31, 15:21

**Background**: Neonatal brain pathologies are serious conditions affecting newborns, often requiring early detection and intervention. MRI is a key imaging modality for diagnosing these conditions.

<details><summary>References</summary>
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

**Discussion**: Reddit discussions highlight the potential impact of this research, with comments ranging from excitement about the technological advancement to concerns about the practical implementation in clinical settings.

**Tags**: `#neonatal brain pathology`, `#deep learning`, `#MRI`, `#neuroimaging`, `#machine learning`

---

<a id="item-5"></a>
## [Soft-MTP: Advancing Multi-Token Prediction](https://www.reddit.com/r/MachineLearning/comments/1xjnz40/multitoken_prediction_done_right_r/) ⭐️ 9.0/10

A novel approach called Soft-MTP has been introduced for multi-token prediction, improving upon existing methods by extracting the KL self-distillation signal from the MTP gradient and offering a practical implementation. This breakthrough enhances the efficiency and accuracy of multi-token prediction, which is crucial for natural language processing tasks, potentially leading to improvements in language models and speculative decoding. Soft-MTP involves a one-line code change to remove a noisy gradient residual, backpropagating only the KL self-distillation signal, and reusing existing NTP and MTP cross-entropy computations.

reddit · r/MachineLearning · /u/jayden_teoh_ · Oct 30, 18:53

**Background**: Multi-token prediction is a key component in natural language processing, particularly in language models, where it helps in predicting the next token based on the context of previous tokens.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2508.15807v1">[2508.15807v1] KL-based self-distillation for large language ... Knowledge Distillation - GeeksforGeeks [2206.08491] Revisiting Self-Distillation - arXiv.org Understanding Self-Distillation and Privileged Information ... Knowledge Distillation: Teacher-Student Loss Explained Knowledge distillation - Wikipedia Self-Distillation in Deep Learning</a></li>
<li><a href="https://arxiv.org/abs/2610.38331">[2610.38331] Multi - Token Prediction Done Right</a></li>

</ul>
</details>

**Discussion**: The Reddit community has shown interest in the topic, with discussions likely including insights and debates on the effectiveness and potential applications of Soft-MTP.

**Tags**: `#MachineLearning`, `#NaturalLanguageProcessing`, `#PreTraining`, `#ResearchBreakthrough`

---

<a id="item-6"></a>
## [HackerTube: YouTube Alternative Curated by HN Comments](https://karpathy.bearblog.dev/hacker-tube/) ⭐️ 8.0/10

HackerTube, a YouTube-style platform, has launched, sourcing videos from Hacker News comments since 2007, offering a unique content consumption experience. This platform is significant as it challenges traditional content curation models by leveraging community-driven content, potentially reshaping how users engage with online video content. The platform uses an API key from Google Cloud to query YouTube for video metadata and operates on a VPS box, showcasing the technical aspects of its creation.

hackernews · karpathy · Oct 31, 19:56 · [Discussion](https://news.ycombinator.com/item?id=50319510)

**Background**: Hacker News is a social news website focusing on computer science and entrepreneurship, known for its community-driven content curation. HackerTube utilizes this model to curate video content.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/?ref=dtf.ru">Hacker News</a></li>
<li><a href="https://www.newyorker.com/news/letter-from-silicon-valley/the-lonely-work-of-moderating-hacker-news">The Lonely Work of Moderating Hacker News | The New Yorker</a></li>
<li><a href="https://www.udemy.com/topic/algorithms/">Top Algorithms Courses Online - Updated [October 2026]</a></li>

</ul>
</details>

**Discussion**: Community feedback is largely positive, with users appreciating the lack of clickbait and the opportunity to discover new content outside of traditional algorithms.

**Tags**: `#Content Curation`, `#YouTube Alternative`, `#Hacker News`, `#Community Curated`, `#Online Video`

---

<a id="item-7"></a>
## [Memdoor Achieves Parity with Fable 5 on LiveCodeBench Hard](https://github.com/guregodevo/memdoor/tree/main/examples/workflows/team-solve) ⭐️ 8.0/10

A team of five Qwen3.8-27B models has achieved parity with Fable 5 on the LiveCodeBench Hard benchmark, indicating significant local performance potential for AI models. This development showcases the growing capabilities of AI models in local environments, potentially reducing reliance on cloud-based services and enhancing privacy and efficiency. The Qwen3.8-27B models are known for their hybrid attention pattern and large context window, which contributes to their strong performance on coding tasks.

hackernews · guregodevo · Oct 31, 22:46 · [Discussion](https://news.ycombinator.com/item?id=50320995)

**Background**: LiveCodeBench Hard is a rigorous benchmark for evaluating AI models on coding challenges, while Qwen3.8-27B is an AI model known for its advanced architecture and performance.

<details><summary>References</summary>
<ul>
<li><a href="https://www.mindstudio.ai/blog/nanbeige4-3-33b-benchmark-comparison">Nanbeige4.3-33B Benchmarks: How It Beats Qwen 3 . 8 - 27 B and ...</a></li>
<li><a href="https://codersera.com/blog/how-to-run-qwen-3-8-locally-2026/">How to Run Qwen 3 . 8 Locally: 27 B on 16–24GB GPUs (2026)</a></li>
<li><a href="https://typilot.com/blog/qwen3-8-27b-run-locally">Qwen 3 . 8 - 27 B : Run It Locally in Ollama | Typilot</a></li>

</ul>
</details>

**Discussion**: Community discussions highlight concerns about the reliance on cloud services and the potential for local AI models to improve efficiency and privacy.

**Tags**: `#AI Research`, `#Machine Learning`, `#Model Performance`, `#Benchmarking`, `#AI Development`

---

<a id="item-8"></a>
## [LSREP: A Longitudinal State-Replay Protocol](https://www.reddit.com/r/MachineLearning/comments/1xkzwz9/lsrep_a_longitudinal_statereplay_protocol_for/) ⭐️ 8.0/10

An undergraduate researcher introduces LSREP, a protocol for evaluating conversational memory systems, and discusses its application on the ICE v2 system, revealing findings on memory persistence and retrieval. LSREP's novel approach to evaluating conversational memory systems could significantly impact the field of AI/ML by providing a more comprehensive understanding of memory persistence and retrieval over time. LSREP combines chronological replay, lifecycle schedules, repeated probes, evolving reference answers, and mechanism-fidelity checks to evaluate conversational memory systems.

reddit · r/MachineLearning · /u/Deepnar_S · Nov 1, 10:38

**Background**: Conversational memory systems are a crucial component of AI/ML, enabling machines to retain and utilize information over the course of a conversation. Evaluating these systems is essential for understanding their capabilities and limitations.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.16730">LSREP: A Longitudinal State-Replay Protocol for Evaluating ...</a></li>
<li><a href="https://arxiv.org/pdf/2609.16730">LSREP: A Longitudinal State-Replay Protocol for Evaluating ...</a></li>
<li><a href="https://kblip.com/research/lsrep-a-longitudinal-state-replay-protocol-for-evaluating-kH7T8ff">LSREP: A Longitudinal State-Replay Protocol for Evaluating ...</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion indicates a mix of positive feedback on the research's methodology and concerns about the limitations of the ICE v2 system.

**Tags**: `#Conversational Memory`, `#AI Research`, `#Machine Learning`, `#Evaluation Protocols`, `#Natural Language Processing`

---