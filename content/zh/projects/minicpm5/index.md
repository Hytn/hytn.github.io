---
title: "MiniCPM5 (1B / 2B)"
# 日期仅用于项目网格排序（页面不显示日期），可按实际发布月份调整。
date: 2026-07-01
summary: "智能体能力负责人 — 开源端侧大模型（1B / 2B），我端到端构建了其智能体能力；累计下载 690 万+"
tags:
  - Foundation Models
  - Autonomous Agents
links:
  - type: site
    url: https://huggingface.co/openbmb/MiniCPM5-2B
  - type: code
    url: https://github.com/OpenBMB/MiniCPM
---

🏆 **我的角色：智能体能力负责人**

[![Stars](https://img.shields.io/github/stars/OpenBMB/MiniCPM?style=social)](https://github.com/OpenBMB/MiniCPM) · `690 万+ 下载量`

MiniCPM5 是面向端侧部署与资源受限场景的开源大模型系列，原生支持 128K 长上下文并兼容主流推理引擎。我负责该系列模型智能体能力的整体构建：工具调用与多轮交互数据的构造、智能体强化学习训练以及评测体系搭建。

**核心成果：**
- 🥇 2B 模型在 BFCL v4、τ²-Bench、SWE-bench Verified、GAIA 等智能体基准上取得同尺寸领先水平，综合平均分超过更大尺寸的 Qwen3.5-4B
- 📦 MiniCPM5-1B 与 MiniCPM5-2B（含 GGUF / MLX 版本）在 Hugging Face 的累计下载量各约 345 万次，合计超过 690 万次
- 🔌 提供 OpenAI 兼容的工具调用解析器与面向编码智能体的 Agent Skills

<!--more-->
