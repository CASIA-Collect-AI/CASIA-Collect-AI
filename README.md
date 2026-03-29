<div align="center">

# CASIA-Collect-AI

**Intelligent Flight Technology Team**
Institute of Automation, Chinese Academy of Sciences (CASIA)

*Curating high-quality open-source research code in Multi-Agent RL, LLM, and Robotics*

[English](https://github.com/CASIA-Collect-AI/CASIA-Collect-AI/blob/main/README.md) | [中文](https://github.com/CASIA-Collect-AI/CASIA-Collect-AI/blob/main/README_CN.md)

[![GitHub](https://img.shields.io/badge/GitHub-CASIA--Collect--AI-181717?logo=github)](https://github.com/CASIA-Collect-AI)
[![Lab](https://img.shields.io/badge/CASIA-ia.cas.cn-blue)](https://www.ia.cas.cn)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Zhiqiang%20Pu-4285F4?logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=G4YHckgAAAAJ)
[![Contact](https://img.shields.io/badge/Contact-zhiqiang.pu%40ia.ac.cn-red)](mailto:zhiqiang.pu@ia.ac.cn)

</div>

---

## 👨‍🏫 About the Team

We are the **Intelligent Flight Technology Team (飞行器智能技术团队)**, led by **Prof. Zhiqiang Pu (蒲志强)** at the Institute of Automation, Chinese Academy of Sciences (CASIA).

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
| **MARL Foundations** | Heterogeneity, parameter sharing, policy distance | [MADPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) (AAMAS'24 Oral), [HetDPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS) (AAMAS'26 Oral) |
| **Sparse Reward MARL** | Lazy agents, responsibility diffusion, curriculum learning | [LazyAgents](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) (ICML'23) |
| **LLM × MARL** | Fine-tuning LLMs with cooperative MARL, MoE PEFT | [CORY](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) (NeurIPS'24) |
| **MARL Platforms** | General simulation environments for MARL research | [Unreal-MAP](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP) (AAAI'26 Oral) |
| **Football AI** | VLM-based reward shaping, generative tactic discovery | [V-GEPF](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF) (AAAI'25), [TacEleven](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven) |
| **Hierarchical Agents** | Nested LM agents for complex long-horizon tasks | [agent-matrix](https://github.com/CASIA-Collect-AI/agent-matrix) |

---

## 📚 Selected Publications (Recent 5 Years)

### 2026

| Paper | Venue | Repo |
|-------|-------|------|
| **Unreal-MAP**: Unreal-Engine-Based General Platform for Multi-Agent RL | **AAAI 2026 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP) |
| **HetDPS**: Heterogeneity in Multi-Agent Reinforcement Learning | **AAMAS 2026 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS) |

### 2025

| Paper | Venue | Repo |
|-------|-------|------|
| **TacEleven**: Generative Tactic Discovery for Football Open Play | arXiv:2511.13326 | [→](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven) |
| **V-GEPF**: Vision-Based Generic Potential Function for Policy Alignment in MARL | **AAAI 2025** | [→](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF) |
| **CoMoE**: Contrastive Representation for MoE in Parameter-Efficient Fine-tuning | **EMNLP 2025** | — |
| Cognition-Oriented Multiagent Reinforcement Learning | **IEEE TNNLS** | — |
| A Policy Resonance Approach to Solve Responsibility Diffusion in MARL | **IEEE TNNLS** | — |
| Self-Clustering Hierarchical MARL With Extensible Cooperation Graph | **IEEE TETCI** | — |
| Hybrid Actor-Critic for Physically Heterogeneous MARL | **IEEE TCDS** | — |
| Efficient Multitask RL via Task-Specific Action Correction | **IEEE TCDS** | — |

### 2024

| Paper | Venue | Repo |
|-------|-------|------|
| **CORY**: Coevolving with the Other You — Fine-Tuning LLM with Sequential Cooperative MARL | **NeurIPS 2024** | [→](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) |
| **MAPD**: Measuring Policy Distance for Multi-Agent Reinforcement Learning | **AAMAS 2024 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) |
| Orientation and Decision-Making for Soccer Based on Sports Analytics and AI | **IEEE/CAA JAS** | — |
| Fuzzy Feedback MARL for Adversarial Dynamic Multiteam Competitions | **IEEE TFS** | — |
| QFuture: Learning Future Expectation Cognition in MARL | **IEEE TCDS** | — |
| Long-Term and Short-Term Opponent Intention Inference for Football MARL | **IEEE TCDS** | — |
| Multiexperience-Assisted Efficient Multiagent Reinforcement Learning | **IEEE TNNLS** | — |

### 2023

| Paper | Venue | Repo |
|-------|-------|------|
| **Lazy Agents**: A New Perspective on Solving Sparse Reward in MARL | **ICML 2023** | [→](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) |
| Attention Enhanced Reinforcement Learning for Multi-Agent Cooperation | **IEEE TNNLS** | — |
| Deep RL for Multiagent Formation Control With Collision Avoidance | **IEEE TSMC:S** | — |
| Deep-RL-Based Multitarget Coverage With Connectivity Guaranteed | **IEEE TII** | — |
| Automatic Curriculum Learning for Large-Scale Cooperative MARL | **IEEE TETCI** | — |
| Cognition-Driven Multiagent Policy Learning for Promoting Cooperation | **IEEE TG** | — |
| Learning to Play Football From Sports Domain Perspective | **IEEE TG** | — |

### 2022

| Paper | Venue |
|-------|-------|
| **ConcNet**: Concentration Network for RL of Large-Scale Multi-Agent Systems | **AAAI 2022** |
| Multi-Target Encirclement with Collision Avoidance via Deep RL | **ICRA 2022** |
| Relative Distributed Formation and Obstacle Avoidance with Multi-Agent RL | **ICRA 2022** |
| Fixed-Time Adaptive Fuzzy Control for Uncertain Nonstrict-Feedback Systems *(Highly Cited, WoS)* | **IEEE TFS** |

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

## 🏆 Awards & Recognition

**Competition Awards**
- 🥇 **Special Prize** — 1st National Collect-AI Technology Challenge (全国群体智能技术挑战赛特等奖), 2023
- 🥇 **1st Place (Heterogeneous Track)** — 2nd National Multi-Agent Adversarial Gaming Challenge (全国多智能体对抗博弈挑战赛异构赛道第一名), 2020
- 🥈 **2nd Place (Homogeneous Track)** — 2nd National Multi-Agent Adversarial Gaming Challenge, 2020

**Academic Awards**
- 🏅 **CAAI Natural Science Award, 2nd Prize** — "Self-Learning Optimization Theory and Methods" (中国人工智能学会自然科学二等奖), 2024
- 📄 **F-5000 Top Academic Paper** — "Knowledge-Data Collaborative Intelligence Decision-Making" (中国科技期刊卓越行动计划高被引论文)
- 📄 **Web of Science Highly Cited Paper** — "Fixed-Time Adaptive Fuzzy Control..." (IEEE TFS, 2022)
- 🏆 **Best Paper Award** — 5th CCSICC International Conference

**Talent Programs**
- 🌟 **NSFC Excellent Young Scientists Fund** (国家自然科学基金优秀青年科学基金)
- 🌟 **Beijing Nova Program — Innovation Star** (北京市科技新星·创新新星, 2022)
- 🌟 **CAS Distinguished Research Fellow** (中科院特聘研究骨干)
- 🌟 **CAS Youth Innovation Promotion Association Member** (中科院青促会会员)
- 🏅 **CICC Youth Outstanding Talent Award** (中国指挥与控制学会青年才俊奖)

---

## 📬 Contact

- **Prof. Zhiqiang Pu:** zhiqiang.pu@ia.ac.cn
- **Lab:** National Key Laboratory of Cognition and Decision Intelligence for Complex Systems, CASIA, Beijing
- **UCAS Profile:** [people.ucas.edu.cn/~pzq](https://people.ucas.edu.cn/~pzq)
- **Google Scholar:** [Zhiqiang Pu](https://scholar.google.com/citations?user=G4YHckgAAAAJ)
- **ORCID:** [0000-0002-4841-4048](https://orcid.org/0000-0002-4841-4048)

---

<div align="center">
<sub>CASIA-Collect-AI curates and maintains open-source research code from the Intelligent Flight Technology Team at CASIA. All repos include bilingual (English/Chinese) documentation.</sub>
</div>
