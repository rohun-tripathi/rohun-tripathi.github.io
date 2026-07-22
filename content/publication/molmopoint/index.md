---
title: 'MolmoPoint: Better Pointing for VLMs with Grounding Tokens'

# Authors
authors:
  - Christopher Clark
  - Yue Yang
  - Jae Sung Park
  - Zixian Ma
  - Jieyu Zhang
  - Rohun Tripathi
  - Mohammadreza Salehi
  - Sangho Lee
  - Taira Anderson
  - Winson Han
  - Ranjay Krishna

# Author notes (optional)
author_notes:

date: '2026-06-04T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: ECCV 2026
publication_short: ECCV 2026

abstract: Grounding has become a fundamental capability of vision-language models (VLMs). Most existing VLMs point by generating coordinates as part of their text output, which requires learning a complicated coordinate system and results in a high token count. Instead, we propose a more intuitive approach using grounding tokens that directly select visual tokens from the input video or image. MolmoPoint scores coarse-grained image patches using the LLM's hidden states, then scores fine-grained subpatches from the highest scoring patch using ViT image features, and then selects a point within the highest scoring subpatch. We show that this approach is more efficient and leads to better performance on diverse pointing, counting, and tracking benchmarks across single image, multi-image, and video tasks.

# Summary. An optional shortened abstract.
summary: MolmoPoint is a new VLM architecture that enables more precise and efficient visual grounding by using special tokens to directly select from the model's internal visual representation instead of generating text coordinates.

tags:
  - Multimodal
  - Vision-Language Models
  - Grounding
  - Pointing
  - Interpretability
  - MolmoPoint

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/pdf/2603.28069'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://allenai.org/blog/molmopoint'
url_slides: ''
url_source: 'https://arxiv.org/abs/2603.28069'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---
