---
layout: default
title: "Horizon Summary: 2026-06-30 (EN)"
date: 2026-06-30
lang: en
---

> From 29 items, 5 important content pieces were selected

---

1. [Google's AI Peer Reviewer at ICML/STOC](#item-1) ⭐️ 9.0/10
2. [European Digital ID Wallets Depend on Google and Apple](#item-2) ⭐️ 8.0/10
3. [Memory Safe Context Switching](#item-3) ⭐️ 8.0/10
4. [11 Million Papers Mapped by Similarity](#item-4) ⭐️ 8.0/10
5. [EML Trees Proven Universal Approximators](#item-5) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Google's AI Peer Reviewer at ICML/STOC](https://www.reddit.com/r/MachineLearning/comments/1uio9rb/googles_agentic_peerreviewer_handled_10k_papers/) ⭐️ 9.0/10

Google deployed an agentic AI peer-reviewer system that successfully reviewed approximately 10,000 research papers at top computer science conferences ICML and STOC with a 30-minute turnaround time. This establishes a significant precedent for AI-automated scientific review at scale, potentially revolutionizing academic publishing by dramatically increasing the efficiency and accuracy of the peer review process. The system demonstrated 34% more mathematical error detection compared to zero-shot prompting, and Google has now published a formal research paper documenting these results.

reddit · r/MachineLearning · /u/Justgototheeffinmoon · Jun 29, 10:05

**Background**: ICML (International Conference on Machine Learning) is one of the fastest growing artificial intelligence conferences globally, while STOC (ACM Symposium on Theory of Computing) is the flagship conference for computational theory, having been held annually since 1969. Agentic AI systems represent an advancement in AI capabilities that allows them to perform complex tasks with more autonomy, while zero-shot prompting is a technique where AI models perform tasks without specific examples or training for those particular tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://icml.cc/">International Conference on Machine Learning - ICML 2026</a></li>
<li><a href="https://acm-stoc.org/">ACM STOC Conference: The ACM Symposium on Theory of Computing</a></li>

</ul>
</details>

**Tags**: `#AI peer review`, `#automated scientific evaluation`, `#Google research`, `#machine learning`, `#academic publishing`

---

<a id="item-2"></a>
## [European Digital ID Wallets Depend on Google and Apple](https://waag.org/en/article/european-digital-id-wallets-are-gift-google-and-apple/) ⭐️ 8.0/10

European digital ID wallets are dependent on Google and Apple safety services, raising concerns about digital sovereignty and autonomy. This dependency undermines Europe's digital sovereignty goals and creates reliance on US tech giants, potentially limiting European control over its digital infrastructure. The EU reference implementation for wallets strictly requires Google Play Services, and even Android's hardware attestation API is seen as an attack on digital autonomy by some experts.

hackernews · donohoe · Jun 30, 10:36 · [Discussion](https://news.ycombinator.com/item?id=48730729)

**Background**: Digital ID wallets are secure applications that store, manage, and share verifiable credentials linked to an individual. Digital sovereignty refers to a nation's ability to control its own digital infrastructure, data, and technologies without undue influence from foreign entities. Many European governments have been pushing for digital sovereignty to reduce dependency on US tech companies.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Digital_wallet">Digital wallet</a></li>
<li><a href="https://en.wikipedia.org/wiki/Digital_sovereignty">Digital sovereignty - Wikipedia Digital sovereignty at the UN: Inside the global push to ... Digital sovereignty – the clash between wanting to take back ... Digital sovereignty | Microsoft Learn Digital Sovereignty: A Descriptive Analysis and a Critical ... Digital Sovereignty Reconsidered: From Location-Based ...</a></li>

</ul>
</details>

**Discussion**: Community members express concerns about the irony of European digital ID relying on US companies, with some calling it 'performative nonsense' regarding European sovereignty discussions. Others warn that regulations may create monopolies, and there are concerns about government overreach through remote attestation of users' entire platforms.

**Tags**: `#digital-identity`, `#europe`, `#google`, `#apple`, `#digital-sovereignty`

---

<a id="item-3"></a>
## [Memory Safe Context Switching](https://fil-c.org/context_switches) ⭐️ 8.0/10

Fil-C has introduced memory-safe implementations of setjmp/longjmp and ucontext APIs, addressing critical safety issues with traditional context switching methods. This advancement is crucial for systems programming where memory safety is paramount, preventing dangerous stack frame overwrites and register state mismatches that could lead to security vulnerabilities. The implementation supports setjmp, longjmp, setcontext, getcontext, makecontext, and swapcontext APIs with memory safety guarantees, and is available in Fil-C release 0.680.

hackernews · modeless · Jun 30, 00:38 · [Discussion](https://news.ycombinator.com/item?id=48727177)

**Background**: Context switching is a fundamental concept in operating systems and concurrent programming, allowing control to transfer between different execution contexts. Traditional setjmp/longjmp implementations have memory safety issues because they can become invalid if the calling function returns before longjmp is called. The ucontext API provides an alternative but has been historically heavy in terms of performance.

<details><summary>References</summary>
<ul>
<li><a href="https://fil-c.org/context_switches">Memory Safe Context Switching - fil-c.org</a></li>
<li><a href="https://en.wikipedia.org/wiki/Setjmp/longjmp">Setjmp/longjmp</a></li>
<li><a href="https://news.ycombinator.com/item?id=48727177">Memory Safe Context Switching (longjmp, setjmp) in Fil-C ...</a></li>

</ul>
</details>

**Discussion**: The discussion includes expert insights on implementation details, with matheusmoreira highlighting the safety issues with setjmp, nanolith discussing Boost's fiber implementation alternatives, and infogulch proposing a solution using per-stack base pointers.

**Tags**: `#systems`, `#memory-safety`, `#context-switching`, `#low-level-programming`, `#fibers`

---

<a id="item-4"></a>
## [11 Million Papers Mapped by Similarity](https://www.reddit.com/r/MachineLearning/comments/1ujn3u5/a_map_of_the_latest_11_million_papers_split_by/) ⭐️ 8.0/10

A new visualization tool maps 11 million research papers by semantic similarity and time using SPECTER 2 and UMAP, allowing researchers to navigate scientific literature more effectively. This tool addresses the challenge of keeping up with the vast amount of scientific literature published daily, helping researchers identify trends, discover relevant papers, and understand the evolution of research fields over time. The tool processes papers from OpenAlex and ArXiv, uses SPECTER 2 to encode titles and abstracts, applies UMAP for dimensionality reduction, and includes time-sliced visualization with daily updates and analytics capabilities.

reddit · r/MachineLearning · /u/icannotchangethename · Jun 30, 11:55

**Background**: SPECTER 2 is a specialized NLP model designed for scientific literature that creates embeddings based on paper titles and abstracts. UMAP (Uniform Manifold Approximation and Projection) is a dimensionality reduction technique that preserves the topological structure of high-dimensional data when projecting it to lower dimensions. Voronoi diagrams are used to partition space into regions based on distance to specific points, which in this case helps create meaningful boundaries around clusters of similar papers.

<details><summary>References</summary>
<ul>
<li><a href="https://umap-learn.readthedocs.io/en/latest/">UMAP: Uniform Manifold Approximation and Projection for ...</a></li>
<li><a href="https://www.geeksforgeeks.org/machine-learning/umap-uniform-manifold-approximation-and-projection/">UMAP: Uniform Manifold Approximation and Projection</a></li>
<li><a href="https://www.pythontutorials.net/blog/voronoi-compute-exact-boundaries-of-every-region/">How to Compute Exact Boundaries of Voronoi ... — pythontutorials.net</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion shows moderate engagement with several thoughtful comments about potential applications and limitations, indicating community interest in this approach to literature exploration.

**Tags**: `#scientific-literature`, `#nlp`, `#data-visualization`, `#research-tools`, `#specter`

---

<a id="item-5"></a>
## [EML Trees Proven Universal Approximators](https://www.reddit.com/r/MachineLearning/comments/1uipl1t/eml_trees_are_universal_approximators_r/) ⭐️ 8.0/10

A new paper proves that EML(-type) trees can represent any function in reasonably general spaces through composition, establishing a universal approximation theorem for this novel function representation method. This theoretical advancement provides mathematical justification for using EML trees in machine learning, potentially offering a more structured approach to function approximation than traditional neural networks while maintaining their universal approximation capabilities. The proof includes explicit constructions of EML(-type) representations for binary operations, polynomials, hyperbolic tangent, and approximate partitions of unity, which serve as 'LEGO' blocks for building more complex functions. The paper addresses technical challenges like the ill-definedness of the natural logarithm for nonpositive inputs through sign-based decompositions and affine maps.

reddit · r/MachineLearning · /u/JoeGermany · Jun 29, 11:16

**Background**: The universal approximation theorem is a foundational result in machine learning theory, stating that neural networks with certain structures can approximate any continuous function to any desired accuracy. EML (Elementary Mathematical Library) functions recently gained attention as a 'cool trick' that can represent all elementary functions through composition. Sobolev spaces are mathematical function spaces that include functions with certain differentiability properties, important for many applications in partial differential equations and functional analysis.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Universal_approximation_theorem">Universal approximation theorem</a></li>
<li><a href="https://en.wikipedia.org/wiki/Sobolev_space">Sobolev space</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion shows moderate technical engagement with some questions and clarifications from the author about the theoretical contributions and practical implications of the work.

**Tags**: `#universal approximation`, `#EML trees`, `#function approximation`, `#machine learning theory`, `#mathematical foundations`

---