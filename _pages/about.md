---
permalink: /
title: null
---

<div class="home-section" id="about" markdown="1">

## About
{: .home-section__title}

I am **Xuhong He (贺旭鸿)**, a Master's student in **Intelligent Information Systems (MIIS)** at **Carnegie Mellon University**, where I currently work with **[Prof. Fernando Diaz](https://841.io)** on **information retrieval**, **LLM agents**, and **query simulation/evaluation**.

Most recently, I was an **AI Research Scientist Intern at Foundation AI (Cisco)**, working on **looped Transformers for reasoning**.

Before CMU, I completed dual undergraduate degrees from **Zhejiang University** and the **University of Illinois Urbana-Champaign**. I previously collaborated with **[Prof. Zhiting Hu](https://zhiting.ucsd.edu)** at **University of California San Diego** on **SimWorld**, a UE5-based simulator for autonomous agents in physical and social worlds. I also worked as a software engineer intern at **ByteDance** on large-scale search infrastructure and neural sparse retrieval.

</div>

<div class="home-section" id="experience" markdown="1">

## Experience
{: .home-section__title}

<section class="exp-section" id="internship-experience">
  <h3 class="exp-section__title">Internship Experience</h3>

  <div class="exp-block">
    <h4 class="exp-block__title">Foundation AI (Cisco)</h4>
    <p class="exp-block__meta"><strong>AI Research Scientist Intern</strong><br>May 2026 - Aug 2026</p>
    <div class="exp-item__content">
      <p>Conducted research on <strong>looped Transformers</strong>, with a focus on reasoning and efficient model training.</p>
    </div>
  </div>

  <div class="exp-block">
    <h4 class="exp-block__title">ByteDance</h4>
    <p class="exp-block__meta"><strong>Software Engineer Intern, Search Infrastructure (Information Retrieval)</strong><br>Jul 2024 - Mar 2025</p>
    <div class="exp-item exp-item--centered">
      <div class="exp-item__media">
        <img src="/assets/images/bytedance_intern.png" alt="ByteDance internship project diagram">
      </div>
      <div class="exp-item__content">
        <p>Built a production-level <strong>neural sparse retrieval pipeline (SPLADE, BGE)</strong> into ByteES (an <strong>OpenSearch-based</strong> search stack), focusing on the full pipeline from indexing to serving under large-scale constraints. Also explored and prototyped Learning-to-Rank reranking integration to improve relevance in the existing production system.</p>
      </div>
    </div>
  </div>
</section>

<section class="exp-section" id="research-experience">
  <h3 class="exp-section__title">Research Experience</h3>

  <div class="exp-block">
    <h4 class="exp-block__title"><a href="https://arxiv.org/abs/2606.19911">Multi-Agent Transactive Memory (MATM)</a></h4>
    <p class="exp-block__meta">Jan 2026 - May 2026<br>Areas: LLM Agents, Information Retrieval, Memory, Reranking<br>Advisor: <a href="https://841.io">Prof. Fernando Diaz</a> (CMU & Google)</p>
    <div class="exp-item exp-item--centered">
      <div class="exp-item__media">
        <img src="/assets/images/matm.png" alt="Multi-Agent Transactive Memory (MATM) system overview">
      </div>
      <div class="exp-item__content">
        <p>Developed <strong>MATM</strong>, a population-level memory system that lets LLM agents retrieve and reuse <strong>trajectory-based procedural knowledge</strong> from prior agents in <strong>ALFWorld</strong> and <strong>WebArena</strong>. Built state-aware indexing and reranking over large agent-generated trajectory repositories, improving downstream task success and step efficiency without requiring joint training or centralized coordination.</p>
      </div>
    </div>
  </div>

  <div class="exp-block">
    <h4 class="exp-block__title"><a href="https://arxiv.org/abs/2604.21096">Multilingual Simulation of Tip-of-the-Tongue (ToT) Queries</a></h4>
    <p class="exp-block__meta">Aug 2025 - Present<br>Areas: LLMs, Information Retrieval, Evaluation<br>Advisor: <a href="https://841.io">Prof. Fernando Diaz</a> (CMU & Google)</p>
    <div class="exp-item exp-item--centered">
      <div class="exp-item__media">
        <img src="/assets/images/tot.png" alt="Multilingual Tip-of-the-Tongue (ToT) simulation overview">
      </div>
      <div class="exp-item__content">
        <p>Created a <strong>multilingual Tip-of-the-Tongue query simulation</strong> pipeline from Wikipedia corpora, with a focus on Chinese, Japanese and Korean for <strong>NTCIR-19 Tip-of-the-Tongue (ToT) Track</strong>. Verified quality via retrieval-behavior consistency across <strong>Systems-rank Correlation</strong> evaluation, ensuring simulated queries behave similarly to human queries in ranking.</p>
      </div>
    </div>
  </div>

  <div class="exp-block">
    <h4 class="exp-block__title"><a href="https://simworld.org">SimWorld: Open-ended Simulator for Agents in Physical and Social Worlds</a></h4>
    <p class="exp-block__meta">Jun 2024 - May 2025<br>Areas: LLMs, Agents<br>Advisor: <a href="https://zhiting.ucsd.edu">Prof. Zhiting Hu</a> (UCSD)</p>
    <div class="exp-item exp-item--centered">
      <div class="exp-item__media">
        <img src="/assets/images/simworld.jpg" alt="SimWorld platform overview">
      </div>
      <div class="exp-item__content">
        <p>Developed an Unreal Engine 5-based simulator for developing and evaluating autonomous agents (including LLM/VLM agents) in rich physical and social worlds, featuring open-ended realistic simulation with <strong>language-controllable world generation</strong>, a rich <strong>gym-like LLM/VLM agent interface</strong> with multimodal observations and grounded natural-language actions across multiple abstraction levels, and <strong>diverse long-horizon physical/social reasoning scenarios</strong> for systematic agent training and evaluation.</p>
      </div>
    </div>
  </div>
</section>

</div>

<div class="home-section" id="publications" markdown="1">

## Publications
{: .home-section__title}

<div class="pub-entry">
  <h4 class="pub-entry__title"><a href="https://arxiv.org/abs/2606.19911">Multi-Agent Transactive Memory</a></h4>
  <p class="pub-entry__authors">To Eun Kim*, <strong>Xuhong He*</strong>, Dishank Jain*, Ambuj Agrawal, Negar Arabzadeh, Fernando Diaz.</p>
  <p class="pub-entry__venue">Submitted to EACL 2027</p>
</div>

<div class="pub-entry">
  <h4 class="pub-entry__title"><a href="https://arxiv.org/abs/2604.21096">Multilingual and Domain-Agnostic Tip-of-the-Tongue Query Generation for Simulated Evaluation</a></h4>
  <p class="pub-entry__authors"><strong>Xuhong He</strong>, To Eun Kim, Maik Fr&ouml;be, Jaime Arguello, Bhaskar Mitra, Fernando Diaz.</p>
  <p class="pub-entry__venue">SIGIR 2026; NTCIR ToT Track</p>
</div>

<div class="pub-entry">
  <h4 class="pub-entry__title"><a href="https://arxiv.org/abs/2512.01078">SimWorld: An Open-ended Realistic Simulator for Autonomous Agents in Physical and Social Worlds</a></h4>
  <p class="pub-entry__authors">Jiawei Ren*, Yan Zhuang*, Xiaokang Ye*, Lingjun Mao, <strong>Xuhong He</strong>, Jianzhi Shen, Mrinaal Dogra, Yiming Liang, Ruixuan Zhang, Tianai Yue, Yiqing Yang, Eric Liu, Ryan Wu, Kevin Benavente, Rajiv Mandya Nagaraju, Muhammad Faayez, Xiyan Zhang, Dhruv Vivek Sharma, Xianrui Zhong, Ziqiao Ma, Tianmin Shu, Zhiting Hu, Lianhui Qin.</p>
  <p class="pub-entry__venue">Technical report, 2025</p>
</div>

<div class="pub-entry">
  <h4 class="pub-entry__title"><a href="https://neurips.cc/virtual/2025/loc/san-diego/poster/119002">SimWorld: An Open-ended Simulator for Agents in Physical and Social Worlds</a></h4>
  <p class="pub-entry__authors">Xiaokang Ye*, Jiawei Ren*, Yan Zhuang, <strong>Xuhong He</strong>, Yiming Liang, Yiqing Yang, Xianrui Zhong, Mrinaal Dogra, Eric Liu, Kevin Benavente, Rajiv Nagaraju, Dhruv Sharma, Ziqiao Ma, Tianmin Shu, Zhiting Hu, Lianhui Qin.</p>
  <p class="pub-entry__venue">NeurIPS 2025 Spotlight</p>
</div>

<div class="pub-entry">
  <h4 class="pub-entry__title"><a href="https://arxiv.org/abs/2512.10046">Synthesizing Photorealistic and Dynamic Urban Environments for Multimodal Robot Navigation and Collaboration</a></h4>
  <p class="pub-entry__authors">Yan Zhuang, Jiawei Ren*, Xiaokang Ye*, Jianzhi Shen, Ruixuan Zhang, Tianai Yue, Muhammad Faayez, <strong>Xuhong He</strong>, Xiyan Zhang, Ziqiao Ma, Lianhui Qin, Zhiting Hu, Tianmin Shu.</p>
  <p class="pub-entry__venue">NeurIPS 2025 Poster</p>
</div>

</div>

<div class="home-section" id="blog" markdown="1">

## Blog
{: .home-section__title}

<div class="placeholder-block">
  <p class="placeholder-block__title">Under Construction</p>
  <p class="placeholder-block__text">I plan to use this section for research notes, engineering writeups, and short posts on information retrieval, LLM agents, and systems. The blog structure is kept in the repo, but public posts will be added later.</p>
</div>

</div>

<div class="home-section" id="service" markdown="1">

## Service
{: .home-section__title}

- **Co-organizer**, [NTCIR-19 Tip-of-the-Tongue (ToT) Track](https://ntcir-tot.github.io) (2026)
- **Reviewer**, [ICLR 2027](https://iclr.cc/Conferences/2027)
- **Reviewer**, [SIGIR 2026 (Resources Paper Track)](https://sigir2026.org/en-AU/pages/submissions/resources-track)

</div>

<div class="home-section" id="education" markdown="1">

## Education
{: .home-section__title}

- **Carnegie Mellon University** (Dec 2026, expected)  
  M.S. in Intelligent Information Systems (MIIS)
- **University of Illinois Urbana-Champaign** (May 2025)  
  B.S. in Computer Engineering (double degree)
- **Zhejiang University** (May 2025)  
  B.E. in Electronic and Computer Engineering (double degree)

</div>
