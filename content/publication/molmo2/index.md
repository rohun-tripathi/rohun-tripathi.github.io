---
title: 'Molmo2: Open Weights and Data for Vision-Language Models with Video Understanding and Grounding'

# Authors
authors:
  - Christopher Clark
  - Jieyu Zhang
  - Zixian Ma
  - Jae Sung Park
  - Mohammadreza Salehi
  - Rohun Tripathi
  - Sangho Lee
  - Zhongzheng Ren
  - Chris Dongjoo Kim
  - Yinuo Yang
  - Vincent Shao
  - Yue Yang
  - Weikai Huang
  - Ziqi Gao
  - Taira Anderson
  - Jianrui Zhang
  - Jitesh Jain
  - George Stoica
  - Winson Han
  - Ali Farhadi
  - Ranjay Krishna

# Author notes (optional)
author_notes:

date: '2026-06-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: CVPR 2026 (Best Paper Award Nominee)
publication_short: CVPR 2026 (Best Paper Award Nominee)

abstract: Today's strongest video-language models (VLMs) remain proprietary. The strongest open-weight models either rely on synthetic data from proprietary VLMs, effectively distilling from them, or do not disclose their training data or recipe. As a result, the open-source community lacks the foundations needed to improve on the state-of-the-art video (and image) language models. Crucially, many downstream applications require more than just high-level video understanding; they require grounding -- either by pointing or by tracking in pixels. Even proprietary models lack this capability. We present Molmo2, a new family of VLMs that are state-of-the-art among open-source models and demonstrate exceptional new capabilities in point-driven grounding in single image, multi-image, and video tasks. Our key contribution is a collection of 7 new video datasets and 2 multi-image datasets, including a dataset of highly detailed video captions for pre-training, a free-form video Q&A dataset for fine-tuning, a new object tracking dataset with complex queries, and an innovative new video pointing dataset, all collected without the use of closed VLMs. We also present a training recipe for this data utilizing an efficient packing and message-tree encoding scheme, and show bi-directional attention on vision tokens and a novel token-weight strategy improves performance. Our best-in-class 8B model outperforms others in the class of open weight and data models on short videos, counting, and captioning, and is competitive on long-videos.

# Summary. An optional shortened abstract.
summary: Molmo2 is a new family of open-source video-language models that achieve state-of-the-art performance through novel datasets and training methods, particularly excelling in video grounding tasks without relying on proprietary models.

tags:
  - Multimodal
  - Vision-Language Models
  - Video Understanding
  - Grounding
  - Open Data
  - Molmo2

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/pdf/2601.10611'
url_code: 'https://github.com/allenai/molmo'
url_dataset: 'https://huggingface.co/collections/allenai/molmo2-data'
url_poster: ''
url_project: 'https://allenai.org/blog/molmo2'
url_slides: ''
url_source: 'https://arxiv.org/abs/2601.10611'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---
