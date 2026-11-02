---
title: "MemT-1.0"
date: 2026-10-19
summary: "Technical Advisor · RL Lead — memory-native foundation models (Nano 36B-A3B / Flash 288B-A17B); 100K+ downloads in the first week"
tags:
  - Agent Memory
  - Foundation Models
links:
  - type: site
    url: https://huggingface.co/MemTensor/MemT-1.0-Nano
  - type: code
    url: https://github.com/MemTensor/MemT-1.0
---

🧠 **My role: Technical Advisor, leading the reinforcement-learning stage**

[![Stars](https://img.shields.io/github/stars/MemTensor/MemT-1.0?style=social)](https://github.com/MemTensor/MemT-1.0) · `100K+ Downloads in Week 1`

MemT-1.0 makes memory an intrinsic part of the model's computation rather than an external retrieval step: a dynamic local memory and a trainable hyper-memory consolidate past interactions into a fixed-size persistent memory state, so the model can draw on prior sessions without re-reading the original text at inference time.

**Key results:**
- ⚡ At a 128K history length, Nano achieves about a 1.86× end-to-end inference speedup and a 66× reduction in persistent storage compared with a full-context KV cache
- 📈 Outperforms parametric-memory baselines on average, stays competitive with retrieval-augmented methods, and largely preserves general capabilities
- 📦 Open-sourced in Oct. 2026 with two models (Nano 36B-A3B, Flash 288B-A17B) and a 66-page technical report; 100K+ downloads within one week of release

<!--more-->
