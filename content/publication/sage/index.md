---
title: 'SAGE: Training Smart Any-Horizon Agents for Long Video Reasoning with Reinforcement Learning'

# Authors
authors:
  - Jitesh Jain
  - Jialuo Li
  - Zixian Ma
  - Jieyu Zhang
  - Chris Dongjoo Kim
  - Sangho Lee
  - Rohun Tripathi
  - Tanmay Gupta
  - Christopher Clark
  - Humphrey Shi

# Author notes (optional)
author_notes:

date: '2026-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-12-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026
publication_short: CVPR 2026

abstract: As humans, we are natural any-horizon reasoners, i.e., we can decide whether to iteratively skim long videos or watch short ones in full when necessary for a given task. With this in mind, one would expect video reasoning models to reason flexibly across different durations. However, SOTA models are still trained to predict answers in a single turn while processing a large number of frames, akin to watching an entire long video, requiring significant resources. This raises the question - Is it possible to develop performant any-horizon video reasoning systems? Inspired by human behavior, we first propose SAGE, an agent system that performs multi-turn reasoning on long videos while handling simpler problems in a single turn. Secondly, we introduce an easy synthetic data generation pipeline using Gemini-2.5-Flash to train the orchestrator, SAGE-MM, which lies at the core of SAGE. We further propose an effective RL post-training recipe essential for instilling any-horizon reasoning ability in SAGE-MM. Thirdly, we curate SAGE-Bench with an average duration of greater than 700 seconds for evaluating video reasoning ability in real-world entertainment use cases. Lastly, we empirically validate the effectiveness of our system, data, and RL recipe, observing notable improvements of up to 6.1% on open-ended video reasoning tasks, as well as an impressive 8.2% improvement on videos longer than 10 minutes.

# Summary. An optional shortened abstract.
summary: SAGE is an agent system that enables flexible video reasoning across different time scales by using multi-turn processing and reinforcement learning, achieving improved performance on long-form video analysis tasks.

tags:
  - Video Reasoning
  - Agents
  - Reinforcement Learning
  - Long Video

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/pdf/2512.13874'
url_code: 'https://github.com/allenai/SAGE'
url_dataset: ''
url_poster: ''
url_project: 'https://praeclarumjj3.github.io/sage/'
url_slides: ''
url_source: 'https://arxiv.org/abs/2512.13874'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---
