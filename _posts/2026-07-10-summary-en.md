---
layout: default
title: "Horizon Summary: 2026-07-10 (EN)"
date: 2026-07-10
lang: en
---

> From 38 items, 8 important content pieces were selected

---

1. [EU Parliament greenlights Chat Control 1.0](#item-1) ⭐️ 8.0/10
2. [PostgreSQL rewritten in Rust passes all regression tests](#item-2) ⭐️ 8.0/10
3. [OpenAI launches GPT-5.6 model family with three sizes](#item-3) ⭐️ 8.0/10
4. [Rewriting Bun JavaScript Runtime from Zig to Rust](#item-4) ⭐️ 8.0/10
5. [OpenAI Introduces GPT-Live Voice Mode Upgrade](#item-5) ⭐️ 8.0/10
6. [Flock Cameras Screw Up, Swarm Innocent Man With Armed Police](#item-6) ⭐️ 8.0/10
7. [Publishers Prepare to Opt Out of Google Search](#item-7) ⭐️ 8.0/10
8. [OpenAI accused of faking data search inability in NYT copyright dispute](#item-8) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [EU Parliament greenlights Chat Control 1.0](https://www.patrick-breyer.de/en/eu-parliament-greenlights-chat-control-1-0-breyer-our-children-lose-out/) ⭐️ 8.0/10

The European Parliament approved Chat Control 1.0 legislation, which allows tech companies to scan private messages without warrants. This reverses a previous rejection from March, as the motion to reject failed to secure the required absolute majority of 361 votes, with 314 MEPs voting against, 276 in favor, and 17 abstentions. This legislation has significant implications for privacy and technology platforms, potentially creating a mass surveillance framework across major messaging services. It affects millions of users on platforms like Instagram, Discord, Gmail, and iCloud, raising concerns about the balance between child protection and fundamental privacy rights. The legislation applies to messaging and email services that are not end-to-end encrypted or where platforms can access message content server-side. The vote was strategically held on the day before summer break, with 113 members absent, and requires an absolute majority to reject rather than to pass, which critics call a 'parliamentary trick'.

hackernews · rapnie · Jul 9, 11:03 · [Discussion](https://news.ycombinator.com/item?id=48843923)

**Background**: Chat Control is EU legislation aimed at combating child sexual abuse material online. The first iteration, Chat Control 1.0, allows platforms to scan private communications for illegal content. Previous attempts to pass this legislation were rejected in March due to concerns about privacy violations and mass surveillance. The EU has been debating the balance between child protection and digital privacy for several years, with critics arguing that the technology for detecting unknown child pornography without high error rates doesn't exist, while supporters emphasize the need to protect children from abuse.

<details><summary>References</summary>
<ul>
<li><a href="https://www.patrick-breyer.de/en/eu-parliament-greenlights-chat-control-1-0-breyer-our-children-lose-out/">EU Parliament greenlights Chat Control 1.0 – Breyer: "Our children lose out"</a></li>
<li><a href="https://www.techtimes.com/articles/320010/20260709/eu-parliament-passes-chat-control-default-314-meps-couldnt-block-scanning-law.htm">EU Parliament Passes Chat Control by Default: 314 MEPs Couldn't Block Scanning Law</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community comments show strong opposition and concern about the parliamentary procedure. Many users criticize the timing of the vote (held before summer break with many members absent) and the requirement for an absolute majority to reject rather than pass. There are concerns about the EU becoming a 'totalitarian government' and the legitimacy of the EU project being jeopardized. Some point out that public posts and cloud storage could already be scanned without this law, while others emphasize the need for better child protection measures.

**Tags**: `#privacy`, `#legislation`, `#EU`, `#technology policy`, `#messaging platforms`

---

<a id="item-2"></a>
## [PostgreSQL rewritten in Rust passes all regression tests](https://github.com/malisper/pgrust) ⭐️ 8.0/10

A project has successfully rewritten PostgreSQL in Rust and is now passing 100% of PostgreSQL's regression tests. The author is also experimenting with using LLMs to build a better database system. This is significant because rewriting PostgreSQL in Rust could improve database performance and safety. The project represents a major technical achievement that has garnered strong community interest and validation. The project is called pgrust and is available on GitHub. The author mentions experimenting with LLMs for database system development, which is an innovative approach to building better database systems.

hackernews · SweetSoftPillow · Jul 9, 06:18 · [Discussion](https://news.ycombinator.com/item?id=48841676)

**Background**: PostgreSQL is a widely-used open-source relational database management system written in C. Rust is a systems programming language known for its performance, safety, and concurrency features. Regression tests are a comprehensive set of tests that ensure the database's SQL implementation works correctly across different versions and scenarios.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/malisper/pgrust">GitHub - malisper/pgrust: Postgres rewritten in Rust, now passing 100% of the Postgres regression tests · GitHub</a></li>
<li><a href="https://www.postgresql.org/docs/current/regress.html">PostgreSQL: Documentation: 18: Chapter 31. Regression Tests</a></li>
<li><a href="https://pgrust.com/">pgrust — postgres, rewritten in rust</a></li>

</ul>
</details>

**Discussion**: The community has mixed reactions. Some are impressed by the technical achievement, while others express concerns about the project's long-term viability due to being a single-person effort and the use of AI-generated code. There are suggestions for testing the Rust version against traditional PostgreSQL in production environments and questions about code review processes for AI-generated commits.

**Tags**: `#database`, `#rust`, `#postgresql`, `#systems-programming`, `#ai-development`

---

<a id="item-3"></a>
## [OpenAI launches GPT-5.6 model family with three sizes](https://simonwillison.net/2026/Jul/9/gpt-5-6/#atom-everything) ⭐️ 8.0/10

OpenAI announced the release of its GPT-5.6 model family with three sizes (Luna, Terra, Sol) featuring new pricing, technical specifications, and benchmark claims. The models are now generally available with pricing per 1M input/output tokens and include new API features like Programmatic Tool Calling and Multi-agent capabilities. This release is significant as it represents OpenAI's latest flagship model family, competing directly with Anthropic's Claude series. The new pricing structure and technical capabilities could impact the AI/ML landscape, potentially influencing how developers and enterprises choose between different large language models for their applications. The GPT-5.6 models feature a 1 million token context window and 128,000 maximum output tokens, with all having a February 16th 2026 knowledge cutoff. While OpenAI claims superior performance in 'Agents' Last Exam' benchmark, Claude Fable 5 outperformed GPT-5.6 Sol in SWE-Bench Pro (80% vs 64.6%), leading OpenAI to criticize the SWE-Bench Pro benchmark as having ~30% broken tasks.

rss · Simon Willison · Jul 9, 19:46

**Background**: GPT-5.6 is the latest in OpenAI's series of large language models (LLMs) following the GPT-3 and GPT-4 families. Large language models process text through tokens, which are essentially pieces of words or subwords. The context window refers to the maximum amount of text the model can consider at once when generating responses. Agentic performance refers to how well AI models can perform complex, multi-step tasks that require reasoning and tool usage, which is increasingly important for real-world applications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.6">GPT-5.6 - Wikipedia</a></li>
<li><a href="https://techcrunch.com/2026/07/09/openai-launches-its-new-family-of-models-with-gpt-5-6/">OpenAI launches its new family of models with GPT-5.6</a></li>
<li><a href="https://machinelearningmastery.com/agent-evaluation-how-to-test-and-measure-agentic-ai-performance/">Agent Evaluation: How to Test and Measure Agentic AI Performance - MachineLearningMastery.com</a></li>

</ul>
</details>

**Discussion**: The author of the article notes that despite OpenAI's claims, GPT-5.6 Sol hasn't seemed better than Fable at complex coding tasks in their early testing. There's also discussion about the new API features, with particular interest in Programmatic Tool Calling which could bridge the gap between Model Context Protocols (MCPs) and full terminal sessions.

**Tags**: `#AI`, `#OpenAI`, `#GPT`, `#LLM`, `#Machine Learning`

---

<a id="item-4"></a>
## [Rewriting Bun JavaScript Runtime from Zig to Rust](https://simonwillison.net/2026/Jul/8/rewriting-bun-in-rust/#atom-everything) ⭐️ 8.0/10

Jarred Sumner completed the rewrite of the Bun JavaScript runtime from Zig to Rust, a major technical migration that took 11 days with the help of AI coding agents. The new Rust implementation has been live in Claude Code since June 17th, 2026, with startup performance improving by 10% on Linux. This demonstrates how AI coding agents are changing the traditional wisdom about never rewriting large software projects from scratch. The successful migration showcases Rust's memory safety advantages over Zig for complex systems mixing garbage collection with manual memory management, potentially influencing future JavaScript runtime development. The rewrite cost an estimated $165,000 in API tokens and involved 5.9 billion uncached input tokens, 690 million output tokens, and 72 billion cached input token reads. The TypeScript test suite acted as a conformance suite, enabling automated porting and validation of the Rust implementation.

rss · Simon Willison · Jul 8, 23:57

**Background**: Bun is a popular JavaScript runtime that competes with Node.js and Deno. Zig is a systems programming language similar to C but with modern features, while Rust offers memory safety through its ownership system. The challenge arose from mixing garbage collection (common in JavaScript) with manual memory management (required in systems programming), leading to numerous bugs that Rust's compiler could catch as errors.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://en.wikipedia.org/wiki/List_of_JavaScript_engines">List of JavaScript engines - Wikipedia</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Memory_management">Memory management - JavaScript - MDN Web Docs</a></li>

</ul>
</details>

**Discussion**: The community discussion on Hacker News shows interest in the technical details and cost of the rewrite, with some questioning the practicality of such expensive AI-assisted development and others marveling at the engineering achievement.

**Tags**: `#JavaScript`, `#Rust`, `#Zig`, `#Runtime`, `#Systems Programming`

---

<a id="item-5"></a>
## [OpenAI Introduces GPT-Live Voice Mode Upgrade](https://simonwillison.net/2026/Jul/8/introducing-gptlive/#atom-everything) ⭐️ 8.0/10

OpenAI has introduced GPT-Live, a significant upgrade to ChatGPT's voice mode that can delegate complex tasks to GPT-5.5 in the background while maintaining conversation flow. The new model is full-duplex, allowing it to listen and respond continuously rather than waiting for turns to end. This upgrade significantly improves the usability and intelligence of ChatGPT's voice capabilities, making it more effective as a brainstorming partner. The ability to delegate complex tasks to more advanced models in the background while maintaining conversation flow represents a major step forward in voice AI technology. GPT-Live uses GPT-5.5 as its backend model for complex tasks and will be continuously updated with new frontier models as they're released. The previous voice mode was based on a GPT-4o era model with a 2024 knowledge cutoff, which limited its usefulness. During preview, some users reported the model interrupting with inappropriate laughter, though OpenAI appears to have addressed this issue.

rss · Simon Willison · Jul 8, 23:20

**Background**: GPT-Live represents a new generation of voice models designed to make conversations with AI feel more natural and intelligent. The full-duplex capability allows for continuous listening and responding, unlike previous models that required clearly defined turn-taking. GPT-5.5 is OpenAI's frontier model designed for complex professional workloads, building on previous versions with stronger reasoning and improved token efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://www.technology.org/2026/07/09/openai-gpt-live-full-duplex-voice-models/">OpenAI Launches GPT-Live Voice AI Models - Technology Org</a></li>
<li><a href="https://openrouter.ai/openai/gpt-5.5">GPT - 5 . 5 - API Pricing & Benchmarks | OpenRouter</a></li>
<li><a href="https://deploymentsafety.openai.com/gpt-live/gpt-live.pdf">PDF GPT-Live System Card</a></li>

</ul>
</details>

**Discussion**: Based on the Hacker News discussion, users are generally impressed with the upgrade but note some quirks during the preview period, such as the model interrupting with inappropriate laughter. The community appreciates the continuous improvement and the ability to maintain conversation flow while handling complex tasks.

**Tags**: `#AI`, `#OpenAI`, `#ChatGPT`, `#voice-assistant`, `#model-upgrade`

---

<a id="item-6"></a>
## [Flock Cameras Screw Up, Swarm Innocent Man With Armed Police](https://www.reddit.com/r/technology/comments/1us2ghn/flock_cameras_screw_up_swarm_innocent_man_with/) ⭐️ 8.0/10

A Reddit post reports that an error by Flock surveillance cameras led to an innocent person being surrounded by armed police, highlighting a serious incident involving surveillance technology. This incident raises significant concerns about the reliability and accuracy of automated surveillance systems, potentially leading to wrongful accusations and privacy violations, and fuels ongoing debates about the ethics of widespread surveillance technology deployment. A 2021 study by IPVM found a 10% error rate in Flock's Falcon camera output, which the company disputed. Additionally, a data breach and public opposition in cities like Denver have highlighted privacy and civil liberties concerns associated with Flock's technology.

reddit · r/technology · /u/Plastic_Ninja_9014 · Jul 9, 20:43

**Background**: Flock Safety is an American company that manufactures and operates security hardware and software, including automated license plate recognition (ALPR) and video surveillance systems. Their AI-powered cameras are designed to provide instant alerts and 24/7 security coverage, often deployed by law enforcement and municipalities for public safety and crime prevention. However, the accuracy and potential for misuse of such technology have been subjects of debate.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.flocksafety.com/products/video-cameras">AI Video Cameras | Smart Security with Instant Alerts | Flock</a></li>
<li><a href="https://trafficvision.live/blog/flock-cameras">Flock Cameras : What They Are & Can You Watch... | TrafficVision.Live</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#surveillance`, `#security-cameras`, `#technology-ethics`, `#police-technology`

---

<a id="item-7"></a>
## [Publishers Prepare to Opt Out of Google Search](https://www.reddit.com/r/technology/comments/1us199b/once_unimaginable_publishers_are_preparing_to_opt/) ⭐️ 8.0/10

Publishers are reportedly preparing to opt out of Google Search, which would be a significant shift in how content is discovered online. This move comes as Google introduces new AI-powered search features that use publisher content for training and generative AI experiences. This could fundamentally alter the search engine landscape and content discovery ecosystem. If publishers opt out, it may reduce the quality and comprehensiveness of Google's AI-generated search results, potentially driving users to alternative search engines or directly to publisher websites. The opt-out mechanism allows publishers to remove their content from AI Overviews, AI Mode, and AI Overviews in Discover while maintaining their regular organic search rankings. Google has stated that opting out won't result in penalties or ranking changes for publishers.

reddit · r/technology · /u/Steap-Edit · Jul 9, 19:59

**Background**: Google has been increasingly integrating AI into its search results, creating AI Overviews that synthesize information from multiple sources. This has raised concerns among publishers about how their content is used without proper compensation or control. The new opt-out feature gives publishers more control over how their content appears in these AI-powered experiences.

<details><summary>References</summary>
<ul>
<li><a href="https://cloversreport.com/guides/how-to-opt-out-of-google-searchs-new-ai-data-training-feature">How to opt out of Google Search ’s new AI data... — Clovers Report</a></li>
<li><a href="https://digiday.com/media/googles-forced-ai-opt-out-what-changes-and-what-doesnt-for-publishers/">Google ’s forced AI opt out : what changes — and what... - Digiday</a></li>
<li><a href="https://kalinga.ai/opt-out-of-ai-search-guide/">Opt Out of AI Search : Powerful Publisher Guide 2026</a></li>

</ul>
</details>

**Tags**: `#Google`, `#Search Engines`, `#Publishing`, `#Web Technology`, `#Industry News`

---

<a id="item-8"></a>
## [OpenAI accused of faking data search inability in NYT copyright dispute](https://www.reddit.com/r/technology/comments/1urzuf4/openai_faked_inability_to_search_training_data/) ⭐️ 8.0/10

According to a news report, OpenAI allegedly faked its inability to search training data and hid billions of logs during a copyright dispute with the New York Times, potentially facing sanctions as a result. This could significantly impact AI regulation, transparency requirements, and legal precedents in AI copyright cases, raising important questions about AI ethics and accountability. The allegations suggest OpenAI may have deliberately misrepresented its technical capabilities during legal proceedings, which could have serious legal and reputational consequences for the company.

reddit · r/technology · /u/swingadmin · Jul 9, 19:08

**Background**: AI training data consists of examples fed into AI models to help them learn patterns and relationships. Large language models like ChatGPT are trained on vast amounts of internet data, often including copyrighted material. ChatGPT logs typically record user interactions and can be accessed by authorized OpenAI employees for specific purposes like litigation or investigations. The use of copyrighted material in AI training has become a major legal and ethical issue, with several lawsuits challenging whether creating digital copies of copyrighted works for training AI systems constitutes infringement.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/training-data">What is Training Data? | IBM</a></li>
<li><a href="https://www.rws.com/artificial-intelligence/train-ai-data-services/blog/how-ai-is-trained-the-critical-role-of-ai-training-data/">How AI is trained: the critical role of training data – RWS</a></li>
<li><a href="https://www.copyright.gov/ai/">Copyright and Artificial Intelligence | U.S. Copyright Office</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#Copyright law`, `#OpenAI`, `#Legal disputes`, `#AI regulation`

---