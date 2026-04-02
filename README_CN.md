<div align="center">

# CASIA-Collect-AI

**无人集群智能团队**
中国科学院自动化研究所

*收录和维护多智能体强化学习、大语言模型与机器人领域高质量开源研究代码*

[English](https://github.com/CASIA-Collect-AI/CASIA-Collect-AI/blob/main/README.md) | [中文](https://github.com/CASIA-Collect-AI/CASIA-Collect-AI/blob/main/README_CN.md)

[![GitHub](https://img.shields.io/badge/GitHub-CASIA--Collect--AI-181717?logo=github)](https://github.com/CASIA-Collect-AI)
[![Lab](https://img.shields.io/badge/CASIA-ia.cas.cn-blue)](https://www.ia.cas.cn)
[![Contact](https://img.shields.io/badge/联系-zhiqiang.pu%40ia.ac.cn-red)](mailto:zhiqiang.pu@ia.ac.cn)

</div>

---

## 👨‍🏫 团队介绍

我们是**无人集群智能团队**，由中国科学院自动化研究所**蒲志强研究员**领衔。

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
| **MARL 基础理论** | 异构性、参数共享、策略距离度量 | [MADPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS)（[论文](https://arxiv.org/abs/2401.11257)）（AAMAS'24 Oral）、[HetDPS](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS)（[论文](https://arxiv.org/abs/2512.22941)）（AAMAS'26 Oral） |
| **稀疏奖励 MARL** | 懒惰智能体、责任扩散、课程学习 | [LazyAgents](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents)（[论文](https://proceedings.mlr.press/v202/liu23ac.html)）（ICML'23） |
| **LLM × MARL** | 协作式 MARL 微调 LLM、MoE 参数高效微调 | [CORY](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY)（[论文](https://arxiv.org/abs/2410.06101)）（NeurIPS'24） |
| **MARL 仿真平台** | 通用多智能体强化学习实验环境 | [Unreal-MAP](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP)（[论文](https://arxiv.org/abs/2503.15947)）（AAAI'26 Oral） |
| **足球 AI** | VLM 奖励塑造、生成式战术发现 | [V-GEPF](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF)（[论文](https://arxiv.org/abs/2502.13430)）（AAAI'25）、[TacEleven](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven)（[论文](https://arxiv.org/abs/2511.13326)） |
| **层级智能体** | 嵌套语言模型智能体，面向长时序复杂任务 | [agent-matrix](https://github.com/CASIA-Collect-AI/agent-matrix) |

---

## 📚 部分代表性论文

### 2026

| 论文 | 发表期刊/会议 | 仓库 |
|------|-------------|------|
| **[Unreal-MAP](https://arxiv.org/abs/2503.15947)**：基于虚幻引擎的通用 MARL 平台 | **AAAI 2026 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Environment-UnrealMAP) |
| **[HetDPS](https://arxiv.org/abs/2512.22941)**：多智能体强化学习中的异构性 | **AAMAS 2026 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Diversity-HetDPS) |

### 2025

| 论文 | 发表期刊/会议 | 仓库 |
|------|-------------|------|
| **[TacEleven](https://arxiv.org/abs/2511.13326)**：足球开放性战术的生成式发现 | arXiv:2511.13326 | [→](https://github.com/CASIA-Collect-AI/LLM-Football-TacEleven) |
| **[V-GEPF](https://arxiv.org/abs/2502.13430)**：基于视觉的通用势函数在 MARL 策略对齐中的应用 | **AAAI 2025** | [→](https://github.com/CASIA-Collect-AI/MARL-Football-VGEPF) |
| **[CoMoE](https://arxiv.org/abs/2505.17553)**：参数高效微调中混合专家的对比表示学习 | **EMNLP 2025** | — |
| [面向认知的多智能体强化学习](https://ieeexplore.ieee.org/document/10777850/) | **IEEE TNNLS** | — |
| [策略共振方法解决 MARL 中的责任扩散问题](https://arxiv.org/abs/2208.07753) | **IEEE TNNLS** | — |
| [基于可扩展协作图的自聚类层级 MARL](https://ieeexplore.ieee.org/document/10665939/) | **IEEE TETCI** | — |
| [物理异构多智能体 RL 的混合 Actor-Critic](https://ieeexplore.ieee.org/document/11006503/) | **IEEE TCDS** | — |
| [基于任务特定动作校正的高效多任务强化学习](https://ieeexplore.ieee.org/document/10892354/) | **IEEE TCDS** | — |

### 2024

| 论文 | 发表期刊/会议 | 仓库 |
|------|-------------|------|
| **[CORY](https://arxiv.org/abs/2410.06101)**：与另一个你共同进化——序列协作 MARL 微调 LLM | **NeurIPS 2024** | [→](https://github.com/CASIA-Collect-AI/LLM-MARL-CORY) |
| **[MAPD](https://arxiv.org/abs/2401.11257)**：面向多智能体强化学习的策略距离度量 | **AAMAS 2024 (Oral)** | [→](https://github.com/CASIA-Collect-AI/MARL-Diversity-MADPS) |
| [基于体育分析与 AI 的足球决策综述](https://ieeexplore.ieee.org/document/10399370/) | **IEEE/CAA JAS** | — |
| [面向对抗多团队博弈的模糊反馈 MARL](https://ieeexplore.ieee.org/document/10424698/) | **IEEE TFS** | — |
| [QFuture：多智能体 RL 中的未来期望认知学习](https://ieeexplore.ieee.org/document/10372209/) | **IEEE TCDS** | — |
| [足球多人策略学习中的长短期意图推断](https://ieeexplore.ieee.org/document/10536732/) | **IEEE TCDS** | — |
| [基于多经验辅助的高效多智能体强化学习](https://ieeexplore.ieee.org/document/10098712/) | **IEEE TNNLS** | — |

### 2023

| 论文 | 发表期刊/会议 | 仓库 |
|------|-------------|------|
| **[Lazy Agents](https://proceedings.mlr.press/v202/liu23ac.html)**：解决 MARL 稀疏奖励问题的新视角 | **ICML 2023** | [→](https://github.com/CASIA-Collect-AI/MARL-Reward-LazyAgents) |
| [注意力增强的多智能体合作强化学习](https://ieeexplore.ieee.org/document/9716772/) | **IEEE TNNLS** | — |
| [基于深度 RL 的多智能体避障编队控制](https://ieeexplore.ieee.org/document/10047984/) | **IEEE TSMC:S** | — |
| [基于深度 RL 的保连通多目标覆盖](https://ieeexplore.ieee.org/document/9738445/) | **IEEE TII** | — |
| [大规模协作 MARL 自动课程学习](https://ieeexplore.ieee.org/document/9919423/) | **IEEE TETCI** | — |
| [面向合作促进的多智能体认知驱动策略学习](https://ieeexplore.ieee.org/document/9807394/) | **IEEE TG** | — |
| [基于体育领域知识的足球强化学习](https://ieeexplore.ieee.org/document/9893354/) | **IEEE TG** | — |

### 2022

| 论文 | 发表期刊/会议 |
|------|-------------|
| **[ConcNet](https://ojs.aaai.org/index.php/AAAI/article/view/21165)**：大规模多智能体系统强化学习的聚焦网络 | **AAAI 2022** |
| [基于深度 RL 的多目标包围与避碰](https://ieeexplore.ieee.org/document/9812151/) | **ICRA 2022** |
| [多智能体相对分布式编队与障碍规避 RL](https://ieeexplore.ieee.org/document/9812263/) | **ICRA 2022** |
| [不确定非严格反馈系统的固定时间自适应模糊控制](https://ieeexplore.ieee.org/document/9328286/) *（Web of Science 高被引）* | **IEEE TFS** |

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

## 📬 联系方式

- **蒲志强研究员：** zhiqiang.pu@ia.ac.cn
- **实验室：** 认知与决策智能全国重点实验室，中国科学院自动化研究所，北京
- **中科院大学主页：** [people.ucas.edu.cn/~pzq](https://people.ucas.edu.cn/~pzq)

---

<div align="center">
<sub>CASIA-Collect-AI 收录和维护中科院自动化所无人集群智能团队的开源研究代码，所有仓库均提供中英双语文档。</sub>
</div>
