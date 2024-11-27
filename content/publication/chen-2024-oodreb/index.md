---
title: 'OODREB: Benchmarking State-of-the-Art Methods for Out-Of-Distribution Generalization
  on Relation Extraction'
authors:
- Haotian Chen
- Houjing Guo
- Bingsheng Chen
- Xiangdong Zhou
date: '2024-01-01'
publishDate: '2024-11-27T12:52:59.477488Z'
publication_types:
- paper-conference
publication: '*Proceedings of the ACM Web Conference 2024*'
doi: 10.1145/3589334.3645695
abstract: 'Relation extraction (RE) methods have achieved striking performance when
  training and test data are independently and identically distributed (i.i.d). However,
  in real-world scenarios where RE models are trained to acquire knowledge in the
  wild, the assumption can hardly be satisfied due to the different and unknown testing
  distributions. In this paper, we serve as the first effort to study out-of-distribution
  (OOD) problems in RE by constructing an out-of-distribution relation extraction
  benchmark (OODREB) and then investigating the abilities of state-of-the-art (SOTA)
  RE methods on OODREB in both i.i.d. and OOD settings. Our proposed benchmark and
  analysis reveal new findings and insights: (1) Existing SOTA RE methods struggle
  to achieve satisfying performance on OODREB in both i.i.d. and OOD settings due
  to the complex training data and biased model selection method. Rethinking the developing
  protocols of RE methods is of great urgency. (2) The SOTA RE methods fail to learn
  causality due to the diverse linguistic expressions of causal information. The failure
  limits their robustness and generalization ability; (3) Current RE methods based
  on language models are far away from being deployed in real-world applications.
  We appeal to future work to take the OOD generalization and causality learning ability
  into consideration. We make our annotation and code publicly available at https://github.com/Hytn/OODREB.'
tags:
- benchmark
- out-of-distribution generalization
- relation extraction
links:
- name: URL
  url: https://doi.org/10.1145/3589334.3645695
---