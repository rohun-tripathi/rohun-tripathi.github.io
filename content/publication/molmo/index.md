---
title: 'Molmo and PixMo: Open Weights and Open Data for State-of-the-Art Vision-Language Models'

# Authors
authors:
  - Matt Deitke*
  - Christopher Clark*
  - Sangho Lee
  - Rohun Tripathi
  - Yue Yang
  - Jae Sung Park
  - Mohammadreza Salehi
  - others

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025 (Best Paper Honorable Mention)
publication_short: CVPR 2025

abstract: Today's most advanced vision-language models (VLMs) remain proprietary. The strongest open-weight models rely heavily on synthetic data from proprietary VLMs to achieve good performance, effectively distilling these closed VLMs into open ones. As a result, the community has been missing foundational knowledge about how to build performant VLMs from scratch. We present Molmo, a new family of VLMs that are state-of-the-art in their class of openness. Our key contribution is a collection of new datasets called PixMo, including a dataset of highly detailed image captions for pre-training, a free-form image Q&A dataset for fine-tuning, and an innovative 2D pointing dataset, all collected without the use of external VLMs. The success of our approach relies on careful modeling choices, a well-tuned training pipeline, and, most critically, the quality of our newly collected datasets. Our best-in-class 72B model not only outperforms others in the class of open weight and data models, but also outperforms larger proprietary models including Claude 3.5 Sonnet, and Gemini 1.5 Pro and Flash, second only to GPT-4o based on both academic benchmarks and on a large human evaluation. Our model weights, new datasets, and source code will all be released.

# Summary. An optional shortened abstract.
summary: We present Molmo, a new family of state-of-the-art VLMs. Starting from pre-trained vision encoders and language-only LLMs, the entire remainder of our VLM pipeline – weights, code, data, and evaluations – is open and free from VLM distillation.

tags:
  - Multimodal
  - Vision-Language Models
  - Open Data
  - PixMo
  - Molmo

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/pdf/2409.17146'
url_code: 'https://github.com/allenai/molmo'
url_dataset: 'https://huggingface.co/collections/allenai/pixmo'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/abs/2409.17146'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---
