---
title: ''
summary: ''
date: 2024-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: markdown
    content:
      title: '陈颢天'
      subtitle: '上海交通大学人工智能学院助理研究员'
      text: |-
        ![](/media/authors/me.jpg)

        陈颢天现任**上海交通大学人工智能学院助理研究员**，在 [RethinkLab](https://thinklab.sjtu.edu.cn/index.html) 与 [严骏驰](https://thinklab.sjtu.edu.cn/index.html) 教授合作开展研究。

        他的研究目标是理解并发展能够自动完成长期、复杂、需要大量时间投入甚至创造性思考任务的人工智能系统，重点关注**自主智能体**、**大语言模型**与 **AI4Research**。

        他于**复旦大学**获得数据科学博士学位，并在**清华大学 THUNLP** 开展博士后研究，与 [刘知远](https://nlp.csai.tsinghua.edu.cn/~lzy/) 教授和 [孙茂松](https://nlp.csai.tsinghua.edu.cn/staff/sms/) 教授合作。他也曾在**微软亚洲研究院**担任科研实习生，参与研发的 RD-Agent 登上微软 Build 2025 全球 Keynote。

        **邮箱：** [htchen@tsinghua.edu.cn](mailto:htchen@tsinghua.edu.cn)  
        **GitHub：** [github.com/Hytn](https://github.com/Hytn)  
        **Google Scholar：** [scholar profile](https://scholar.google.com/citations?user=nwU3FhUAAAAJ&hl=zh-CN)
    design:
      columns: '1'
  - block: markdown
    content:
      title: '🎯 研究兴趣'
      subtitle: ''
      text: |-
        - 自主智能体
        - 大语言模型
        - AI4Research
        - 智能体强化学习
        - 工具学习

        **教育背景**

        - **复旦大学**，数据科学博士（2018.09 – 2024.06）
        - **大连理工大学**，电气工程工学学士（2014.09 – 2018.06）
    design:
      columns: '1'
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
        我的研究目标是理解并发展能够自动完成工程、科研、开发等复杂任务的人工智能系统。这些任务通常需要长期投入、大量努力，甚至依赖人类的创造性思考。围绕这一目标，我目前主要聚焦三个彼此关联的方向：

        🧪 **AI4Research** —— 构建能够进行文献检索、实验设计、数据分析、假设生成与验证的 AI 科研助手。

        🤖 **自主智能体** —— 研究具备环境感知、长短期记忆、任务分解与规划、工具调用能力的智能体模型与系统，并以大语言模型作为核心智能引擎。

        🧠 **基础模型** —— 探索通用人工智能模型的预训练与适配，包括语言理解与生成、知识表征、多模态信息融合以及下游任务泛化。
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
        我的开源工作围绕 **LLM 驱动的智能体** 形成了较完整的生态链：**数据**（AgentCPM-GUI, ToolLLM）→ **算法**（AgentRL, AgentCPM-Explore, MiniCPM4-MCP）→ **执行**（RD-Agent, XAgent）→ **评测**（ToLeaP）→ **应用**（QingXiaoDa）。
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
        🧑‍🏫 **学生指导** —— 共同指导 7 名本科生、6 名博士生开展 LLM 智能体研究，以及 5 名硕士生开展数据挖掘研究。

        📝 **会议审稿** —— NeurIPS、ICLR、EMNLP、KDD、WWW、COLING 等。

        📰 **期刊审稿** —— TKDE、Science China、AI Open 等。

        🎤 **邀请报告** —— “Autonomous Agents and Tool Learning with LLMs”（RLChina 2025）；“LLM-Driven Autonomous Agents”（Huawei OpenHarmony AI Agent TSG）。

        💰 **主持科研项目** —— 中国博士后科学基金面上资助（No. 2024M761689，8 万元）；国家资助博士后研究人员计划 C 档（24 万元）。
    design:
      columns: '1'
  - block: markdown
    id: contact
    content:
      title: '📬 联系方式'
      subtitle: ''
      text: |-
        欢迎就研究问题或合作想法与我联系。

        ✉️ **邮箱：** [htchen@tsinghua.edu.cn](mailto:htchen@tsinghua.edu.cn)

        🐙 **GitHub：** [github.com/Hytn](https://github.com/Hytn)
    design:
      columns: '1'
---
