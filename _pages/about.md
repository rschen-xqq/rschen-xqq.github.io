---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a second-year Ph.D. student in Computer Science at the [Legal Tech Group](https://www.cs.cit.tum.de/lt/tum-legal-tech-working-group/) of the [Technical University of Munich (TUM)](https://www.cit.tum.de/cit/startseite/), advised by [Prof. Matthias Grabmair](https://www.cs.cit.tum.de/lt/team/matthias-grabmair/). My research focuses on **post-training and alignment for legal large language models**, with particular interests in reinforcement learning, on-policy distillation, agentic search and tool use, model evaluation, and reward modeling.

I received my M.Sc. in Robotics, Cognition, Intelligence from TUM in 2025. My master's thesis, completed in collaboration with Google DeepMind, studied relation-specific neurons in multilingual LLMs and led to a paper at **EMNLP 2025 Main**. I hold a B.Eng. in Mechanical Engineering from [Southeast University](https://www.seu.edu.cn/english/), Nanjing, China.

## <i class="fas fa-newspaper"></i> News

<div class="news-list">
  <div class="news-item">
    <span class="news-date">Apr 2026</span>
    <span class="news-text">Our paper <em>"Exploiting LLM-as-a-Judge Disposition on Free Text Legal QA via Prompt Optimization"</em> is accepted at <strong>ICAIL 2026</strong> — preprint available on <a href="https://arxiv.org/abs/2604.20726">arXiv</a>!</span>
  </div>
  <div class="news-item">
    <span class="news-date">2026</span>
    <span class="news-text"><em>"AppeaLLM: Mimicking a Closed-World Environment for Court Decision Prediction"</em> is published at <strong>ACM CS&amp;LAW 2026</strong> (<a href="https://doi.org/10.1145/3788646.3789528">DOI</a>).</span>
  </div>
  <div class="news-item">
    <span class="news-date">Nov 2025</span>
    <span class="news-text"><em>"On Relation-Specific Neurons in Large Language Models"</em> is accepted to the <strong>EMNLP 2025</strong> Main Conference (<a href="https://arxiv.org/abs/2502.17355">arXiv</a>)!</span>
  </div>
  <div class="news-item">
    <span class="news-date">Feb 2025</span>
    <span class="news-text">The preprint of my master thesis, <em>"On Relation-Specific Neurons in Large Language Models"</em>, is available on <a href="https://arxiv.org/abs/2502.17355">arXiv</a>.</span>
  </div>
</div>

## <i class="fas fa-project-diagram"></i> Research Experience

<div class="project-card" markdown="1">

### [Generatives Sprachmodell Justiz (GSJ)](https://www.bmjv.de/DE/themen/digitales/digitalisierung_justiz/digitalisierungsinitiative/laendervorhaben/_doc/artikel_vorhaben_06_gsj.html)

<p class="project-meta"><i class="fas fa-university"></i>Legal Tech Group, TUM &nbsp;·&nbsp; <i class="fas fa-calendar-alt"></i>06.2025 - Present</p>

*LLM Post-Training · Alignment · Legal NLP Systems*

- Develop scalable post-training recipes and distributed pipelines using reinforcement learning and on-policy distillation for legal reasoning and summarization.
- Engineer runtime infrastructure for tool-using legal agents, including context management, sandboxed execution, state machines, and multi-turn workflow integration.

</div>

<div class="project-card" markdown="1">

### On-Policy Self-Distillation for Legal Reasoning

<p class="project-meta"><i class="fas fa-university"></i>Legal Tech Group, TUM &nbsp;·&nbsp; <i class="fas fa-calendar-alt"></i>05.2026 - 07.2026</p>

*LLM Post-Training · Knowledge Distillation · Legal Reasoning*

- Designed on-policy self-distillation workflows for compact LLMs on the LEXAM reasoning benchmark.
- Studied how privileged information, including gold rationales, statutory hints, and teacher critiques, can improve training stability and out-of-distribution generalization.

</div>

<div class="project-card" markdown="1">

### Answer-Aware Hint Refinement for RL-Trained Search Agents

<p class="project-meta"><i class="fas fa-university"></i>Legal Tech Group, TUM &nbsp;·&nbsp; <i class="fas fa-calendar-alt"></i>03.2026 - 05.2026</p>

*Agentic RAG · Reinforcement Learning · Tool Use*

- Developed answer-aware, loss-masked hint refinement for multi-hop search agents to address credit assignment and reward sparsity.
- Built distributed RL training infrastructure across an 8xH200 GPU cluster using VeRL, vLLM, GPU-accelerated FAISS, and an asynchronous LLM-judge reward server.

</div>

## <i class="fab fa-github"></i> Open Source

<div class="project-card" markdown="1">

### [Zotero Smart Highlighter](https://github.com/MemorushB/zotero-smart-highlighter)

*Intelligent Document Assistant · TypeScript · Python*

An open-source Zotero 8 plugin that extracts and highlights informative passages in research papers through configurable backends: local BM25 ranking, an on-device neural reranker, or LLM APIs.

</div>
