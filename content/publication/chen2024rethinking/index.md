---
title: 'Rethinking the Development of Large Language Models from the Causal Perspective: A Legal Text Prediction Case Study'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Lingwei Zhang
  - Yiran Liu
  - Yang Yu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-12-01T00:00:00Z'
# doi: '10.18653/v1/2023.acl-long.354'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The 38th Annual AAAI Conference on Artificial Intelligence
publication_short: AAAI 2024

abstract: While large language models (LLMs) exhibit impressive performance on a wide range of NLP tasks, most of them fail to learn the causality from correlation, which disables them from learning rationales for predicting. Rethinking the whole developing process of LLMs is of great urgency as they are adopted in various critical tasks that need rationales, including legal text prediction (e.g., legal judgment prediction). In this paper, we first explain the underlying theoretical mechanism of their failure and argue that both the data imbalance and the omission of causality in model design and selection render the current training-testing paradigm failed to select the unique causality-based model from correlation-based models. Second, we take the legal text prediction task as the testbed and reconstruct the developing process of LLMs by simultaneously infusing causality into model architectures and organizing causality-based adversarial attacks for evaluation. Specifically, we base our reconstruction on our theoretical analysis and propose a causality-aware self-attention mechanism (CASAM), which prevents LLMs from entangling causal and non-causal information by restricting the interaction between causal and non-causal words. Meanwhile, we propose eight kinds of legal-specific attacks to form causality-based model selection. Our extensive experimental results demonstrate that our proposed CASAM achieves state-of-the-art (SOTA) performances and the strongest robustness on three commonly used legal text prediction benchmarks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://aclanthology.org/2023.acl-long.354/

url_pdf: publications/aaai2024.pdf
url_code: 'https://github.com/Carrot-Red/Rethink-LLM-development'
# url_dataset: 'https://github.com/Hytn/DocRED-HWE'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://aclanthology.org/2023.acl-long.354.mp4'

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
