---
layout: default
title: "Horizon Summary: 2026-07-19 (EN)"
date: 2026-07-19
lang: en
---

> From 31 items, 2 important content pieces were selected

---

1. [Transcribe.cpp: New Speech-to-Text Library with Local Inference](#item-1) ⭐️ 8.0/10
2. [EU AI Act OpenRAG Dataset Released with Structured Chunks and BGE-M3 Embeddings](#item-2) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Transcribe.cpp: New Speech-to-Text Library with Local Inference](https://workshop.cjpais.com/projects/transcribe-cpp) ⭐️ 8.0/10

Transcribe.cpp, a new open-source C/C++ speech-to-text inference library, has been announced. It enables local inference with portable, GPU-accelerated support for multiple STT models and offers bindings in multiple languages. This project is significant because it addresses the growing need for privacy-preserving and offline speech recognition. By enabling local inference, it allows users to run speech recognition on their own hardware without sending data to the cloud, which is increasingly important for applications requiring data security and offline functionality. Transcribe.cpp is based on the ggml framework and supports over 16 model families. It was developed through Mozilla.ai's Builders in Residence program and aims to make adding fast, local transcription easier for developers.

hackernews · sebjones · Jul 19, 00:38 · [Discussion](https://news.ycombinator.com/item?id=48963879)

**Background**: Speech-to-text (STT) technology converts spoken language into written text. Local inference in AI refers to running AI models directly on a user's device or local hardware, rather than relying on cloud-based services. This approach enhances privacy and can work offline. Language bindings are wrapper libraries that allow a program written in one programming language to use a library or API written in another language, facilitating integration across different software ecosystems.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/handy-computer/transcribe.cpp">GitHub - handy-computer/transcribe.cpp: ggml speech-to-text inference for 16+ model families · GitHub</a></li>
<li><a href="https://blog.mozilla.ai/announcing-transcribe-cpp/">Announcing transcribe.cpp</a></li>
<li><a href="https://workshop.cjpais.com/projects/transcribe-cpp">Project - transcribe.cpp</a></li>

</ul>
</details>

**Discussion**: The community showed strong engagement, with discussions focusing on funding for the project's maintenance, the availability of Python bindings, and practical applications like integrating speech recognition into prompting toolkits or for note-taking. There was also interest in adding speaker separation features.

**Tags**: `#speech-recognition`, `#AI`, `#local-inference`, `#machine-learning`, `#cpp`

---

<a id="item-2"></a>
## [EU AI Act OpenRAG Dataset Released with Structured Chunks and BGE-M3 Embeddings](https://www.reddit.com/r/MachineLearning/comments/1uytlac/eu_ai_act_openrag_933_legally_structured_chunks/) ⭐️ 8.0/10

A downloadable corpus of the EU AI Act, EU AI Act OpenRAG, has been released, featuring 933 legally structured chunks and normalized 1024-dimensional BGE-M3 embeddings stored in a SQLite file, with evaluation showing improved performance over baseline methods. This dataset is significant as it provides a well-structured, evaluated resource for the AI/ML community, particularly relevant to AI regulation and legal NLP applications, with a novel approach of chunking by legal structure instead of simple sliding windows. The corpus chunks by legal structure (per article, recital, definition, annex point, etc.) instead of sliding windows, includes EUR-Lex links and Article 113 metadata, uses narrow derived labels with ambiguous cases as NULL, and evaluation shows improved recall@20 (0.541 vs 0.449) and hit@10 (0.927 vs 0.898) over baseline.

reddit · r/MachineLearning · /u/Automatic-Forever-63 · Jul 17, 08:18

**Background**: RAG (Retrieval-Augmented Generation) is a technique that combines retrieval of relevant documents with generative AI to improve response accuracy. BGE-M3 is a multilingual embedding model developed by the Beijing Academy of Artificial Intelligence (BAAI) that enhances semantic retrieval with dense, sparse, and multi-vector heads. For legal documents, chunking by inherent structure (like articles, recitals) preserves legal context, unlike simple sliding windows, which can break semantic coherence.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/understanding-bge-m3-powerful-multilingual-embedding-model-shankaran-si4fc">Understanding BGE M 3 : A Powerful Multilingual Embedding Model for...</a></li>
<li><a href="https://github.com/langflow-ai/openrag">GitHub - langflow-ai/ openrag : OpenRAG is a comprehensive, single...</a></li>
<li><a href="https://milvus.io/ai-quick-reference/what-are-best-practices-for-chunking-lengthy-legal-documents-for-vectorization">What are best practices for chunking lengthy legal documents for vectorization?</a></li>

</ul>
</details>

**Tags**: `#EU AI Act`, `#RAG`, `#legal NLP`, `#dataset`, `#BGE-M3`

---