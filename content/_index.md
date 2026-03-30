---
title: ''
summary: ''
date: 2024-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
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
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: false
  - block: markdown
    content:
      title: '🔬 Research'
      subtitle: ''
      text: |-
        My research goal is to understand and develop AI for automating the tasks (e.g., engineering, research, development) that require extensive time, effort, and sometimes even the creative thinking of humans. I work on automating data-driven scientific research for contributing to both alleviating the burden on humans and revolutionizing human productivity. My research revolves around three interconnected directions:

        🧪 **AI4Research** — Building AI-powered research assistants capable of literature retrieval, experiment design, data analysis, and hypothesis generation & verification.

        🤖 **Autonomous Agents** — Developing agent models and systems with environment perception, long/short-term memory, task decomposition & planning, and tool-use capabilities, driven by LLMs as the intelligent core.

        🧠 **Foundation Models** — Pre-training general-purpose AI models with language understanding & generation, knowledge representation, multimodal information fusion, and downstream task adaptation.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 📄 Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: 📚 All Publications
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
      title: 💻 Open-Source Projects
      text: |-
        All my open-source contributions revolve around the central theme of **LLM-powered agents**, forming a cohesive ecosystem: **Data** (AgentCPM-GUI, ToolLLM) → **Algorithm** (AgentRL, AgentCPM-Explore, MiniCPM4-MCP) → **Execution** (RD-Agent, XAgent) → **Evaluation** (ToLeaP) → **Application** (QingXiaoDa).
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
  - block: markdown
    id: service
    content:
      title: '🎓 Academic Service'
      subtitle: ''
      text: |-
        🧑‍🏫 **Student Supervision** — Co-supervising 7 undergraduates and 6 PhD students on LLM agents, and 5 master students on data mining.

        📝 **Conference Reviewer** — NeurIPS, ICLR, EMNLP, KDD, WWW, COLING, etc.

        📰 **Journal Reviewer** — TKDE, Science China, AI Open, etc.

        🎤 **Invited Talks** — "Autonomous Agents and Tool Learning with LLMs" (RLChina 2025); "LLM-Driven Autonomous Agents" (Huawei OpenHarmony AI Agent TSG).

        💰 **Research Grants (PI)** — China Postdoctoral Science Foundation General Grant (No. 2024M761689, 80K CNY); National Postdoctoral Researcher Program Category C (240K CNY).
    design:
      columns: '1'
  - block: markdown
    id: contact
    content:
      title: '📬 Contact'
      subtitle: ''
      text: |-
        Feel free to reach out for questions or collaboration ideas!

        ✉️ **Email:** [htchen@tsinghua.edu.cn](mailto:htchen@tsinghua.edu.cn)

        🐙 **GitHub:** [github.com/Hytn](https://github.com/Hytn)

        🎓 **Google Scholar:** [scholar profile](https://scholar.google.com/citations?user=nwU3FhUAAAAJ&hl=en)
    design:
      columns: '1'
---
