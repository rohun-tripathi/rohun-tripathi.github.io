---
title: 'HinTel-AlignBench: A Framework and Benchmark for Hindi-Telugu with English-Aligned Samples'

# Authors
authors:
  - Rishikant Chigrupaatii
  - Ponnada Sai Tulasi Kanishka
  - Lalit Chandra Routhu
  - Martin Patel Sama Supratheek Reddy
  - Divyam Gupta
  - Dasari Srikar
  - Krishna Teja Kuchimanchi
  - Rajiv Misra
  - Rohun Tripathi

# Author notes (optional)
author_notes:

date: '2026-05-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-11-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ACL 2026 AVLR Workshop
publication_short: ACL 2026 AVLR Workshop

abstract: "With nearly 1.5 billion people and more than 120 major languages, India represents one of the most diverse regions in the world. As multilingual Vision-Language Models (VLMs) gain prominence, robust evaluation methodologies are essential to drive progress toward equitable AI for low-resource languages. Current multilingual VLM evaluations suffer from four major limitations: reliance on unverified auto-translations, narrow task/domain coverage, limited sample sizes, and lack of cultural and natively sourced Question-Answering (QA). To address these gaps, we present a scalable framework to evaluate VLMs in Indian languages and compare it with performance in English. Using the framework, we generate HinTel-AlignBench, a benchmark that draws from diverse sources in Hindi and Telugu with English-aligned samples. Our contributions are threefold: (1) a semi-automated dataset creation framework combining back-translation, filtering, and human verification; (2) the most comprehensive vision-language benchmark for Hindi and and Telugu, including adapted English datasets (VQAv2, RealWorldQA, CLEVR-Math) and native novel Indic datasets (JEE for STEM, VAANI for cultural grounding) with approximately 4,000 QA pairs per language; and (3) a detailed performance analysis of various State-of-the-Art (SOTA) open-weight and closed-source VLMs. We find a regression in performance for tasks in English versus in Indian languages for 4 out of 5 tasks across all the models, with an average regression of 8.3 points in Hindi and 5.5 points for Telugu. We categorize common failure modes to highlight concrete areas of improvement in multilingual multimodal understanding."

# Summary. An optional shortened abstract.
summary: We present HinTel-AlignBench, a scalable framework and comprehensive benchmark for evaluating Vision-Language Models in Hindi and Telugu with English-aligned samples.

tags:
  - Multilingual
  - Vision-Language Models
  - Benchmarking
  - Indic Languages
  - Hindi
  - Telugu

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - indicvisionbench
url_pdf: 'https://arxiv.org/pdf/2511.15183.pdf'
url_code: ''
url_dataset: 'https://huggingface.co/datasets/lalit-03/IndicVisionBench'
url_poster: ''
url_project: 'https://rishikant24.github.io/indicvisionbench.github.io/'
url_slides: ''
url_source: 'https://arxiv.org/abs/2511.15183'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---
