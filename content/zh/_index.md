---
title: ''
summary: ''
date: 2024-10-24
type: landing

design:
  spacing: '3rem'

sections:
  - block: resume-biography-3
    content:
      username: me_zh
      text: ''
      headings:
        about: '个人简介'
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: resume-experience
    id: experience
    content:
      username: me_zh
    design:
      date_format: '2006年1月'
      is_education_first: false
  - block: markdown
    content:
      title: '🔬 研究方向'
      subtitle: ''
      text: |-
        我关注如何构建能够自动完成科研、工程与开发等长期复杂任务的人工智能系统。我的一个核心目标，是让数据驱动的科学研究变得更高效、更可靠，也更具生产力。围绕这一目标，我目前主要聚焦四个彼此关联的方向：

        🧪 **AI4Research / AI4AI** —— 我构建能够进行文献检索、实验设计、数据分析、假设生成与验证的 AI 科研助手，并研究如何用 AI 系统改进 AI 自身的研发过程。

        🤖 **自主智能体与大模型后训练** —— 我研究具备环境感知、记忆、规划与工具调用能力的智能体模型与系统，并通过智能体强化学习对端侧小模型（1B–8B）进行后训练，让小模型完成以往只有闭源前沿模型才能完成的长程任务。

        🧠 **智能体记忆与持续学习** —— 我研究记忆原生基座模型与可学习的动态记忆操作，让智能体能够沉淀经验、跨任务复用并持续学习与演化。

        🏗️ **基础模型** —— 我探索通用模型的训练与适配，包括语言理解与生成、知识表征、多模态融合以及下游泛化。
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: '📄 代表性论文'
      count: 6
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: '📚 全部论文'
      text: ''
      count: 0
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: '💻 开源项目'
      text: |-
        我的开源工作围绕 **LLM 驱动的智能体** 形成了较完整的生态链：**数据**（AgentCPM-GUI）→ **算法**（AgentRL, AgentCPM-Explore, MiniCPM4-MCP, MiniCPM5）→ **记忆**（MemT-1.0, AtomMem）→ **执行**（RD-Agent）→ **评测**（ToLeaP）。这些项目累计获得 **4 万+ GitHub 星标** 与 **700 万+ 模型下载**。
      count: 0
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
      show_date: false
      show_read_time: false
  - block: markdown
    id: service
    content:
      title: '🎓 学术服务'
      subtitle: ''
      text: |-
        🧑‍🏫 **学生指导** —— 我共同指导本科生、硕士生和博士生开展 LLM 智能体与大模型后训练研究。

        🧭 **领域主席** —— ACL（Area Chair）。

        📝 **会议审稿** —— 我长期为 NeurIPS、ICLR、EMNLP、KDD、WWW、COLING 等会议审稿。

        📰 **期刊审稿** —— 我也为 TKDE、Science China、AI Open 等期刊审稿。

        🏛️ **学术兼职** —— 中国计算机学会（CCF）理论计算机科学专业委员会委员。

        🎤 **邀请报告** —— 《面向长程复杂任务的端侧智能体后训练方法》（RLChina 2026）、《迈向智能体 2.0 时代》（SMP 2026）、“Autonomous Agents and Tool Learning with LLMs”（RLChina 2025）、“LLM-Driven Autonomous Agents”（Huawei OpenHarmony AI Agent TSG）。

        💰 **主持科研项目** —— 我主持国家自然科学基金青年科学基金项目（C 类）、中国博士后科学基金面上资助与国家资助博士后研究人员计划 C 档项目。
    design:
      columns: '1'
  - block: markdown
    id: contact
    content:
      title: '📬 联系方式'
      subtitle: ''
      text: |-
        欢迎就研究问题、合作想法或开源项目与我联系。

        ✉️ **邮箱：** [haotian.chen@163.com](mailto:haotian.chen@163.com) / [ht1ian.chen@gmail.com](mailto:ht1ian.chen@gmail.com)

        🐙 **GitHub：** [github.com/Hytn](https://github.com/Hytn)

        ✖️ **X：** [@HytnChen](https://x.com/HytnChen)

        🎓 **Google Scholar：** [scholar profile](https://scholar.google.com/citations?user=nwU3FhUAAAAJ&hl=zh-CN)
    design:
      columns: '1'
---
