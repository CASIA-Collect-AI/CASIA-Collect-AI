<div align="center">

# CASIA-Collect-AI

**Unmanned Collective Intelligence Team**
Institute of Automation, Chinese Academy of Sciences (CASIA)

*Curating high-quality open-source research code in Multi-Agent RL, LLM, and Robotics*

[English](https://github.com/CASIA-Collect-AI/CASIA-Collect-AI/blob/main/README.md) | [中文](https://github.com/CASIA-Collect-AI/CASIA-Collect-AI/blob/main/README_CN.md)

[![GitHub](https://img.shields.io/badge/GitHub-CASIA--Collect--AI-181717?logo=github)](https://github.com/CASIA-Collect-AI)
[![Lab](https://img.shields.io/badge/CASIA-ia.cas.cn-blue)](https://www.ia.cas.cn)
[![Contact](https://img.shields.io/badge/Contact-zhiqiang.pu%40ia.ac.cn-red)](mailto:zhiqiang.pu@ia.ac.cn)

</div>

---

## 👨‍🏫 About the Team

We are the **Unmanned Collective Intelligence Team (无人集群智能团队)**, led by **Prof. Zhiqiang Pu (蒲志强)** at the Institute of Automation, Chinese Academy of Sciences (CASIA).

**CASIA-Collect-AI** is our open-source code collection platform, curating and maintaining high-quality research code from our team and affiliated researchers in MARL, LLM, and robotics.

Our group is affiliated with the **National Key Laboratory of Cognition and Decision Intelligence for Complex Systems** (认知与决策智能全国重点实验室), where Prof. Pu serves as deputy director. We are also part of the School of Artificial Intelligence, University of Chinese Academy of Sciences (UCAS).

Our research operates at the intersection of:
- 🤖 **Multi-Agent Reinforcement Learning (MARL)** — cooperative, heterogeneous, large-scale
- 🧠 **LLM × MARL** — RL-based LLM fine-tuning, alignment, and parameter-efficient methods
- ⚽ **Football / Sports AI** — data-driven tactic generation, VLM-guided policy alignment
- 🚁 **Autonomous Unmanned Systems** — UAV formation control, nonlinear flight control

---

## 🔬 Research Directions

| Direction | Description | Representative Work |
|-----------|-------------|---------------------|
| **MARL Foundations** | Heterogeneity, parameter sharing, policy distance | [MADPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) ([paper](https://arxiv.org/abs/2401.11257)) (AAMAS'24 Oral), [HetDPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS) ([paper](https://arxiv.org/abs/2512.22941)) (AAMAS'26 Oral) |
| **Sparse Reward MARL** | Lazy agents, responsibility diffusion, curriculum learning | [LazyAgents](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) ([paper](https://proceedings.mlr.press/v202/liu23ac.html)) (ICML'23) |
| **LLM × MARL** | Fine-tuning LLMs with cooperative MARL, MoE PEFT | [CORY](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) ([paper](https://arxiv.org/abs/2410.06101)) (NeurIPS'24) |
| **MARL Platforms** | General simulation environments for MARL research | [Unreal-MAP](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP) ([paper](https://arxiv.org/abs/2503.15947)) (AAAI'26 Oral) |
| **Football AI** | VLM-based reward shaping, generative tactic discovery | [V-GEPF](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF) ([paper](https://arxiv.org/abs/2502.13430)) (AAAI'25), [TacEleven](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven) ([paper](https://arxiv.org/abs/2511.13326)) |
| **Hierarchical Agents** | Nested LM agents for complex long-horizon tasks | [agent-matrix](https://github.com/CASIA-Collect-AI/agent-matrix) |

---

## 📚 Some of the Representative Publications

### 2026

| Paper | Venue | Repo |
|-------|-------|------|
| **[Unreal-MAP](https://arxiv.org/abs/2503.15947)**: Unreal-Engine-Based General Platform for Multi-Agent RL | **AAAI 2026 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP) |
| **[HetDPS](https://arxiv.org/abs/2512.22941)**: Heterogeneity in Multi-Agent Reinforcement Learning | **AAMAS 2026 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS) |

### 2025

| Paper | Venue | Repo |
|-------|-------|------|
| **[TacEleven](https://arxiv.org/abs/2511.13326)**: Generative Tactic Discovery for Football Open Play | arXiv:2511.13326 | [→](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven) |
| **[V-GEPF](https://arxiv.org/abs/2502.13430)**: Vision-Based Generic Potential Function for Policy Alignment in MARL | **AAAI 2025** | [→](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF) |
| **[CoMoE](https://arxiv.org/abs/2505.17553)**: Contrastive Representation for MoE in Parameter-Efficient Fine-tuning | **EMNLP 2025** | — |
| [Cognition-Oriented Multiagent Reinforcement Learning](https://ieeexplore.ieee.org/document/10777850/) | **IEEE TNNLS** | — |
| [A Policy Resonance Approach to Solve Responsibility Diffusion in MARL](https://arxiv.org/abs/2208.07753) | **IEEE TNNLS** | — |
| [Self-Clustering Hierarchical MARL With Extensible Cooperation Graph](https://ieeexplore.ieee.org/document/10665939/) | **IEEE TETCI** | — |
| [Hybrid Actor-Critic for Physically Heterogeneous MARL](https://ieeexplore.ieee.org/document/11006503/) | **IEEE TCDS** | — |
| [Efficient Multitask RL via Task-Specific Action Correction](https://ieeexplore.ieee.org/document/10892354/) | **IEEE TCDS** | — |

### 2024

| Paper | Venue | Repo |
|-------|-------|------|
| **[CORY](https://arxiv.org/abs/2410.06101)**: Coevolving with the Other You — Fine-Tuning LLM with Sequential Cooperative MARL | **NeurIPS 2024** | [→](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) |
| **[MAPD](https://arxiv.org/abs/2401.11257)**: Measuring Policy Distance for Multi-Agent Reinforcement Learning | **AAMAS 2024 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) |
| [Orientation and Decision-Making for Soccer Based on Sports Analytics and AI](https://ieeexplore.ieee.org/document/10399370/) | **IEEE/CAA JAS** | — |
| [Fuzzy Feedback MARL for Adversarial Dynamic Multiteam Competitions](https://ieeexplore.ieee.org/document/10424698/) | **IEEE TFS** | — |
| [QFuture: Learning Future Expectation Cognition in MARL](https://ieeexplore.ieee.org/document/10372209/) | **IEEE TCDS** | — |
| [Long-Term and Short-Term Opponent Intention Inference for Football MARL](https://ieeexplore.ieee.org/document/10536732/) | **IEEE TCDS** | — |
| [Multiexperience-Assisted Efficient Multiagent Reinforcement Learning](https://ieeexplore.ieee.org/document/10098712/) | **IEEE TNNLS** | — |

### 2023

| Paper | Venue | Repo |
|-------|-------|------|
| **[Lazy Agents](https://proceedings.mlr.press/v202/liu23ac.html)**: A New Perspective on Solving Sparse Reward in MARL | **ICML 2023** | [→](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) |
| [Attention Enhanced Reinforcement Learning for Multi-Agent Cooperation](https://ieeexplore.ieee.org/document/9716772/) | **IEEE TNNLS** | — |
| [Deep RL for Multiagent Formation Control With Collision Avoidance](https://ieeexplore.ieee.org/document/10047984/) | **IEEE TSMC:S** | — |
| [Deep-RL-Based Multitarget Coverage With Connectivity Guaranteed](https://ieeexplore.ieee.org/document/9738445/) | **IEEE TII** | — |
| [Automatic Curriculum Learning for Large-Scale Cooperative MARL](https://ieeexplore.ieee.org/document/9919423/) | **IEEE TETCI** | — |
| [Cognition-Driven Multiagent Policy Learning for Promoting Cooperation](https://ieeexplore.ieee.org/document/9807394/) | **IEEE TG** | — |
| [Learning to Play Football From Sports Domain Perspective](https://ieeexplore.ieee.org/document/9893354/) | **IEEE TG** | — |

### 2022

| Paper | Venue |
|-------|-------|
| **[ConcNet](https://ojs.aaai.org/index.php/AAAI/article/view/21165)**: Concentration Network for RL of Large-Scale Multi-Agent Systems | **AAAI 2022** |
| [Multi-Target Encirclement with Collision Avoidance via Deep RL](https://ieeexplore.ieee.org/document/9812151/) | **ICRA 2022** |
| [Relative Distributed Formation and Obstacle Avoidance with Multi-Agent RL](https://ieeexplore.ieee.org/document/9812263/) | **ICRA 2022** |
| [Fixed-Time Adaptive Fuzzy Control for Uncertain Nonstrict-Feedback Systems](https://ieeexplore.ieee.org/document/9328286/) *(Highly Cited, WoS)* | **IEEE TFS** |

---

## 🗂️ Repository Index

| Repository | Topic | Paper |
|------------|-------|-------|
| [LLM-MARL-CORY](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) | LLM fine-tuning via cooperative MARL | NeurIPS 2024 |
| [LLM-Football-TacEleven](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven) | LLM-based generative football tactic discovery | arXiv 2025 |
| [MARL-Diversity-HetDPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS) | Heterogeneity & dynamic parameter sharing | AAMAS 2026 (Oral) |
| [MARL-Diversity-MADPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) | Policy distance metric for MARL | AAMAS 2024 (Oral) |
| [MARL-Environment-UnrealMAP](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP) | Unreal Engine MARL simulation platform | AAAI 2026 (Oral) |
| [MARL-Football-VGEPF](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF) | VLM-based reward shaping for football MARL | AAAI 2025 |
| [MARL-Reward-LazyAgents](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) | Sparse reward & lazy agent problem in MARL | ICML 2023 |
| [agent-matrix](https://github.com/CASIA-Collect-AI/agent-matrix) | Hierarchical nested LM agents (new project) | — |

---

## 📬 Contact

- **Prof. Zhiqiang Pu:** zhiqiang.pu@ia.ac.cn
- **Lab:** National Key Laboratory of Cognition and Decision Intelligence for Complex Systems, CASIA, Beijing
- **UCAS Profile:** [people.ucas.edu.cn/~pzq](https://people.ucas.edu.cn/~pzq)

---

<div align="center">
<sub>CASIA-Collect-AI curates and maintains open-source research code from the Unmanned Collective Intelligence Team at CASIA. All repos include bilingual (English/Chinese) documentation.</sub>
</div>
