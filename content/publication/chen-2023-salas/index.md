---
title: 'SALAS: Supervised Aspect Learning Improves Abstractive Multi-document Summarization Through Aspect Information Loss'
authors:
- admin
- Han Zhang
- Houjing Guo
- Shuchang Yi
- Bingsheng Chen
- Xiangdong Zhou
date: '2023-01-01' # '2023-06-01T00:00:00Z'
publishDate: '2024-11-27T12:52:59.491406Z' # '2023-09-01T00:00:00Z'
publication_types:
- paper-conference
publication: 'Machine Learning and Knowledge Discovery in Databases: Research Track.'
publication_short: ECML-PKDD 2023
doi: 10.1007/978-3-031-43421-1_4

abstract: Abstractive multi-document summarization (MDS) aims at summarizing and paraphrasing the salient key information in multiple documents. For dealing with the long-input issue brought by multiple documents, most previous work extracts salient sentence-level information from the input documents and then performs summarizing on the extracted information. However, the aspects of documents are neglected. The limited ability to discover the content on certain aspects hampers the key information seeking and ruins the comprehensiveness of the generated summaries. To solve the issue, we propose a novel Supervised Aspect-Learning Abstractive Summarization framework (SALAS) and a new aspect information loss (AILoss) to learn aspect information to supervise the generating process heuristically. Specifically, SALAS adopts three probes to capture aspect information as both constraints of the objective function and supplement information to be expressed in the representations. Aspect information is explicitly discovered and exploited to facilitate generating comprehensive summaries by AILoss. We conduct extensive experiments on three public datasets. The experimental results demonstrate that SALAS outperforms previous state-of-the-art (SOTA) baselines, achieving a new SOTA performance on the three MDS datasets.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://aclanthology.org/2023.acl-long.354/

url_pdf: pubs/ecmlpkdd2023.pdf
url_code: 'https://github.com/Hytn/AspectSum'
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
