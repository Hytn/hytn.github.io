---
title: 'Did the Models Understand Documents? Benchmarking Models for Language Understanding in Document-Level Relation Extraction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Bingsheng Chen
  - Xiangdong Zhou

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-01T00:00:00Z'
doi: '10.18653/v1/2023.acl-long.354'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']
# publication_types: ["article-journal"]
# publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics
publication_short: ACL 2023

abstract: Document-level relation extraction (DocRE) attracts more research interest recently. While models achieve consistent performance gains in DocRE, their underlying decision rules are still understudied - Do they make the right predictions according to rationales? In this paper, we take the first step toward answering this question and then introduce a new perspective on comprehensively evaluating a model. Specifically, we first conduct annotations to provide the rationales considered by humans in DocRE. Then, we conduct investigations and reveal the fact - In contrast to humans, the representative state-of-the-art (SOTA) models in DocRE exhibit different decision rules. Through our proposed RE-specific attacks, we next demonstrate that the significant discrepancy in decision rules between models and humans severely damages the robustness of models and renders them inapplicable to real-world RE scenarios. After that, we introduce mean average precision (MAP) to evaluate the understanding and reasoning capabilities of models. According to the extensive experimental results, we finally appeal to future work to consider evaluating both performance and the understanding ability of models for the development of their applications.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://aclanthology.org/2023.acl-long.354/

url_pdf: publications/acl2023.pdf
url_code: 'https://github.com/Hytn/DocRED-HWE'
url_dataset: 'https://github.com/Hytn/DocRED-HWE'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://aclanthology.org/2023.acl-long.354.mp4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
# slides: example
---
