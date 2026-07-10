---
layout: default
title: "Horizon Summary: 2026-07-10 (ZH)"
date: 2026-07-10
lang: zh
---

> 从 38 条内容中筛选出 8 条重要资讯。

---

1. [欧盟议会通过聊天控制 1.0 法案](#item-1) ⭐️ 8.0/10
2. [PostgreSQL 用 Rust 重写并通过所有回归测试](#item-2) ⭐️ 8.0/10
3. [OpenAI 发布 GPT-5.6 模型家族，包含三种尺寸](#item-3) ⭐️ 8.0/10
4. [将 Bun JavaScript 运行时从 Zig 重写为 Rust](#item-4) ⭐️ 8.0/10
5. [OpenAI 推出 GPT-Live 语音模式升级](#item-5) ⭐️ 8.0/10
6. [Flock 摄像头出错，无辜男子遭武装警察包围](#item-6) ⭐️ 8.0/10
7. [出版商准备退出谷歌搜索](#item-7) ⭐️ 8.0/10
8. [OpenAI 被指在纽约时报版权纠纷中伪造数据搜索能力](#item-8) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [欧盟议会通过聊天控制 1.0 法案](https://www.patrick-breyer.de/en/eu-parliament-greenlights-chat-control-1-0-breyer-our-children-lose-out/) ⭐️ 8.0/10

欧洲议会通过了聊天控制 1.0 法案，允许科技公司无需搜查令即可扫描私人消息。这推翻了三月份的先前拒绝，因为拒绝动议未能获得 361 票的绝对多数，314 名欧洲议会议员投票反对，276 票赞成，17 票弃权。 这项立法对隐私和技术平台有重大影响，可能在整个主要消息服务中创建大规模监控框架。它影响到 Instagram、Discord、Gmail 和 iCloud 等平台上的数百万用户，引发了关于儿童保护与基本隐私权之间平衡的担忧。 该立法适用于非端到端加密或平台可以访问消息内容的服务器端消息和电子邮件服务。投票被策略性地安排在暑假前的一天进行，有 113 名成员缺席，并且需要绝对多数才能拒绝而不是通过，批评者称之为'议会伎俩'。

hackernews · rapnie · 7月9日 11:03 · [社区讨论](https://news.ycombinator.com/item?id=48843923)

**背景**: 聊天控制是欧盟旨在打击在线儿童性虐待材料的立法。第一版聊天控制 1.0 允许平台扫描私人通信中的非法内容。此前的通过尝试因隐私侵犯和大规模监控的担忧而在三月被拒绝。欧盟多年来一直在讨论儿童保护与数字隐私之间的平衡，批评者认为，没有高错误率检测未知儿童色情材料的技术不存在，而支持者则强调保护儿童免受虐待的必要性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.patrick-breyer.de/en/eu-parliament-greenlights-chat-control-1-0-breyer-our-children-lose-out/">EU Parliament greenlights Chat Control 1.0 – Breyer: "Our children lose out"</a></li>
<li><a href="https://www.techtimes.com/articles/320010/20260709/eu-parliament-passes-chat-control-default-314-meps-couldnt-block-scanning-law.htm">EU Parliament Passes Chat Control by Default: 314 MEPs Couldn't Block Scanning Law</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区评论显示对议会程序强烈反对和担忧。许多用户批评投票时机（在暑假前举行，许多成员缺席）以及需要绝对多数才能拒绝而不是通过。有人担心欧盟成为'极权政府'，欧盟项目的合法性受到损害。一些人指出，公共帖子和云存储已经可以在没有这项法律的情况下被扫描，而另一些人则强调需要更好的儿童保护措施。

**标签**: `#privacy`, `#legislation`, `#EU`, `#technology policy`, `#messaging platforms`

---

<a id="item-2"></a>
## [PostgreSQL 用 Rust 重写并通过所有回归测试](https://github.com/malisper/pgrust) ⭐️ 8.0/10

一个项目已成功将 PostgreSQL 用 Rust 重写，并通过了 PostgreSQL 的所有回归测试。作者还在尝试使用 LLM 构建更好的数据库系统。 这很重要，因为用 Rust 重写 PostgreSQL 可能会提高数据库的性能和安全性。该项目代表了重大的技术成就，并获得了社区的高度关注和认可。 该项目名为 pgrust，可在 GitHub 上找到。作者提到正在尝试使用 LLM 进行数据库系统开发，这是一种构建更好数据库系统的创新方法。

hackernews · SweetSoftPillow · 7月9日 06:18 · [社区讨论](https://news.ycombinator.com/item?id=48841676)

**背景**: PostgreSQL 是一个广泛使用的开源关系型数据库管理系统，用 C 语言编写。Rust 是一种系统编程语言，以其性能、安全性和并发特性而闻名。回归测试是一套全面的测试，确保数据库的 SQL 实现在不同版本和场景下都能正常工作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/malisper/pgrust">GitHub - malisper/pgrust: Postgres rewritten in Rust, now passing 100% of the Postgres regression tests · GitHub</a></li>
<li><a href="https://www.postgresql.org/docs/current/regress.html">PostgreSQL: Documentation: 18: Chapter 31. Regression Tests</a></li>
<li><a href="https://pgrust.com/">pgrust — postgres, rewritten in rust</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一。一些人对其技术成就印象深刻，而另一些人则对项目的长期可行性表示担忧，因为它是一个人的项目，并且使用了 AI 生成的代码。有人建议在生产环境中将 Rust 版本与传统 PostgreSQL 进行对比测试，还有人质疑 AI 生成提交的代码审查过程。

**标签**: `#database`, `#rust`, `#postgresql`, `#systems-programming`, `#ai-development`

---

<a id="item-3"></a>
## [OpenAI 发布 GPT-5.6 模型家族，包含三种尺寸](https://simonwillison.net/2026/Jul/9/gpt-5-6/#atom-everything) ⭐️ 8.0/10

OpenAI 宣布发布其 GPT-5.6 模型家族，包含三种尺寸（Luna、Terra、Sol），具有新的定价、技术规格和基准测试声明。这些模型现已全面上市，按每 100 万输入/输出令牌定价，并包含新的 API 功能，如程序化工具调用和多智能体能力。 这一发布具有重要意义，因为它代表了 OpenAI 最新的旗舰模型家族，直接与 Anthropic 的 Claude 系列竞争。新的定价结构和技术能力可能影响 AI/ML 领域，可能影响开发者和企业如何在不同的大型语言模型之间为他们的应用程序做出选择。 GPT-5.6 模型具有 100 万令牌上下文窗口和 128,000 最大输出令牌，所有模型都有 2026 年 2 月 16 日的知识截止日期。虽然 OpenAI 声称在'Agents' Last Exam'基准测试中表现更优，但 Claude Fable 5 在 SWE-Bench Pro 中表现优于 GPT-5.6 Sol（80%对 64.6%），导致 OpenAI 批评 SWE-Bench Pro 基准测试有约 30%的任务存在缺陷。

rss · Simon Willison · 7月9日 19:46

**背景**: GPT-5.6 是 OpenAI 系列大型语言模型（LLM）的最新产品，继 GPT-3 和 GPT-4 家族之后。大型语言模型通过令牌处理文本，这些令牌本质上是单词或子词的片段。上下文窗口指的是模型在生成响应时可以同时考虑的最大文本量。智能体性能指的是 AI 模型在需要推理和工具使用的复杂多步骤任务中的表现能力，这对于实际应用越来越重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.6">GPT-5.6 - Wikipedia</a></li>
<li><a href="https://techcrunch.com/2026/07/09/openai-launches-its-new-family-of-models-with-gpt-5-6/">OpenAI launches its new family of models with GPT-5.6</a></li>
<li><a href="https://machinelearningmastery.com/agent-evaluation-how-to-test-and-measure-agentic-ai-performance/">Agent Evaluation: How to Test and Measure Agentic AI Performance - MachineLearningMastery.com</a></li>

</ul>
</details>

**社区讨论**: 文章作者指出，尽管 OpenAI 声称 GPT-5.6 Sol 在复杂编码任务上表现更优，但在他们的早期测试中，它似乎并不比 Fable 更好。还有关于新 API 功能的讨论，特别是程序化工具调用，这可能弥合模型上下文协议（MCP）和完整终端会话之间的差距。

**标签**: `#AI`, `#OpenAI`, `#GPT`, `#LLM`, `#Machine Learning`

---

<a id="item-4"></a>
## [将 Bun JavaScript 运行时从 Zig 重写为 Rust](https://simonwillison.net/2026/Jul/8/rewriting-bun-in-rust/#atom-everything) ⭐️ 8.0/10

Jarred Sumner 完成了将 Bun JavaScript 运行时从 Zig 重写为 Rust 的重大技术迁移，在 AI 编码助手的帮助下仅用 11 天完成。新的 Rust 实现自 2026 年 6 月 17 日起已在 Claude Code 中上线，在 Linux 上的启动性能提升了 10%。 这展示了 AI 编码助手如何改变关于从不从头重写大型软件项目的传统观念。成功的迁移展示了 Rust 在内存安全方面的优势，可能影响未来 JavaScript 运行时的开发。 重写估计花费了 16.5 万美元的 API 令牌，涉及 59 亿个未缓存输入令牌、6.9 亿个输出令牌和 720 亿个缓存输入令牌读取。TypeScript 测试套件作为一致性测试套件，实现了 Rust 实现的自动化移植和验证。

rss · Simon Willison · 7月8日 23:57

**背景**: Bun 是一个流行的 JavaScript 运行时，与 Node.js 和 Deno 竞争。Zig 是一种类似于 C 但具有现代功能的系统编程语言，而 Rust 通过其所有权系统提供内存安全。挑战源于将垃圾回收（JavaScript 中常见）与手动内存管理（系统编程中需要）混合，导致许多 Rust 编译器可以捕获为错误的错误。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://en.wikipedia.org/wiki/List_of_JavaScript_engines">List of JavaScript engines - Wikipedia</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Memory_management">Memory management - JavaScript - MDN Web Docs</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的社区讨论显示了对重写技术细节和成本的兴趣，一些人质疑这种昂贵 AI 辅助开发的实用性，而另一些人则对工程成就感到惊叹。

**标签**: `#JavaScript`, `#Rust`, `#Zig`, `#Runtime`, `#Systems Programming`

---

<a id="item-5"></a>
## [OpenAI 推出 GPT-Live 语音模式升级](https://simonwillison.net/2026/Jul/8/introducing-gptlive/#atom-everything) ⭐️ 8.0/10

OpenAI 推出了 GPT-Live，这是 ChatGPT 语音模式的重要升级，能够在后台将复杂任务委托给 GPT-5.5，同时保持对话流畅。新模型是全双工的，可以连续收听和响应，而不是等待轮次结束。 此次升级显著提升了 ChatGPT 语音功能的可用性和智能性，使其作为头脑风暴伙伴更加有效。能够在后台将复杂任务委托给更高级模型的同时保持对话流畅，代表了语音 AI 技术的重要进步。 GPT-Live 使用 GPT-5.5 作为复杂任务的 backend 模型，并将随着新前沿模型的发布持续更新。之前的语音模式基于 GPT-4o 时代模型，知识截止到 2024 年，这限制了其有用性。在预览期间，一些用户报告模型会以不恰当的笑声打断对话，尽管 OpenAI 似乎已经解决了这个问题。

rss · Simon Willison · 7月8日 23:20

**背景**: GPT-Live 代表了新一代语音模型，旨在使与 AI 的对话感觉更自然、更智能。全双工能力允许连续收听和响应，不像之前的模型需要明确的轮次。GPT-5.5 是 OpenAI 的前沿模型，专为复杂的专业工作负载设计，在先前版本的基础上增强了推理能力和令牌效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.technology.org/2026/07/09/openai-gpt-live-full-duplex-voice-models/">OpenAI Launches GPT-Live Voice AI Models - Technology Org</a></li>
<li><a href="https://openrouter.ai/openai/gpt-5.5">GPT - 5 . 5 - API Pricing & Benchmarks | OpenRouter</a></li>
<li><a href="https://deploymentsafety.openai.com/gpt-live/gpt-live.pdf">PDF GPT-Live System Card</a></li>

</ul>
</details>

**社区讨论**: 根据 Hacker News 的讨论，用户普遍对升级印象深刻，但指出预览期间存在一些怪癖，例如模型以不恰当的笑声打断对话。社区欣赏持续改进的能力以及在处理复杂任务时保持对话流畅的功能。

**标签**: `#AI`, `#OpenAI`, `#ChatGPT`, `#voice-assistant`, `#model-upgrade`

---

<a id="item-6"></a>
## [Flock 摄像头出错，无辜男子遭武装警察包围](https://www.reddit.com/r/technology/comments/1us2ghn/flock_cameras_screw_up_swarm_innocent_man_with/) ⭐️ 8.0/10

Reddit 上的一篇帖子报告称，Flock 监控摄像头的一次错误导致一名无辜人士被武装警察包围，突显了一起涉及监控技术的严重事件。 这一事件引发了人们对自动化监控系统的可靠性和准确性的严重担忧，可能导致错误指控和隐私侵犯，并加剧了关于广泛部署监控技术伦理的持续辩论。 2021 年 IPVM 的一项研究发现 Flock 的 Falcon 摄像头输出存在 10%的错误率，但该公司对此提出异议。此外，数据泄露事件以及在丹佛等城市引发的公众反对，突显了与 Flock 技术相关的隐私和公民自由担忧。

reddit · r/technology · /u/Plastic_Ninja_9014 · 7月9日 20:43

**背景**: Flock Safety 是一家美国公司，生产和运营安全硬件和软件，包括自动车牌识别（ALPR）和视频监控系统。他们的 AI 摄像头旨在提供即时警报和 24/7 安全覆盖，通常由执法部门和市政府部署用于公共安全和犯罪预防。然而，此类技术的准确性和潜在滥用一直是争论的焦点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.flocksafety.com/products/video-cameras">AI Video Cameras | Smart Security with Instant Alerts | Flock</a></li>
<li><a href="https://trafficvision.live/blog/flock-cameras">Flock Cameras : What They Are & Can You Watch... | TrafficVision.Live</a></li>

</ul>
</details>

**标签**: `#privacy`, `#surveillance`, `#security-cameras`, `#technology-ethics`, `#police-technology`

---

<a id="item-7"></a>
## [出版商准备退出谷歌搜索](https://www.reddit.com/r/technology/comments/1us199b/once_unimaginable_publishers_are_preparing_to_opt/) ⭐️ 8.0/10

出版商据报道正准备退出谷歌搜索，这将是内容发现方式的重要转变。这一举动发生在谷歌推出使用出版商内容进行训练和生成式 AI 体验的新 AI 搜索功能之际。 这可能从根本上改变搜索引擎格局和内容发现生态系统。如果出版商退出，可能会降低谷歌 AI 生成搜索结果的质量和全面性，可能将用户推向其他搜索引擎或直接导向出版商网站。 退出机制允许出版商将其内容从 AI 概览、AI 模式和发现中的 AI 概览中移除，同时保持其常规的有机搜索排名。谷歌已表示，退出不会导致出版商受到惩罚或排名变化。

reddit · r/technology · /u/Steap-Edit · 7月9日 19:59

**背景**: 谷歌一直在将其搜索结果中越来越多地整合 AI，创建从多个来源综合信息的 AI 概览。这引发了出版商关于其内容如何被使用而没有适当补偿或控制的担忧。新的退出功能让出版商对其内容在这些 AI 体验中的呈现方式有了更多控制权。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cloversreport.com/guides/how-to-opt-out-of-google-searchs-new-ai-data-training-feature">How to opt out of Google Search ’s new AI data... — Clovers Report</a></li>
<li><a href="https://digiday.com/media/googles-forced-ai-opt-out-what-changes-and-what-doesnt-for-publishers/">Google ’s forced AI opt out : what changes — and what... - Digiday</a></li>
<li><a href="https://kalinga.ai/opt-out-of-ai-search-guide/">Opt Out of AI Search : Powerful Publisher Guide 2026</a></li>

</ul>
</details>

**标签**: `#Google`, `#Search Engines`, `#Publishing`, `#Web Technology`, `#Industry News`

---

<a id="item-8"></a>
## [OpenAI 被指在纽约时报版权纠纷中伪造数据搜索能力](https://www.reddit.com/r/technology/comments/1urzuf4/openai_faked_inability_to_search_training_data/) ⭐️ 8.0/10

据报道，OpenAI 在纽约时报的版权纠纷中涉嫌伪造其无法搜索训练数据的能力，并隐藏了数十亿条日志，可能因此面临制裁。 这可能对 AI 监管、透明度要求和 AI 版权案件中的法律先例产生重大影响，引发关于 AI 伦理和问责制的重要问题。 这些指控表明 OpenAI 可能在法律程序中故意歪曲其技术能力，这可能给公司带来严重的法律和声誉后果。

reddit · r/technology · /u/swingadmin · 7月9日 19:08

**背景**: AI 训练数据是输入到 AI 模型中以帮助其学习模式和关系的示例。像 ChatGPT 这样的大型语言模型是在大量互联网数据上训练的，通常包括受版权保护的材料。ChatGPT 日志通常记录用户交互，并可以被授权的 OpenAI 员工用于特定目的，如诉讼或调查。在 AI 训练中使用受版权保护的材料已成为一个主要的法律和伦理问题，已有几起诉讼质疑为训练 AI 系统创建受版权作品的数字副本是否构成侵权。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/training-data">What is Training Data? | IBM</a></li>
<li><a href="https://www.rws.com/artificial-intelligence/train-ai-data-services/blog/how-ai-is-trained-the-critical-role-of-ai-training-data/">How AI is trained: the critical role of training data – RWS</a></li>
<li><a href="https://www.copyright.gov/ai/">Copyright and Artificial Intelligence | U.S. Copyright Office</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#Copyright law`, `#OpenAI`, `#Legal disputes`, `#AI regulation`

---