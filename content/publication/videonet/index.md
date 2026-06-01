---
title: 'VideoNet: A Large-Scale Dataset for Domain-Specific Action Recognition'

# Authors
authors:
  - Tanush Yadav
  - Mohammadreza Salehi
  - Jae Sung Park
  - Vivek Ramanujan
  - Hannaneh Hajishirzi
  - Yejin Choi
  - Ali Farhadi
  - Rohun Tripathi†
  - Ranjay Krishna†

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - 'Equal advising'
  - 'Equal advising'
  - 'Equal advising'

date: '2026-06-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-05-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026 (Highlight)
publication_short: CVPR 2026 Highlight

abstract: Videos are unique in their ability to capture actions which transcend multiple frames. Accordingly, for many years action recognition was the quintessential task for video understanding. Unfortunately, due to a lack of sufficiently diverse and challenging data, modern vision-language models (VLMs) are no longer evaluated on their action recognition capabilities. To revitalize action recognition in the era of VLMs, we advocate for a returned focus on domain-specific actions. To this end, we introduce VideoNet, a domain-specific action recognition benchmark covering 1,000 distinct actions from 37 domains. We begin with a multiple-choice evaluation setting, where the difference between closed and open models is stark - Gemini 3.1 Pro attains 69.9% accuracy while Qwen3-VL-8B gets a mere 45.0%. To understand why VLMs struggle on VideoNet, we relax the questions into a binary setting, where random chance is 50%. Still, Qwen achieves only 59.2% accuracy. Further relaxing the evaluation setup, we provide $k\in\{1,2,3\}$ in-context examples of the action. Some models excel in the few-shot setting, while others falter; Qwen improves $+7.0\%$, while Gemini declines $-4.8\%$. Notably, these gains fall short of the $+13.6\%$ improvement in non-expert humans when given few-shot examples. Finding that VLMs struggle to fully exploit in-context examples, we shift from test-time improvements to the training side. We collect the first large-scale training dataset for domain-specific actions, totaling nearly 500k video question-answer pairs. Fine-tuning a Molmo2-4B model on our data, we surpass all open-weight 8B models on the VideoNet benchmark.

# Summary. An optional shortened abstract.
summary: VideoNet is a large-scale domain-specific action recognition benchmark and training dataset with 1,000 distinct actions across 37 domains, designed to revitalize action recognition evaluation for modern vision-language models.

tags:
  - Action Recognition
  - Video Understanding
  - Vision-Language Models
  - Dataset
  - Benchmark

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/pdf/2605.02834'
url_code: ''
url_dataset: 'https://huggingface.co/datasets/raivn/VideoNet'
url_poster: ''
url_project: 'https://tanu.sh/videonet'
url_slides: ''
url_source: 'https://arxiv.org/abs/2605.02834'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---
