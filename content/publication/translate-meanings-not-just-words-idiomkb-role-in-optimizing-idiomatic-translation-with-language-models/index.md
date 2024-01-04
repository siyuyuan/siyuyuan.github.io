---
abstract: To translate well, machine translation (MT) systems and general-purposed 
  language models (LMs) need a deep understanding of both source and target 
  languages and cultures. Therefore, idioms, with their non-compositional nature, 
  pose particular challenges for Transformer-based systems, as literal translations 
  often miss the intended meaning. Traditional methods, which replace idioms using 
  existing knowledge bases (KBs), often lack scale and context-awareness. 
  Addressing these challenges, our approach prioritizes context-awareness and 
  scalability, allowing for offline storage of idioms in a manageable KB size. 
  This ensures efficient serving with smaller models and provides a more comprehensive 
  understanding of idiomatic expressions. We introduce a multilingual idiom KB 
  (IDIOMKB) developed using large LMs to address this. This KB facilitates better 
  translation by smaller models, such as BLOOMZ (7.1B), Alpaca (7B), and 
  InstructGPT (6.7B), by retrieving idioms’ figurative meanings. We present a novel, 
  GPT-4-powered metric for human-aligned evaluation, demonstrating that IDIOMKB 
  considerably boosts model performance. Human evaluations further validate 
  our KB’s quality.
slides: ""
url_pdf: https://arxiv.org/abs/2308.13961
publication_types:
  - "1"
authors:
  - Shuang Li
  - Jiangjie Chen 
  - admin
  - Xinyi Wu
  - Hao Yang 
  - Shimin Tao 
  - Yanghua Xiao
author_notes: []
publication: In *The 38th Annual AAAI Conference on Artificial Intelligence (**AAAI 2024**)*
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: "Translate Meanings, Not Just Words: IdiomKB's Role in Optimizing Idiomatic Translation with Language Models"
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: 8.png
date: 2023-12-09T02:34:00.000Z
url_slides: ""
publishDate: 2023-12-09T02:34:00.000Z
url_poster: ""
url_code: https://github.com/lishuang-w/IdiomKB
---
