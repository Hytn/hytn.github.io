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
        I study how to build AI systems that can automate long-horizon work in research, engineering, and development. A central goal of my work is to make data-driven scientific research more scalable, reliable, and productive. I currently focus on four closely connected directions:

        🧪 **AI4Research / AI4AI** — I build AI research assistants for literature retrieval, experiment design, data analysis, and hypothesis generation and verification, and study how AI systems can improve the way AI itself is developed.

        🤖 **Autonomous Agents & LLM Post-Training** — I develop agent models and systems with environment perception, memory, planning, and tool-use capabilities, and post-train on-device LLMs (1B–8B) with agentic reinforcement learning so that small models solve long-horizon tasks that previously required closed-source frontier models.

        🧠 **Agent Memory & Continual Learning** — I work on memory-native foundation models and learnable dynamic memory operations that let agents accumulate experience, reuse it across tasks, and keep learning and evolving.

        🏗️ **Foundation Models** — I explore how to train and adapt general-purpose models for language understanding, knowledge representation, multimodal fusion, and downstream generalization.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 📄 Featured Publications
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
        All my open-source contributions revolve around the central theme of **LLM-powered agents**, forming a cohesive ecosystem: **Data** (AgentCPM-GUI) → **Algorithm** (AgentRL, AgentCPM-Explore, MiniCPM4-MCP, MiniCPM5) → **Memory** (MemT-1.0, AtomMem) → **Execution** (RD-Agent) → **Evaluation** (ToLeaP). Together these projects have gathered **40K+ GitHub stars** and **7M+ model downloads**.
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
      title: '🎓 Academic Service'
      subtitle: ''
      text: |-
        🧑‍🏫 **Student Supervision** — I co-supervise undergraduate, master's, and PhD students on LLM agents and LLM post-training.

        🧭 **Area Chair** — ACL.

        📝 **Conference Reviewing** — I regularly review for venues including NeurIPS, ICLR, EMNLP, KDD, WWW, and COLING.

        📰 **Journal Reviewing** — I have also reviewed for journals such as TKDE, Science China, and AI Open.

        🏛️ **Membership** — Member of the CCF Technical Committee on Theoretical Computer Science (China Computer Federation).

        🎤 **Invited Talks** — *Post-Training Methods for On-Device Agents on Long-Horizon Complex Tasks* (RLChina 2026), *Towards the Era of Agent 2.0* (SMP 2026), *Autonomous Agents and Tool Learning with LLMs* (RLChina 2025), and *LLM-Driven Autonomous Agents* (Huawei OpenHarmony AI Agent TSG).

        💰 **Research Grants** — I serve as PI of an NSFC Young Scientists Fund (Category C) project, the China Postdoctoral Science Foundation General Grant, and the National Postdoctoral Researcher Program Category C.
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
