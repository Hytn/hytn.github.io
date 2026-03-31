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
        about: ''
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
        我关注如何构建能够自动完成科研、工程与开发等长期复杂任务的人工智能系统。我的一个核心目标，是让数据驱动的科学研究变得更高效、更可靠，也更具生产力。围绕这一目标，我目前主要聚焦三个彼此关联的方向：

        🧪 **AI4Research** —— 我构建能够进行文献检索、实验设计、数据分析、假设生成与验证的 AI 科研助手。

        🤖 **自主智能体** —— 我研究具备环境感知、记忆、规划与工具调用能力的智能体模型与系统，并以大语言模型作为核心智能引擎。

        🧠 **基础模型** —— 我探索通用模型的训练与适配，包括语言理解与生成、知识表征、多模态融合以及下游泛化。
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: '📄 代表性论文'
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
        我的开源工作围绕 **LLM 驱动的智能体** 形成了较完整的生态链：**数据**（AgentCPM-GUI）→ **算法**（AgentRL, AgentCPM-Explore, MiniCPM4-MCP）→ **执行**（RD-Agent）→ **评测**（ToLeaP）。
      count: 0
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
  - block: markdown
    id: service
    content:
      title: '🎓 学术服务'
      subtitle: ''
      text: |-
        🧑‍🏫 **学生指导** —— 我共同指导本科生、硕士生和博士生开展 LLM 智能体与数据挖掘研究。

        📝 **会议审稿** —— 我长期为 NeurIPS、ICLR、EMNLP、KDD、WWW、COLING 等会议审稿。

        📰 **期刊审稿** —— 我也为 TKDE、Science China、AI Open 等期刊审稿。

        🎤 **邀请报告** —— 近期邀请报告包括 “Autonomous Agents and Tool Learning with LLMs”（RLChina 2025）与 “LLM-Driven Autonomous Agents”（Huawei OpenHarmony AI Agent TSG）。

        💰 **主持科研项目** —— 我目前主持中国博士后科学基金面上资助与国家资助博士后研究人员计划 C 档项目。
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
