---
title: "MemT-1.0"
date: 2026-10-19
summary: "技术顾问 · 负责强化学习 — 记忆原生基座模型（Nano 36B-A3B / Flash 288B-A17B），开源一周下载 10 万+"
tags:
  - Agent Memory
  - Foundation Models
links:
  - type: site
    url: https://huggingface.co/MemTensor/MemT-1.0-Nano
  - type: code
    url: https://github.com/MemTensor/MemT-1.0
---

🧠 **我的角色：技术顾问，负责模型的强化学习部分**

[![Stars](https://img.shields.io/github/stars/MemTensor/MemT-1.0?style=social)](https://github.com/MemTensor/MemT-1.0) · `开源一周下载 10 万+`

MemT-1.0 将记忆作为模型固有的计算能力而非外部检索：通过动态局部记忆与可训练的超记忆（hyper memory），在固定大小的持久记忆状态中沉淀历史交互，推理时无需重读原始文本即可跨会话调用过往信息。

**核心成果：**
- ⚡ 在 128K 历史长度下，Nano 模型相比全上下文 KV 缓存实现约 1.86 倍端到端推理加速与 66 倍持久化存储压缩
- 📈 在参数化记忆基线上平均领先，与检索增强方法持平，并基本保持通用能力
- 📦 2026 年 10 月开源 Nano（36B-A3B）与 Flash（288B-A17B）两个模型及 66 页技术报告，发布一周下载量突破 10 万次

<!--more-->
