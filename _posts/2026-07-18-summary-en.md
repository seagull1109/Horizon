---
layout: default
title: "Horizon Summary: 2026-07-18 (EN)"
date: 2026-07-18
lang: en
---

> From 33 items, 8 important content pieces were selected

---

1. [First atmosphere found on Earth-like planet in habitable zone of distant star](#item-1) ⭐️ 9.0/10
2. [Kimi K3: Moonshot AI's 2.8T Parameter Model and the Pelican Benchmark](#item-2) ⭐️ 8.0/10
3. [Firefox Compiled to WebAssembly](#item-3) ⭐️ 8.0/10
4. [Thinking Machines Lab releases Inkling open-weights multimodal model](#item-4) ⭐️ 8.0/10
5. [Linus Torvalds Clarifies Linux’s Stance on AI](#item-5) ⭐️ 8.0/10
6. [Stereo2Spatial: Convert Stereo Music Tracks to Spatialized Binaural Mixes](#item-6) ⭐️ 8.0/10
7. [EU AI Act OpenRAG: 933 legally structured chunks and BGE-M3 embeddings in one SQLite file](#item-7) ⭐️ 8.0/10
8. [ExTernD: Novel Ternary PTQ Method for LLMs](#item-8) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [First atmosphere found on Earth-like planet in habitable zone of distant star](https://www.bbc.com/news/articles/cy4kdd1e0ejo) ⭐️ 9.0/10

Scientists have discovered the first atmosphere on an Earth-like planet located in the habitable zone of a distant star, marking a significant breakthrough in the search for potentially habitable worlds beyond our solar system. This discovery is significant because it represents a major step forward in the search for extraterrestrial life and habitable planets. It demonstrates that Earth-like planets in habitable zones can retain atmospheres, which is crucial for supporting life as we know it. The planet, LHS 1140b, is located 48 light-years away and orbits a red dwarf star. The atmosphere was detected using JWST spectroscopy, which ruled out the possibility of it being a mini-Neptune.

hackernews · neversaydie · Jul 17, 14:06 · [Discussion](https://news.ycombinator.com/item?id=48947560)

**Background**: The habitable zone, also known as the Goldilocks zone, is the range of orbits around a star where a planet could potentially support liquid water on its surface. This is considered essential for life as we know it. Most previously discovered exoplanets in habitable zones have been either super-Earths or gas giants, making this discovery of an Earth-like planet with an atmosphere particularly significant. Atmospheric detection of exoplanets is challenging and typically relies on indirect methods like spectroscopy.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Habitable_zone">Habitable zone</a></li>
<li><a href="https://science.nasa.gov/exoplanets/habitable-zone/">The Habitable Zone - NASA Science</a></li>
<li><a href="https://www.britannica.com/science/habitable-zone">Habitable zone | Astrobiology, Exoplanets & Habitability | Britannica</a></li>

</ul>
</details>

**Discussion**: Community members expressed skepticism about the planet being truly Earth-like, with one commenter noting that red dwarfs are known to be unstable and that LHS 1140b might be more like a mini-Neptune. However, another commenter referenced JWST emission spectroscopy that rules out the mini-Neptune possibility. There was also discussion about the feasibility of future space exploration to this planet and the implications for the Fermi paradox.

**Tags**: `#astronomy`, `#exoplanets`, `#space science`, `#habitable zone`, `#atmospheric detection`

---

<a id="item-2"></a>
## [Kimi K3: Moonshot AI's 2.8T Parameter Model and the Pelican Benchmark](https://simonwillison.net/2026/Jul/16/kimi-k3/#atom-everything) ⭐️ 8.0/10

Moonshot AI announced Kimi K3, a 2.8 trillion parameter model claiming to be the first open 3T-class model, with self-reported benchmarks showing it mostly beats Claude Opus 4.8 max and GPT-5.5 high, while being available via their website and API with an open weight release promised by July 27, 2026. This is significant as Kimi K3 represents a major advancement in Chinese AI development, potentially challenging established models like Claude and GPT in certain benchmarks, while its open weight release could democratize access to state-of-the-art AI technology for developers and researchers. Kimi K3's pricing is $3/million input tokens and $15/million output tokens, making it the most expensive model from a Chinese AI lab to date, and it shows significant improvements in token efficiency with 21% fewer output tokens than its predecessor Kimi K2.6.

rss · Simon Willison · Jul 16, 20:19 · [Discussion](https://news.ycombinator.com/item?id=48947717)

**Background**: Large language models (LLMs) are AI systems trained on vast amounts of text data to generate human-like responses. Model parameters represent the number of weights in the neural network, with larger models typically having greater capabilities but also higher computational requirements. The 'pelican benchmark' is a simple test Simon Willison created to compare how different AI models handle creative image generation tasks, specifically creating an SVG of a pelican riding a bicycle.

<details><summary>References</summary>
<ul>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you've been told</a></li>
<li><a href="https://huggingface.co/spaces/victor/pelican-benchmark">Pelican Benchmark - a Hugging Face Space by victor</a></li>
<li><a href="https://developer.nvidia.com/blog/scaling-language-model-training-to-a-trillion-parameters-using-megatron/">Scaling Language Model Training to a Trillion Parameters Using...</a></li>

</ul>
</details>

**Discussion**: Community comments highlight concerns about the pelican benchmark's validity, noting that Simon's website likely influenced model training data, questioning tokenization differences across models, and suggesting the benchmark doesn't test important modern capabilities like agentic tool calling. Some users also point out the need for multiple runs to account for variability in model outputs.

**Tags**: `#AI`, `#large language models`, `#model release`, `#benchmarking`, `#Kimi K3`

---

<a id="item-3"></a>
## [Firefox Compiled to WebAssembly](https://simonwillison.net/2026/Jul/16/firefox-in-webassembly/#atom-everything) ⭐️ 8.0/10

Puter successfully compiled the Firefox browser to WebAssembly, enabling the entire browser to run within another browser. The project utilized AI tools including Claude Opus and Fable tokens for development and demonstrates advanced WebAssembly capabilities. This achievement showcases the extreme capabilities of WebAssembly and has potential implications for browser architecture and web-based applications. It demonstrates how complex software like a full-featured browser can be executed within a web environment, opening new possibilities for web development. The project used an estimated $25,000 worth of Claude Opus and Fable tokens for development, though a subscription plan reduced actual costs. The demo implements end-to-end encryption and uses the Wisp protocol to proxy all traffic through Puter's servers, as browser-based code cannot open arbitrary network connections.

rss · Simon Willison · Jul 16, 23:34

**Background**: WebAssembly (WASM) is a binary instruction format for a stack-based virtual machine, designed as a portable target for compilation of high-level languages like C++, Rust, and others, enabling near-native performance in web browsers. Gecko is the open-source browser engine that powers Firefox, known for its strong single-process support which made it suitable for this compilation project. The Wisp protocol is a low-overhead protocol designed for proxying multiple TCP and UDP sockets over a single WebSocket connection, essential for this browser-in-browser implementation.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/MercuryWorkshop/wisp-protocol">GitHub - MercuryWorkshop/ wisp - protocol : Wisp is a low-overhead...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Opus">Claude Opus</a></li>
<li><a href="https://en.wikipedia.org/wiki/Gecko">Gecko</a></li>

</ul>
</details>

**Discussion**: The project generated significant discussion on Hacker News, with the team having to scale up their servers to handle the traffic during the conversation. Community members expressed amazement at the technical achievement while noting concerns about the proxying approach and its potential costs for widespread adoption.

**Tags**: `#WebAssembly`, `#Browser`, `#Firefox`, `#AI`, `#WebDevelopment`

---

<a id="item-4"></a>
## [Thinking Machines Lab releases Inkling open-weights multimodal model](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 8.0/10

Thinking Machines Lab released Inkling, a 975B parameter open-weights multimodal transformer model trained on 45 trillion tokens of text, images, audio and video under Apache-2.0 license. They also announced Inkling-Small, a 276B parameter model with 12B active parameters, which is still being tested. This represents important progress in accessible AI research as it provides a large-scale open-weights multimodal model that can compete with models from China and other open-source alternatives. The Apache-2.0 license makes it valuable for both research and commercial applications in the AI community. Inkling is a Mixture-of-Experts transformer with 975B total parameters but only 41B active at any time, making it computationally efficient. The model documentation is minimal, and it's positioned as a strong base model for fine-tuning rather than a frontier model.

rss · Simon Willison · Jul 16, 15:35

**Background**: A Mixture-of-Experts (MoE) transformer is a neural architecture that integrates numerous parallel expert subnetworks with a gating mechanism to selectively process tokens, ensuring scalability and efficient compute. Unlike traditional transformers where every part of the model is activated for every input, MoE models dynamically route inputs to only a subset of model components. An open-weights model is an AI model whose core components (trained parameters) are publicly released, allowing anyone to download and use it, which promotes transparency and accessibility in AI development.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/mixture-of-experts-transformer">Mixture - of - Experts Transformer</a></li>
<li><a href="https://www.emergentmind.com/topics/mixture-of-experts-transformer-architecture">Mixture - of - Experts Transformer Architecture</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>

</ul>
</details>

**Tags**: `#AI`, `#machine-learning`, `#open-source`, `#multimodal`, `#transformers`

---

<a id="item-5"></a>
## [Linus Torvalds Clarifies Linux’s Stance on AI](https://simonwillison.net/2026/Jul/16/linus-torvalds/#atom-everything) ⭐️ 8.0/10

Linus Torvalds stated that Linux is not an anti-AI project and that those who disagree can fork it or leave, viewing AI as a useful tool. As the top-level maintainer of Linux, his stance carries significant weight in the open-source community and addresses the ongoing debate about AI integration in open-source projects, potentially influencing future development directions. Torvalds emphasized his willingness to take a firm stance on the issue, noting that AI’s usefulness is no longer in question and that those who doubt it haven’t used it.

rss · Simon Willison · Jul 16, 13:26

**Background**: In open-source projects, the top-level maintainer has the authority to set the project’s direction and make key decisions. Forking is a common practice in open-source where developers can create a new version of the project if they disagree with the original’s direction, as allowed by open-source licenses.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Fork_(software_development)">Fork (software development) - Wikipedia</a></li>
<li><a href="https://www.linuxfoundation.org/blog/open-source-maintainers-what-they-need-and-how-to-support-them">Open source maintainers : What they need and how to support them</a></li>

</ul>
</details>

**Tags**: `#Linux`, `#AI`, `#Open-source`, `#Linus Torvalds`, `#Kernel development`

---

<a id="item-6"></a>
## [Stereo2Spatial: Convert Stereo Music Tracks to Spatialized Binaural Mixes](https://www.reddit.com/r/MachineLearning/comments/1uzevbg/stereo2spatial_convert_stereo_music_tracks_to/) ⭐️ 8.0/10

A developer released Stereo2Spatial, a flow-matching diffusion model that converts stereo music tracks to spatialized binaural mixes. The model was initially developed in the latent space of a VAE but pivoted to raw waveforms for better quality, incorporating memory tokens for stable long-context generation and amplitude lifting to solve training instability issues. This represents a novel application of diffusion models and VAEs to audio processing, addressing the lack of high-quality spatial audio for existing music. The open-source release and innovative techniques could significantly impact the music and entertainment industries by enabling widespread spatial audio conversion. The model was trained on 7,669 tracks for ~20 days on 2x A6000 GPUs, with a two-stage training process. The waveform version, which offers direct binaural output, was made possible by implementing amplitude lifting (scaling audio tracks to an RMS of 0.33 and multiplying by 3) to overcome training instability. The project, including a Windows desktop app, is released under the Apache 2.0 license.

reddit · r/MachineLearning · /u/kittenkrazy · Jul 17, 22:55

**Background**: Flow-matching diffusion models are a type of generative AI that learn to generate data by transforming a simple distribution into a complex one, often used for images, videos, and now audio. Variational Autoencoders (VAEs) are generative models that learn a compressed, probabilistic representation (latent space) of input data, allowing for reconstruction and generation. Latent space is a lower-dimensional representation of data where similar items are positioned closer together, enabling efficient data compression and manipulation.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2506.02070">[2506.02070] An Introduction to Flow Matching and Diffusion Models</a></li>
<li><a href="https://www.ibm.com/think/topics/variational-autoencoder">What is a Variational Autoencoder? | IBM</a></li>
<li><a href="https://en.wikipedia.org/wiki/Latent_space">Latent space</a></li>

</ul>
</details>

**Tags**: `#audio-processing`, `#diffusion-models`, `#vae`, `#spatial-audio`, `#machine-learning`

---

<a id="item-7"></a>
## [EU AI Act OpenRAG: 933 legally structured chunks and BGE-M3 embeddings in one SQLite file](https://www.reddit.com/r/MachineLearning/comments/1uytlac/eu_ai_act_openrag_933_legally_structured_chunks/) ⭐️ 8.0/10

A downloadable SQLite database containing 933 legally structured chunks of the EU AI Act with BGE-M3 embeddings has been released for RAG and legal-NLP experimentation. This resource is significant for legal AI research as it provides a high-quality, structured dataset for experimenting with regulatory compliance and legal NLP, addressing a specific need in the field. The corpus chunks based on legal structure (articles, recitals, definitions, annexes) rather than simple sliding windows, includes 1024-dimensional BGE-M3 embeddings, and provides evaluation results showing improved performance over baseline methods.

reddit · r/MachineLearning · /u/Automatic-Forever-63 · Jul 17, 08:18

**Background**: RAG (Retrieval-Augmented Generation) is a technique that enhances large language models by retrieving relevant information from an external knowledge base before generating a response. BGE-M3 is a multilingual embedding model that combines dense, sparse, and multi-vector heads to improve semantic retrieval and cross-lingual alignment. The EU AI Act (Regulation (EU) 2024/1689) is a comprehensive regulation governing artificial intelligence within the European Union.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/bge-m3-embedding">BGE M 3 - Embedding : Multilingual Retrieval Model</a></li>
<li><a href="https://huggingface.co/BAAI/bge-m3?ref=blog-ko.allganize.ai">BAAI/ bge - m 3 · Hugging Face</a></li>

</ul>
</details>

**Discussion**: The author requests technical feedback, particularly on retrieval evaluation, structural chunking methodology, and useful additional baselines.

**Tags**: `#legal-nlp`, `#rag`, `#eu-ai-act`, `#dataset`, `#embeddings`

---

<a id="item-8"></a>
## [ExTernD: Novel Ternary PTQ Method for LLMs](https://www.reddit.com/r/MachineLearning/comments/1uy2zb3/externd_expandedrank_ternary_decomposition/) ⭐️ 8.0/10

A research paper introduces ExTernD, a method for ternary post-training quantization (PTQ) of large language models (LLMs) that decomposes weight matrices into two ternary matrices and a diagonal scaling matrix, aiming to achieve high accuracy with minimal VRAM overhead. This approach could significantly improve the efficiency of deploying LLMs by enabling high-accuracy quantization with only 3-bit weights, potentially reducing memory usage and accelerating inference without substantial accuracy loss, which is crucial for on-device AI applications. The core innovation is decomposing the original matrix into two ternary matrices and a diagonal scaling matrix, allowing the inner rank to be arbitrarily large to improve accuracy, while the slight increase in VRAM is justified by leveraging ternary math operations.

reddit · r/MachineLearning · /u/LMTLS5 · Jul 16, 13:31

**Background**: Post-training quantization (PTQ) is a technique to reduce model size and improve inference speed by mapping high-precision weights (e.g., FP32) to lower-precision representations (e.g., INT8, INT4, or ternary) after a model is trained. Ternary quantization represents weights using only three values (e.g., -1, 0, +1), which can significantly reduce memory and computational requirements but often suffers from accuracy degradation. The ExTernD paper argues that fixed matrix size in ternary PTQ is a dead end and proposes a decomposition approach to overcome this limitation.

<details><summary>References</summary>
<ul>
<li><a href="https://developers.google.com/edge/litert/conversion/tensorflow/quantization/post_training_quantization">Post-training quantization | Google AI Edge | Google for Developers</a></li>
<li><a href="https://developer.nvidia.com/blog/optimizing-llms-for-performance-and-accuracy-with-post-training-quantization/">Optimizing LLMs for Performance and Accuracy with Post-Training Quantization | NVIDIA Technical Blog</a></li>
<li><a href="https://docs.pytorch.org/TensorRT/ts/ptq.html">Post Training Quantization (PTQ) — Torch-TensorRT</a></li>

</ul>
</details>

**Discussion**: The author of the paper, /u/LMTLS5, explains that the core idea is to avoid the limitations of fixed matrix size in ternary PTQ by decomposing matrices, allowing for arbitrarily high accuracy by increasing the inner rank, and that the slight VRAM increase is worthwhile when leveraging ternary math.

**Tags**: `#LLM`, `#quantization`, `#model-compression`, `#ternary`, `#PTQ`

---