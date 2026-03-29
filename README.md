<div align="center">

# CASIA-Collect-AI

**Intelligent Flight Technology Team (Swarm Intelligence Group)**
Institute of Automation, Chinese Academy of Sciences (CASIA)

*Curating high-quality open-source research code in Multi-Agent RL, LLM, and Robotics*

[![GitHub Org](https://img.shields.io/badge/GitHub-CASIA--Collect--AI-181717?logo=github)](https://github.com/CASIA-Collect-AI)
[![Lab](https://img.shields.io/badge/CASIA-ia.cas.cn-blue)](https://www.ia.cas.cn)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Zhiqiang%20Pu-4285F4?logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=G4YHckgAAAAJ)
[![Contact](https://img.shields.io/badge/Contact-zhiqiang.pu%40ia.ac.cn-red)](mailto:zhiqiang.pu@ia.ac.cn)

</div>

---

## 👨‍🏫 About the Team

We are the **Intelligent Flight Technology Team (飞行器智能技术团队)**, also known as the **Swarm Intelligence Group (群体智能团队)**, led by **Prof. Zhiqiang Pu (蒲志强)** at the Institute of Automation, Chinese Academy of Sciences (CASIA).

Our group is affiliated with the **National Key Laboratory of Cognition and Decision Intelligence for Complex Systems** (认知与决策智能全国重点实验室), where Prof. Pu serves as deputy director. We are also part of the School of Artificial Intelligence, University of Chinese Academy of Sciences (UCAS).

Our research operates at the intersection of:
- 🤖 **Multi-Agent Reinforcement Learning (MARL)** — cooperative, heterogeneous, large-scale
- 🧠 **LLM Fine-tuning via MARL** — RL-based alignment, policy optimization for language models
- ⚽ **Football/Sports AI** — data-driven tactic generation and analysis
- 🚁 **Autonomous Unmanned Systems** — UAV swarms, formation control, decision-making

---

## 🔬 Research Directions

| Direction | Description | Representative Work |
|-----------|-------------|---------------------|
| **MARL Foundations** | Heterogeneity, parameter sharing, policy distance | [MADPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) (AAMAS'24), [HetDPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS) (AAMAS'26 Oral) |
| **Sparse Reward MARL** | Lazy agents, responsibility diffusion | [LazyAgents](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) (ICML'23) |
| **LLM × MARL** | Fine-tuning LLMs with cooperative MARL, CoT alignment | [CORY](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) (NeurIPS'24) |
| **MARL Platforms** | General simulation environments for MARL research | [Unreal-MAP](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP) (AAAI'26 Oral) |
| **Football AI** | VLM-based reward shaping, generative tactic discovery | [V-GEPF](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF) (AAAI'25), [TacEleven](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven) |
| **Hierarchical Agents** | Nested LM agents for complex long-horizon tasks | [agent-matrix](https://github.com/CASIA-Collect-AI/agent-matrix) |

---

## 📚 Selected Publications

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
| **CoMoE**: Contrastive Representation for Mixture-of-Experts in Parameter-Efficient Fine-tuning | **EMNLP 2025** | — |

### 2024

| Paper | Venue | Repo |
|-------|-------|------|
| **CORY**: Coevolving with the Other You — Fine-Tuning LLM with Sequential Cooperative MARL | **NeurIPS 2024** | [→](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) |
| **MAPD**: Measuring Policy Distance for Multi-Agent Reinforcement Learning | **AAMAS 2024** | [→](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) |
| Orientation and Decision-Making for Soccer Based on Sports Analytics and AI | **IEEE/CAA JAS** | — |

### 2023

| Paper | Venue | Repo |
|-------|-------|------|
| **Lazy Agents**: A New Perspective on Solving Sparse Reward Problem in MARL | **ICML 2023** | [→](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) |

### 2022

| Paper | Venue |
|-------|-------|
| **ConcNet**: Concentration Network for RL of Large-Scale Multi-Agent Systems | **AAAI 2022** |
| Multi-Target Encirclement with Collision Avoidance via Deep RL | **ICRA 2022** |
| Relative Distributed Formation and Obstacle Avoidance with Multi-Agent RL | **ICRA 2022** |

---

## 🗂️ Repository Index

| Repository | Topic | Paper |
|------------|-------|-------|
| [LLM-MARL-CORY](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) | LLM fine-tuning via cooperative MARL | NeurIPS 2024 |
| [LLM-Football-TacEleven](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven) | LLM-based football tactic discovery | arXiv 2025 |
| [MARL-Diversity-HetDPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS) | Heterogeneity & dynamic parameter sharing | AAMAS 2026 (Oral) |
| [MARL-Diversity-MADPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) | Policy distance metric for MARL | AAMAS 2024 |
| [MARL-Environment-UnrealMAP](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP) | Unreal Engine MARL simulation platform | AAAI 2026 (Oral) |
| [MARL-Football-VGEPF](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF) | VLM-based reward shaping for football MARL | AAAI 2025 |
| [MARL-Reward-LazyAgents](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) | Sparse reward & lazy agent problem in MARL | ICML 2023 |
| [agent-matrix](https://github.com/CASIA-Collect-AI/agent-matrix) | Hierarchical nested LM agents (new project) | — |

---

## 👥 Team Members

**Principal Investigator**

| Name | Role | Email |
|------|------|-------|
| **Zhiqiang Pu (蒲志强)** | Full Professor, Deputy Director of National Key Lab | zhiqiang.pu@ia.ac.cn |

**Graduate Students & Researchers** (partial list of co-authors)

| Name | Representative Work |
|------|---------------------|
| Tianyi Hu (胡天一) | NeurIPS'24 (CORY), AAMAS'24 (MADPS), AAMAS'26 (HetDPS), AAAI'26 (Unreal-MAP) |
| Hao Ma (马昊) | NeurIPS'24 (CORY), AAAI'25 (V-GEPF), arXiv (TacEleven) |
| Siyao Zhao (赵思遥) | arXiv (TacEleven), AAAI'25 (V-GEPF) |
| Boyin Liu (刘博印) | ICML'23 (Lazy Agents), NeurIPS'24 (CORY) |
| Qingxu Fu (付庆旭) | AAAI'22 (ConcNet), ICRA'22, AAAI'26 (Unreal-MAP) |
| Tenghai Qiu (仇腾海) | AAAI'22, AAMAS'24, AAAI'26, EMNLP'25 |
| Jinyuan Feng (冯锦源) | EMNLP'25 (CoMoE) |
| Yuan Wang (王苑) | AAAI'26 (Unreal-MAP), AAMAS'26 (HetDPS) |
| Shijie Wang (王士杰) | AAAI'25 (V-GEPF), arXiv (TacEleven) |
| Xiaolin Ai (艾晓林) | AAMAS'24, NeurIPS'24 (CORY), AAAI'25 (V-GEPF) |

---

## 🏆 Awards & Recognition

- 🥇 **1st Place** — 2023 National Swarm Intelligence Technology Challenge (全国群体智能技术挑战赛)
- 🥇 **1st Place** — 2021 National Aerial Game Competition (全国空中博弈大赛)
- 🏅 **Wu Wenjun AI Science & Technology Award** — Natural Science Second Prize (吴文俊人工智能科学技术奖)
- 🏅 **China Aeronautical Society Li Ming Young Talents Award** (李明青年人才奖)

---

## 📬 Contact

- **Prof. Zhiqiang Pu:** zhiqiang.pu@ia.ac.cn
- **Lab:** National Key Laboratory of Cognition and Decision Intelligence for Complex Systems, CASIA, Beijing
- **UCAS Profile:** [people.ucas.edu.cn/~pzq](https://people.ucas.edu.cn/~pzq)
- **Google Scholar:** [Zhiqiang Pu](https://scholar.google.com/citations?user=G4YHckgAAAAJ)

---

<div align="center">
<sub>This organization curates and maintains open-source research code from the Intelligent Flight Technology Team at CASIA. All repos include bilingual (English/Chinese) documentation.</sub>
</div>
