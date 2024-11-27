---
title: 'OODREB: Benchmarking State-of-the-Art Methods for Out-of-Distribution Generalization on Relation Extraction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Houjing Guo
  - Bingsheng Chen
  - Xiangdong Zhou

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-02-01T00:00:00Z'
# doi: '10.18653/v1/2023.acl-long.354'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: International World Wide Web Conference
publication_short: WWW 2024

abstract: Relation extraction (RE) methods have achieved striking performance when training and test data are independently and identically distributed (i.i.d). However, in real-world scenarios where RE models are trained to acquire knowledge in the wild, the assumption can hardly be satisfied due to the different and unknown testing distributions. In this paper, we serve as the first effort to study out-of-distribution (OOD) problems in RE by constructing an out-of-distribution relation extraction benchmark (OODREB) and then investigating the abilities of state-of-the-art (SOTA) RE methods on OODREB in both i.i.d. and OOD settings. Our proposed benchmark and analysis reveal new findings and insights - (1) Existing SOTA RE methods struggle to achieve satisfying performance on OODREB in both i.i.d. and OOD settings due to the complex training data and biased model selection method. Rethinking the developing protocols of RE methods is of great urgency. (2) The SOTA RE methods fail to learn causality due to the diverse linguistic expressions of causal information. The failure limits their robustness and generalization ability; (3) Current RE methods based on language models are far away from being deployed in real-world applications. We appeal to future work to take the OOD generalization and causality learning ability into consideration.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://aclanthology.org/2023.acl-long.354/

url_pdf: publications/www2024.pdf
url_code: 'https://github.com/Hytn/OODREB'
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
