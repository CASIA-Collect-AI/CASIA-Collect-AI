<div align="center">

# CASIA-Collect-AI

**飞行器智能技术团队**
中国科学院自动化研究所

*收录和维护多智能体强化学习、大语言模型与机器人领域高质量开源研究代码*

[English](https://github.com/CASIA-Collect-AI/CASIA-Collect-AI/blob/main/README.md) | [中文](https://github.com/CASIA-Collect-AI/CASIA-Collect-AI/blob/main/README_CN.md)

[![GitHub](https://img.shields.io/badge/GitHub-CASIA--Collect--AI-181717?logo=github)](https://github.com/CASIA-Collect-AI)
[![Lab](https://img.shields.io/badge/CASIA-ia.cas.cn-blue)](https://www.ia.cas.cn)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-蒲志强-4285F4?logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=G4YHckgAAAAJ)
[![Contact](https://img.shields.io/badge/联系-zhiqiang.pu%40ia.ac.cn-red)](mailto:zhiqiang.pu@ia.ac.cn)

</div>

---

## 👨‍🏫 团队介绍

我们是**飞行器智能技术团队**，由中国科学院自动化研究所**蒲志强研究员**领衔。

**CASIA-Collect-AI** 是本团队的开源代码收录平台，面向 MARL、LLM 及机器人领域，系统整理和维护团队及合作者的高质量研究代码。

本团队隶属**认知与决策智能全国重点实验室**（蒲志强担任副主任），同时依托中国科学院大学人工智能学院开展博士研究生培养工作。

主要研究方向：
- 🤖 **多智能体强化学习（MARL）** — 合作式、异构、大规模集群系统
- 🧠 **LLM × MARL** — 基于强化学习的大模型微调、对齐与参数高效方法
- ⚽ **足球 / 体育 AI** — 数据驱动的战术生成、VLM 引导的策略对齐
- 🚁 **自主无人系统** — 无人机编队控制、非线性飞行控制

---

## 🔬 研究方向

| 方向 | 说明 | 代表工作 |
|------|------|---------|
| **MARL 基础理论** | 异构性、参数共享、策略距离度量 | [MADPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS)（AAMAS'24 Oral）、[HetDPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS)（AAMAS'26 Oral） |
| **稀疏奖励 MARL** | 懒惰智能体、责任扩散、课程学习 | [LazyAgents](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents)（ICML'23） |
| **LLM × MARL** | 协作式 MARL 微调 LLM、MoE 参数高效微调 | [CORY](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY)（NeurIPS'24） |
| **MARL 仿真平台** | 通用多智能体强化学习实验环境 | [Unreal-MAP](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP)（AAAI'26 Oral） |
| **足球 AI** | VLM 奖励塑造、生成式战术发现 | [V-GEPF](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF)（AAAI'25）、[TacEleven](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven） |
| **层级智能体** | 嵌套语言模型智能体，面向长时序复杂任务 | [agent-matrix](https://github.com/CASIA-Collect-AI/agent-matrix) |

---

## 📚 代表性论文（近五年）

### 2026

| 论文 | 发表期刊/会议 | 仓库 |
|------|-------------|------|
| **Unreal-MAP**：基于虚幻引擎的通用 MARL 平台 | **AAAI 2026 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP) |
| **HetDPS**：多智能体强化学习中的异构性 | **AAMAS 2026 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS) |

### 2025

| 论文 | 发表期刊/会议 | 仓库 |
|------|-------------|------|
| **TacEleven**：足球开放性战术的生成式发现 | arXiv:2511.13326 | [→](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven) |
| **V-GEPF**：基于视觉的通用势函数在 MARL 策略对齐中的应用 | **AAAI 2025** | [→](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF) |
| **CoMoE**：参数高效微调中混合专家的对比表示学习 | **EMNLP 2025** | — |
| 面向认知的多智能体强化学习 | **IEEE TNNLS** | — |
| 策略共振方法解决 MARL 中的责任扩散问题 | **IEEE TNNLS** | — |
| 基于可扩展协作图的自聚类层级 MARL | **IEEE TETCI** | — |
| 物理异构多智能体 RL 的混合 Actor-Critic | **IEEE TCDS** | — |
| 基于任务特定动作校正的高效多任务强化学习 | **IEEE TCDS** | — |

### 2024

| 论文 | 发表期刊/会议 | 仓库 |
|------|-------------|------|
| **CORY**：与另一个你共同进化——序列协作 MARL 微调 LLM | **NeurIPS 2024** | [→](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) |
| **MAPD**：面向多智能体强化学习的策略距离度量 | **AAMAS 2024 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) |
| 基于体育分析与 AI 的足球决策综述 | **IEEE/CAA JAS** | — |
| 面向对抗多团队博弈的模糊反馈 MARL | **IEEE TFS** | — |
| QFuture：多智能体 RL 中的未来期望认知学习 | **IEEE TCDS** | — |
| 足球多人策略学习中的长短期意图推断 | **IEEE TCDS** | — |
| 基于多经验辅助的高效多智能体强化学习 | **IEEE TNNLS** | — |

### 2023

| 论文 | 发表期刊/会议 | 仓库 |
|------|-------------|------|
| **Lazy Agents**：解决 MARL 稀疏奖励问题的新视角 | **ICML 2023** | [→](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) |
| 注意力增强的多智能体合作强化学习 | **IEEE TNNLS** | — |
| 基于深度 RL 的多智能体避障编队控制 | **IEEE TSMC:S** | — |
| 基于深度 RL 的保连通多目标覆盖 | **IEEE TII** | — |
| 大规模协作 MARL 自动课程学习 | **IEEE TETCI** | — |
| 面向合作促进的多智能体认知驱动策略学习 | **IEEE TG** | — |
| 基于体育领域知识的足球强化学习 | **IEEE TG** | — |

### 2022

| 论文 | 发表期刊/会议 |
|------|-------------|
| **ConcNet**：大规模多智能体系统强化学习的聚焦网络 | **AAAI 2022** |
| 基于深度 RL 的多目标包围与避碰 | **ICRA 2022** |
| 多智能体相对分布式编队与障碍规避 RL | **ICRA 2022** |
| 不确定非严格反馈系统的固定时间自适应模糊控制 *（Web of Science 高被引）* | **IEEE TFS** |

---

## 🗂️ 仓库索引

| 仓库 | 研究方向 | 对应论文 |
|------|---------|---------|
| [LLM-MARL-CORY](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) | 协作式 MARL 微调大语言模型 | NeurIPS 2024 |
| [LLM-Football-TacEleven](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven) | LLM 驱动的生成式足球战术发现 | arXiv 2025 |
| [MARL-Diversity-HetDPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS) | 异构性度量与动态参数共享 | AAMAS 2026 (Oral) |
| [MARL-Diversity-MADPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) | 多智能体策略距离度量 | AAMAS 2024 (Oral) |
| [MARL-Environment-UnrealMAP](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP) | 虚幻引擎 MARL 仿真平台 | AAAI 2026 (Oral) |
| [MARL-Football-VGEPF](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF) | VLM 奖励塑造用于足球 MARL 策略对齐 | AAAI 2025 |
| [MARL-Reward-LazyAgents](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) | MARL 稀疏奖励与懒惰智能体问题 | ICML 2023 |
| [agent-matrix](https://github.com/CASIA-Collect-AI/agent-matrix) | 层级嵌套语言模型智能体（新项目） | — |

---

## 🏆 所获奖励

**竞赛获奖**
- 🥇 **特等奖** — 2023 年全国群体智能技术挑战赛（指导教师）
- 🥇 **第一名（异构赛道）** — 第二届全国多智能体对抗博弈挑战赛，2020
- 🥈 **第二名（同构赛道）** — 第二届全国多智能体对抗博弈挑战赛，2020

**学术奖励**
- 🏅 **中国人工智能学会自然科学二等奖** — "自学习优化理论与方法"，2024
- 📄 **F-5000 卓越论文** — "知识和数据协同驱动的群体智能决策方法研究综述"（中国科技期刊卓越行动计划）
- 📄 **Web of Science 高被引论文** — "Fixed-Time Adaptive Fuzzy Control..."（IEEE TFS，2022）
- 🏆 **最佳论文奖** — 第五届 CCSICC 国际会议

**人才计划**
- 🌟 **国家自然科学基金优秀青年科学基金**获得者
- 🌟 **北京市科技新星·创新新星**（2022 年，编号 2022129）
- 🌟 **中科院特聘研究骨干**
- 🌟 **中国科学院青年创新促进会**会员
- 🏅 **中国指挥与控制学会青年才俊奖**

---

## 📬 联系方式

- **蒲志强研究员：** zhiqiang.pu@ia.ac.cn
- **实验室：** 认知与决策智能全国重点实验室，中国科学院自动化研究所，北京
- **中科院大学主页：** [people.ucas.edu.cn/~pzq](https://people.ucas.edu.cn/~pzq)
- **Google Scholar：** [蒲志强](https://scholar.google.com/citations?user=G4YHckgAAAAJ)
- **ORCID：** [0000-0002-4841-4048](https://orcid.org/0000-0002-4841-4048)

---

<div align="center">
<sub>CASIA-Collect-AI 收录和维护中科院自动化所飞行器智能技术团队的开源研究代码，所有仓库均提供中英双语文档。</sub>
</div>
