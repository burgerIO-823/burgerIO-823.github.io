---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---


I am currently a Research Assistant at the **AGI Lab**, **Westlake University**, advised by Prof. [Chi Zhang](https://icoz69.github.io). Concurrently, I serve as a Remote Research Intern at the **NLP Lab**, **University of California, Merced**, under the supervision of Prof. [Yiwei Wang](https://wangywust.github.io). Prior to this, I received my B.Eng. degree in Artificial Intelligence from **Hebei University of Technology**.

My research interests broadly encompass **Large Language Models (LLMs)**, **Multimodal Learning & Alignment**, and **Reinforcement Learning**. Specifically, I am deeply dedicated to designing efficient **training and post-training methodologies** for **Diffusion Large Language Models (dLLMs)**.

[Download my CV](files/CV_Boyan_Han.pdf)

# Current Research

**Logic-aware RL for dLLM generation order**

Current dLLMs tend to degenerate into linear autoregressive behaviors when facing complex reasoning tasks, failing to fully leverage their non-autoregressive potential. I hypothesize that problem decomposition is naturally **tree-structured** rather than strictly linear. To validate this, I am developing a **Logic-aware Reinforcement Learning framework** designed to optimize the generation order of dLLMs. By extracting explicit logical dependency graphs (e.g., via Abstract Syntax Trees in code) to formulate reward signals, this framework guides the diffusion denoising trajectory. The goal is to encourage the model to discover an optimal generation order that balances **parallel efficiency** with **strict logical validity**, thereby preventing degeneration into linear sequences. (📑 Status: In preparation.)

**Format-constrained generation method for dLLMs**

While Diffusion Large Language Models (dLLMs) offer promising parallel generation capabilities, they often struggle to adhere to strict formatting constraints (e.g., Chain-of-Thought structures like `<think>`/`<answer>` tags) in zero-shot settings. To address this, I propose a **training-free inference framework** based on **Dynamic Infilling Anchors**. This method introduces a novel sampling strategy that utilizes token-level softmax confidence scores to dynamically identify and stabilize high-confidence tokens as "anchors" during the denoising process. Extensive evaluations on mathematical reasoning benchmarks (**GSM8K, MATH**) demonstrate that this approach significantly enhances structural adherence without sacrificing reasoning accuracy, outperforming both static infilling baselines and standard generation methods. (📑 Status: Under review at ICLR 2026)

# Skills

- **Programming**: Python, PyTorch, C, Markdown
- **Research Areas**: Large Language Models, Multimodal Learning, Reinforcement Learning
- **Tools**: Git, Jupyter, LaTeX
