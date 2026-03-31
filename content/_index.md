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
      username: me
      text: ''
      headings:
        about: 'Biography'
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
        I study how to build AI systems that can automate long-horizon work in research, engineering, and development. A central goal of my work is to make data-driven scientific research more scalable, reliable, and productive. I currently focus on three closely connected directions:

        🧪 **AI4Research** — I build AI research assistants for literature retrieval, experiment design, data analysis, and hypothesis generation and verification.

        🤖 **Autonomous Agents** — I develop agent models and systems with environment perception, memory, planning, and tool-use capabilities, with LLMs as the core intelligence.

        🧠 **Foundation Models** — I explore how to train and adapt general-purpose models for language understanding, knowledge representation, multimodal fusion, and downstream generalization.
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
      title: 💻 Open-Source Projects
      text: |-
        All my open-source contributions revolve around the central theme of **LLM-powered agents**, forming a cohesive ecosystem: **Data** (AgentCPM-GUI) → **Algorithm** (AgentRL, AgentCPM-Explore, MiniCPM4-MCP) → **Execution** (RD-Agent) → **Evaluation** (ToLeaP).
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
      title: '🎓 Academic Service'
      subtitle: ''
      text: |-
        🧑‍🏫 **Student Supervision** — I co-supervise undergraduate, master's, and PhD students on LLM agents and data mining.

        📝 **Conference Reviewing** — I regularly review for venues including NeurIPS, ICLR, EMNLP, KDD, WWW, and COLING.

        📰 **Journal Reviewing** — I have also reviewed for journals such as TKDE, Science China, and AI Open.

        🎤 **Invited Talks** — Recent invited talks include *Autonomous Agents and Tool Learning with LLMs* (RLChina 2025) and *LLM-Driven Autonomous Agents* (Huawei OpenHarmony AI Agent TSG).

        💰 **Research Grants** — I currently serve as PI for the China Postdoctoral Science Foundation General Grant and the National Postdoctoral Researcher Program Category C.
    design:
      columns: '1'
  - block: markdown
    id: contact
    content:
      title: '📬 Contact'
      subtitle: ''
      text: |-
        Feel free to reach out if you would like to discuss research ideas, collaborations, or open-source projects.

        ✉️ **Email:** [haotian.chen@163.com](mailto:haotian.chen@163.com) / [ht1ian.chen@gmail.com](mailto:ht1ian.chen@gmail.com)

        🐙 **GitHub:** [github.com/Hytn](https://github.com/Hytn)

        ✖️ **X:** [@HytnChen](https://x.com/HytnChen)

        🎓 **Google Scholar:** [scholar profile](https://scholar.google.com/citations?user=nwU3FhUAAAAJ&hl=en)
    design:
      columns: '1'
---
