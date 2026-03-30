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
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research goal is to understand and develop AI for automating the tasks (e.g., engineering, research, development, etc.) that require extensive time, effort, and sometimes even the creative thinking of humans. I work on automating the data-driven scientific research for contributing to both alleviating the burden on humans and revolutionizing human productivity. My research revolves around three interconnected directions:

        **AI4Research** — Building AI-powered research assistants capable of literature retrieval, experiment design, data analysis, and hypothesis generation & verification. With autonomous agents as the driving engine, I aim to construct systems and platforms for AI-assisted scientific research.

        **Autonomous Agents** — Developing agent models and systems with environment perception, long/short-term memory, task decomposition & planning, and tool-use capabilities, driven by LLMs as the intelligent core.

        **Foundation Models** — Pre-training general-purpose AI models with language understanding & generation, knowledge representation, multimodal information fusion, and downstream task adaptation capabilities.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: All Publications
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
      title: Open-Source Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        Please feel free to contact me if you have any questions or collaboration ideas.

        **Email:** [htchen@tsinghua.edu.cn](mailto:htchen@tsinghua.edu.cn)

        **GitHub:** [github.com/Hytn](https://github.com/Hytn)
    design:
      columns: '1'
---
