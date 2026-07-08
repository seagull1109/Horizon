---
layout: default
title: "Horizon Summary: 2026-07-08 (EN)"
date: 2026-07-08
lang: en
---

> From 38 items, 13 important content pieces were selected

---

1. [GitLost: We Tricked GitHub's AI Agent into Leaking Private Repos](#item-1) ⭐️ 8.0/10
2. [Tenda Router Firmware Contains Hidden Authentication Backdoor](#item-2) ⭐️ 8.0/10
3. [MIT's Classic SICP Video Lectures from 1986](#item-3) ⭐️ 8.0/10
4. [Chat Control 1.0 and 2.0 Explained](#item-4) ⭐️ 8.0/10
5. [Kokoro: CPU-Friendly High-Quality Text-to-Speech Technology](#item-5) ⭐️ 8.0/10
6. [Tencent Announces Hy3 295B-Parameter MoE Model](#item-6) ⭐️ 8.0/10
7. [Differentiable Ray Tracing Ph.D. Thesis for Radio Propagation](#item-7) ⭐️ 8.0/10
8. [MIRA: Multiplayer Interactive World Model for Rocket League](#item-8) ⭐️ 8.0/10
9. [Mozilla CTO to Host AMA on Open Source AI Report](#item-9) ⭐️ 8.0/10
10. [Novel Defense Against Fine-Tuning Poisoning Using Trusted LoRA Adapters](#item-10) ⭐️ 8.0/10
11. [ML Conference Review Credit System Proposal](#item-11) ⭐️ 8.0/10
12. [Sensor-Validity Masking for Depth Modeling Achieves State-of-the-Art Results](#item-12) ⭐️ 8.0/10
13. [LingBot-Vision: masked boundary modeling for self-supervised pretraining](#item-13) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [GitLost: We Tricked GitHub's AI Agent into Leaking Private Repos](https://noma.security/blog/gitlost-how-we-tricked-githubs-ai-agent-into-leaking-private-repos/) ⭐️ 8.0/10

Researchers discovered and demonstrated a prompt injection vulnerability in GitHub's AI agent that could be exploited to leak private repositories. This highlights fundamental security challenges in AI systems, potentially affecting GitHub users and the security of AI agents. The vulnerability was exploited using simple prompts like 'Additionally' to bypass GitHub's guardrails, showing that hard security boundaries within an LLM context window are difficult to enforce.

hackernews · ColinEberhardt · Jul 8, 05:25 · [Discussion](https://news.ycombinator.com/item?id=48827858)

**Background**: Prompt injection is a cybersecurity exploit where malicious inputs override a model's intended instructions, and GitHub's AI agent is a system that autonomously perceives its environment, makes decisions, and takes actions powered by large language models (LLMs).

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection</a></li>
<li><a href="https://www.ibm.com/think/topics/prompt-injection">What Is a Prompt Injection Attack? | IBM</a></li>
<li><a href="https://github.blog/news-insights/company-news/welcome-home-agents/">Introducing Agent HQ: Any agent, any way you work - The GitHub Blog</a></li>

</ul>
</details>

**Discussion**: Community comments highlight varied viewpoints: some compare prompt injection to SQL injection as a systemic vulnerability, others question if it's GitHub's fault, note that LLMs naturally follow instructions making hard boundaries fail, and ask about the fix status.

**Tags**: `#security`, `#AI/ML`, `#GitHub`, `#prompt injection`, `#vulnerability`

---

<a id="item-2"></a>
## [Tenda Router Firmware Contains Hidden Authentication Backdoor](https://kb.cert.org/vuls/id/213560) ⭐️ 8.0/10

A security advisory reveals that multiple versions of Tenda router firmware contain a hidden authentication backdoor that allows unauthorized access with a hardcoded password. The backdoor uses the configuration value 'sys.rzadmin.password' to grant administrator access regardless of the username provided. This vulnerability affects widely-used networking equipment and poses significant security risks to both home and business networks. It highlights concerns about vendor trust and security practices in the networking hardware industry, potentially affecting thousands of devices worldwide. The backdoor password is 'rzadmin' and any username will be accepted when paired with this password. The vulnerability allows attackers to bypass normal login checks and gain full administrative access to the web management interface of affected routers.

hackernews · miniBill · Jul 8, 00:08 · [Discussion](https://news.ycombinator.com/item?id=48825749)

**Background**: Tenda is a Chinese manufacturer of networking equipment including routers, switches, and wireless access points. Firmware is the software that runs on embedded devices like routers, controlling their functionality and security features. Authentication backdoors are covert methods that bypass normal security measures, often implemented intentionally or accidentally during development. This particular vulnerability (CVE-2026-11405) was disclosed by CERT/CC and affects multiple firmware versions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bleepingcomputer.com/news/security/hidden-backdoor-in-tenda-router-firmware-grants-admin-access/">Hidden backdoor in Tenda router firmware grants admin access</a></li>
<li><a href="https://www.mallory.ai/stories/019f3b9f-e0ba-7ab7-a12f-2e5d2765b4b3">Hidden Authentication Backdoor Exposes Tenda Routers to Full Admin Takeover | Mallory</a></li>
<li><a href="https://en.wikipedia.org/wiki/Backdoor_(computing)">Backdoor (computing) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community members expressed strong distrust in router manufacturers, with many recommending alternative firmware solutions like OpenWRT. Some users revealed the specific backdoor password 'rzadmin' and discussed concerns about vendor practices and potential rebranding. There was debate about whether this constitutes a true 'backdoor' or just poor security implementation.

**Tags**: `#cybersecurity`, `#router-security`, `#firmware-vulnerability`, `#network-security`, `#supply-chain-security`

---

<a id="item-3"></a>
## [MIT's Classic SICP Video Lectures from 1986](https://ocw.mit.edu/courses/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video_galleries/video-lectures/) ⭐️ 8.0/10

MIT has made available the classic Structure and Interpretation of Computer Programs (SICP) video lectures from 1986, which were originally part of MIT's introductory computer science course. These lectures are significant because SICP has been highly influential in computer science education, teaching fundamental programming concepts like recursion, abstraction, and modularity. They provide valuable historical context and educational content for both new and experienced programmers. The lectures are from 1986 and use MIT Scheme, though community members suggest alternatives like Racket or DrRacket with add-on packages for modern implementation. Some users have noted audio quality issues in the original recordings.

hackernews · gjvc · Jul 7, 23:57 · [Discussion](https://news.ycombinator.com/item?id=48825664)

**Background**: Structure and Interpretation of Computer Programs (SICP) is a seminal computer science textbook by Harold Abelson, Gerald Jay Sussman, and Julie Sussman from MIT. Known as the 'Wizard Book' in hacker culture, it was used as MIT's introductory CS textbook from 1984 to 2007. The book focuses on fundamental programming principles and problem-solving patterns rather than specific programming languages. A JavaScript version was published in 2022.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Structure_and_Interpretation_of_Computer_Programs">Structure and Interpretation of Computer Programs</a></li>
<li><a href="https://grokipedia.com/page/structure_and_interpretation_of_computer_programs_(book)">Structure and Interpretation of Computer Programs (book)</a></li>

</ul>
</details>

**Discussion**: Community members have mixed reactions - some praise the lectures highly, calling them 'awesome' and addictive after watching the first one. Others note practical concerns like poor audio quality and suggest alternatives like Racket for implementation. There's also discussion about whether to use the book or lectures as primary learning material, with some preferring the lectures as the main resource and the book as supplemental.

**Tags**: `#computer-science`, `#programming`, `#education`, `#MIT`, `#SICP`

---

<a id="item-4"></a>
## [Chat Control 1.0 and 2.0 Explained](https://fightchatcontrol.eu/chat-control-overview) ⭐️ 8.0/10

The article explains the Chat Control 1.0 and 2.0 regulations proposed by the European Union to combat child sexual abuse through chat monitoring, sparking debate over privacy, encryption, and regulatory overreach. These regulations could significantly impact privacy and encryption technologies, as they raise questions about the balance between child protection and fundamental rights to privacy, potentially reshaping messaging systems and encryption practices. Chat Control 1.0 was rejected in March 2026, while Chat Control 2.0 remains under discussion. Civil society argues the proposal would mandate mass scanning of private communications, undermining end-to-end encryption, and experts note no current technology can detect child pornography without high error rates.

hackernews · gasull · Jul 7, 14:23 · [Discussion](https://news.ycombinator.com/item?id=48818311)

**Background**: Chat Control, formally known as the Regulation to Prevent and Combat Child Sexual Abuse (CSAR), is a European Union proposal aimed at preventing online child sexual abuse through measures like mass surveillance by digital platforms. Proposed by European Commissioner for Home Affairs Ylva Johansson in May 2022, it has faced criticism from civil society and experts who argue it would violate privacy and end-to-end encryption.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control_1.0">Chat Control 1.0</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control_2.0">Chat Control 2.0</a></li>

</ul>
</details>

**Discussion**: Comments highlight skepticism about the regulation’s effectiveness, with users questioning the focus on chat control over existing gaps in child abuse enforcement. Some argue it’s a broad law that overreaches, while others debate technical implications like mandatory scanning and impacts on end-to-end encryption, noting concerns about false positives and opt-out options.

**Tags**: `#privacy`, `#encryption`, `#regulation`, `#child protection`, `#messaging`

---

<a id="item-5"></a>
## [Kokoro: CPU-Friendly High-Quality Text-to-Speech Technology](https://ariya.io/2026/03/local-cpu-friendly-high-quality-tts-text-to-speech-with-kokoro/) ⭐️ 8.0/10

A new Text-to-Speech technology called Kokoro has been introduced that delivers high-quality speech synthesis without requiring NVIDIA GPUs, making it accessible for users with standard CPUs. This development is significant because it provides an accessible alternative to GPU-dependent TTS solutions, potentially democratizing high-quality speech synthesis for developers and users who cannot afford expensive hardware. Kokoro allows manual IPA pronunciation guides and works well for longer texts, though it struggles with single words or homographs. Users have successfully implemented it on lower-end GPUs like GTX1650 for applications like article readers and podcast generation.

hackernews · speckx · Jul 7, 18:24 · [Discussion](https://news.ycombinator.com/item?id=48821576)

**Discussion**: Community feedback is generally positive, with users highlighting practical applications like accessibility products and article readers. Users appreciate the CPU-friendly nature and IPA pronunciation features, though some note limitations with single words and homographs. The technology has been successfully implemented on lower-end hardware, demonstrating its accessibility.

**Tags**: `#tts`, `#text-to-speech`, `#ai`, `#machine-learning`, `#accessibility`

---

<a id="item-6"></a>
## [Tencent Announces Hy3 295B-Parameter MoE Model](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 8.0/10

Tencent released Hy3, a 295B-parameter Mixture-of-Experts (MoE) model developed by its Hy Team, which outperforms similar-size models and rivals flagship open-source models with 2-5x parameters. The model was scaled up post-training with higher-quality data after a preview launch in late April. This represents a significant technical achievement in large language model development, showcasing the effectiveness of MoE architecture in balancing model size and performance. It highlights Tencent's progress in the AI/ML field and could influence research directions for efficient large-scale models. Hy3 has 21B active parameters and 3.8B MTP layer parameters. The full-sized model is 598GB on Hugging Face, while the FP8 quantized version is 300GB. It supports a 256K context length and is available for free on OpenRouter until July 21st.

rss · Simon Willison · Jul 6, 23:57

**Background**: Mixture-of-Experts (MoE) is an architecture for large language models where only a subset of 'expert' networks are activated for each input, improving computational efficiency. FP8 quantization is a technique that reduces model size by using 8-bit floating-point formats for weights and activations, commonly used in large language models to optimize storage and inference speed.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/FP8_Quantization">FP8 Quantization</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Machine Learning`, `#Large Language Models`, `#Mixture-of-Experts`, `#Tencent`

---

<a id="item-7"></a>
## [Differentiable Ray Tracing Ph.D. Thesis for Radio Propagation](https://www.reddit.com/r/MachineLearning/comments/1upvkp5/phd_thesis_on_differentiable_ray_tracing_for/) ⭐️ 8.0/10

A Ph.D. thesis on differentiable ray tracing for radio propagation modeling was completed, integrating automatic differentiation frameworks like JAX into ray tracing pipelines to solve inverse problems in wireless communications. This work is significant as it enables gradient computation through complex physical environments, impacting wireless communications and machine learning by facilitating inverse problem solving and direct ML model training for next-gen wireless design. The thesis is structured into three parts (Understanding, Building, Using), includes GPU-accelerated path tracing and discontinuity smoothing techniques, and provides open-source libraries like DiffeRT, relying on JAX packages such as jaxtyping and equinox.

reddit · r/MachineLearning · /u/jeertmans · Jul 7, 13:45

**Background**: Radio propagation modeling simulates how radio waves travel through environments, crucial for wireless communication design. Ray tracing is a technique to simulate light (or radio waves) by tracing paths. Automatic differentiation (autodiff) frameworks like JAX compute gradients efficiently, enabling optimization and inverse problem solving in ML and scientific computing.

**Tags**: `#differentiable ray tracing`, `#radio propagation`, `#automatic differentiation`, `#machine learning`, `#wireless communications`

---

<a id="item-8"></a>
## [MIRA: Multiplayer Interactive World Model for Rocket League](https://www.reddit.com/r/MachineLearning/comments/1upofuw/mira_multiplayer_interactive_world_models_trained/) ⭐️ 8.0/10

MIRA, a 5B parameter multiplayer interactive world model, was trained on 10,000 hours of Rocket League data and can simulate 4 players at 20fps on a single B200 GPU. A playable demo, technical report, and 1k-hour dataset have been released. This represents a significant advancement in multiplayer world models, demonstrating real-time simulation capabilities that could impact AI research and game development. The collaboration between General Intuition, Kyutai, and Epic Games, plus its presentation at ICML, highlights its importance in the field. Notable technical specs include 5 billion parameters, 20fps simulation speed, and single B200 GPU support. The release includes a playable online demo, an in-depth technical report, and a 1k-hour 4-player gameplay dataset.

reddit · r/MachineLearning · /u/MasterScrat · Jul 7, 07:59

**Background**: World models are internal representations of external reality used for cognition, reasoning, and decision-making. In AI, they help agents anticipate events and shape behavior. MIRA applies this concept to multiplayer game environments, enabling AI to simulate complex interactions in real-time.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MIRA">MIRA</a></li>
<li><a href="https://en.wikipedia.org/wiki/World_models">World models</a></li>

</ul>
</details>

**Tags**: `#world-models`, `#reinforcement-learning`, `#game-ai`, `#multiplayer-ai`, `#rocket-league`

---

<a id="item-9"></a>
## [Mozilla CTO to Host AMA on Open Source AI Report](https://www.reddit.com/r/MachineLearning/comments/1upxdvc/raffi_krikorian_cto_mozilla_ama_on_the_state_of/) ⭐️ 8.0/10

Mozilla's CTO, Raffi Krikorian, announced an upcoming Ask Me Anything (AMA) session to discuss the company's inaugural State of Open Source AI report, which will cover various aspects of AI in production environments. This AMA and report are significant as they promise to offer valuable insights into the current state of the open source AI ecosystem, addressing critical topics like enterprise adoption, the impact of Chinese models, and developer trust, which are of high interest to the AI/ML community. The AMA will delve into specific topics including the hidden costs of 'free' models, the reality of enterprise adoption versus marketing, the 'China effect' from capable Chinese models, developer trust based on a survey of over 950 developers, and the concept of the 'agentic harness'.

reddit · r/MachineLearning · /u/raffikrikorian · Jul 7, 14:51

**Tags**: `#Open Source AI`, `#Mozilla`, `#AMA`, `#AI Ecosystem`, `#AI Industry`

---

<a id="item-10"></a>
## [Novel Defense Against Fine-Tuning Poisoning Using Trusted LoRA Adapters](https://www.reddit.com/r/MachineLearning/comments/1uq68li/what_if_a_model_could_only_learn_what_trusted/) ⭐️ 8.0/10

A research paper proposes constraining model updates to a subspace learned from trusted LoRA adapters, making certain malicious directions geometrically unreachable during fine-tuning. The approach was tested on 196 public LoRA adapters and showed strong results with attack success dropping sharply while preserving useful adaptation. This represents a significant advancement in model security by addressing fine-tuning poisoning attacks through architectural constraints rather than detection. The approach could protect models in scenarios like user-generated content fine-tuning or on-device personalization where traditional detection methods may fail. The defense mechanism works by restricting the model's update space to variations already represented by a trusted pool of adapters, rather than attempting to detect every possible poison or backdoor. The approach was tested against adaptive attacks specifically designed to bypass the defense, demonstrating its robustness.

reddit · r/MachineLearning · /u/Bright_Warning_8406 · Jul 7, 20:00

**Background**: Fine-tuning poisoning is a type of adversarial attack where malicious data is introduced during the fine-tuning process to embed hidden behaviors or backdoors in machine learning models. LoRA (Low-Rank Adaptation) is a parameter-efficient fine-tuning technique that adds small adapter modules to pre-trained models. Traditional defenses focus on detecting poisoned data or reducing its impact, but this approach takes a fundamentally different approach by constraining what the model can learn.

**Tags**: `#machine-learning`, `#model-security`, `#fine-tuning`, `#lora`, `#adversarial-attacks`

---

<a id="item-11"></a>
## [ML Conference Review Credit System Proposal](https://www.reddit.com/r/MachineLearning/comments/1upjftu/icml_position_track_want_better_ml_reviews_stop/) ⭐️ 8.0/10

A position paper proposes a credit system to incentivize better behavior in the ML conference review process, where community members earn points for positive contributions like reviewing papers and can redeem these points for conference perks. This proposal addresses a well-known problem in academic publishing by introducing an innovative incentive system that could transform how ML conferences operate and improve the quality of peer reviews. The proposed system includes earning points for reviewing papers (+1 point) and being outstanding (+3 points), with points redeemable for perks like free registration or requesting additional reviewers, and explores ideas like refundable submission fees.

reddit · r/MachineLearning · /u/choHZ · Jul 7, 03:32

**Background**: The ML research community has long struggled with issues in the conference review process, including lack of reviewer engagement, inconsistent quality of reviews, and insufficient accountability mechanisms. Current approaches often rely on voluntary participation without meaningful incentives, leading to suboptimal review quality and experience for both authors and reviewers.

**Tags**: `#machine-learning`, `#academic-publishing`, `#conference-review`, `#incentive-systems`, `#research-community`

---

<a id="item-12"></a>
## [Sensor-Validity Masking for Depth Modeling Achieves State-of-the-Art Results](https://www.reddit.com/r/MachineLearning/comments/1upqghy/masked_depth_modeling_with_sensorvalidity_masking/) ⭐️ 8.0/10

A research paper introduces a novel approach called sensor-validity masking for depth modeling, which outperforms traditional random dropout methods by using the sensor's own missing regions as the masking signal. The study also includes a controlled encoder-initialization experiment, comparing different pretrained backbones and finding that LingBot-Vision initialization generally performs best. This advancement significantly improves depth estimation accuracy, particularly for challenging scenarios like transparent or textureless surfaces, which are common failure points for RGB-D cameras. The findings provide valuable insights into encoder initialization strategies, contributing to the broader field of computer vision and embodied AI by offering a more robust and effective training paradigm. The paper reports achieving the best Root Mean Square Error (RMSE) on 7 out of 8 masked/sparse depth benchmarks and 6 out of 8 real camera configurations across multiple capture suites. Notably, performance on transparent-object datasets like ClearGrasp improved significantly, with RMSE roughly halving compared to a previous release. However, the model weights for Depth 2.0 are not publicly released, preventing independent verification of the reported results.

reddit · r/MachineLearning · /u/Ok-Line2658 · Jul 7, 09:54

**Background**: Masked depth modeling is a technique where parts of the input depth data are intentionally obscured (masked) during training, forcing the model to learn to predict the missing information. This is similar to masked language modeling in NLP. RGB-D cameras are sensors that capture both color (RGB) and depth information, providing a 3D understanding of a scene. RMSE (Root Mean Square Error) is a standard metric used to measure the average magnitude of the error between predicted and actual depth values, indicating the model's accuracy.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reddit.com/r/MachineLearning/comments/1upqghy/masked_depth_modeling_with_sensorvalidity_masking/">Masked depth modeling with sensor-validity masking: reports best RMSE on 7 of 8 masked/sparse depth benchmarks, plus a controlled encoder-init study[R] - Reddit</a></li>
<li><a href="https://en.wikipedia.org/wiki/RGB-D_camera">RGB-D camera</a></li>

</ul>
</details>

**Discussion**: A user in the comments asks whether sensor-validity masking would be as effective for other sensing modalities like lidar or thermal, questioning the generalizability of the proposed framing beyond RGB-D cameras.

**Tags**: `#depth-estimation`, `#computer-vision`, `#masked-modeling`, `#embodied-ai`, `#sensor-processing`

---

<a id="item-13"></a>
## [LingBot-Vision: masked boundary modeling for self-supervised pretraining](https://www.reddit.com/r/MachineLearning/comments/1up4cjh/lingbotvision_masked_boundary_modeling_for/) ⭐️ 8.0/10

LingBot-Vision introduces a novel masked boundary modeling approach for self-supervised vision pretraining that forces students to reconstruct boundary regions, achieving competitive results on NYUv2 and segmentation tasks with 0.296 NYUv2 linear-probe RMSE at 1.1B parameters compared to 0.309 for DINOv3-7B. This approach demonstrates technical innovation in how boundary structures are learned in self-supervised vision pretraining, potentially improving learning efficiency by focusing on hard-to-learn boundary regions. The method shows promise for advancing self-supervised learning techniques and has generated significant discussion in the machine learning community. The approach uses a teacher-student framework where the teacher predicts dense boundary fields online, with boundary targets derived from the teacher itself rather than external labels. Boundary fields are recast as per-pixel categorical distributions, and the method achieves strong results with significantly less training data (161M images vs DINOv3's larger dataset) while trailing on ImageNet classification tasks.

reddit · r/MachineLearning · /u/StillThese3747 · Jul 6, 17:37

**Background**: Self-supervised learning is a machine learning paradigm where models learn from data without explicit labels, often by predicting masked or corrupted parts of the input. Masked modeling, popularized by approaches like BERT in NLP and MAE in vision, involves masking random patches of input and training models to reconstruct them. Vision Transformers (ViT) are transformer architectures adapted for computer vision tasks, which have become increasingly popular for their ability to capture long-range dependencies in images.

**Discussion**: The community discussion highlights the approach's innovation but also notes limitations, including the need for further verification of results, potential sensitivity to probe protocols, and the absence of ablation studies against learned/hard-masking baselines. There's also discussion about whether the boundary forcing is complementary to existing techniques like Gram anchoring in DINOv3 rather than a replacement.

**Tags**: `#self-supervised-learning`, `#computer-vision`, `#masked-modeling`, `#vision-transformers`, `#pretraining`

---