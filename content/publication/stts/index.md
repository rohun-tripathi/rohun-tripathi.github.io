---
title: 'Unified Spatio-Temporal Token Scoring for Efficient Video VLMs'

# Authors
authors:
  - Jianrui Zhang
  - Yue Yang
  - Rohun Tripathi
  - Winson Han
  - Ranjay Krishna
  - Christopher Clark
  - Yong Jae Lee
  - Sangho Lee

# Author notes (optional)
author_notes:

date: '2026-03-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: Arxiv 2026
publication_short: Arxiv 2026

abstract: Token pruning is essential for enhancing the computational efficiency of vision-language models (VLMs), particularly for video-based tasks where temporal redundancy is prevalent. Prior approaches typically prune tokens either (1) within the vision transformer (ViT) exclusively for unimodal perception tasks such as action recognition and object segmentation, without adapting to downstream vision-language tasks; or (2) only within the LLM while leaving the ViT output intact, often requiring complex text-conditioned token selection mechanisms. In this paper, we introduce Spatio-Temporal Token Scoring (STTS), a simple and lightweight module that prunes vision tokens across both the ViT and the LLM without text conditioning or token merging, and is fully compatible with end-to-end training. By learning how to score temporally via an auxiliary loss and spatially via LLM downstream gradients, aided by our efficient packing algorithm, STTS prunes 50% of vision tokens throughout the entire architecture, resulting in a 62% improvement in efficiency during both training and inference with only a 0.7% drop in average performance across 13 short and long video QA tasks. Efficiency gains increase with more sampled frames per video. Applying test-time scaling for long-video QA further yields performance gains of 0.5-1% compared to the baseline. Overall, STTS represents a novel, simple yet effective technique for unified, architecture-wide vision token pruning.

# Summary. An optional shortened abstract.
summary: STTS is a novel, simple yet effective technique for unified, architecture-wide vision token pruning across both ViT and LLM, improving efficiency by 62% with minimal performance loss in video QA tasks.

tags:
  - Video VLMs
  - Token Pruning
  - Efficiency
  - Vision-Language Models
  - STTS

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/pdf/2603.18004'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/abs/2603.18004'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---
