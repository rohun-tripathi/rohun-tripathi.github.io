---
title: 'MolmoB0T: Large-Scale Simulation Enables Zero-Shot Manipulation'

# Authors
authors:
  - Abhay Deshpande
  - Maya Guru
  - Rose Hendrix
  - Snehal Jauhri
  - Ainaz Eftekhar
  - Rohun Tripathi
  - Max Argus
  - Jordi Salvador
  - Haoquan Fang
  - Matthew Wallingford
  - Wilbert Pumacay
  - Yejin Kim
  - Quinn Pfeifer
  - Ying-Chun Lee
  - Piper Wolters
  - Omar Rayyan
  - Mingtong Zhang
  - Jiafei Duan
  - Karen Farley
  - Winson Han
  - Eli Vanderbilt
  - Dieter Fox
  - Ali Farhadi
  - Georgia Chalvatzaki
  - Dhruv Shah
  - Ranjay Krishna

# Author notes (optional)
author_notes:

date: '2026-06-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: ICRA 2026 SDRL Workshop
publication_short: ICRA 2026 SDRL Workshop (Best Paper Award)

abstract: Procedural environment generation and large-scale simulation have shown promise in training robust robotic policies. However, zero-shot transfer of these policies to diverse real-world tasks remains a challenge. We introduce MolmoB0T, a suite of general-purpose manipulation policies trained on a massive dataset of 2.5 million expert trajectories in simulation. We leverage a diverse set of over 10,000 articulated objects and 500 procedurally generated environments to ensure broad coverage of manipulation tasks. We train three policy classes - MolmoBot, a Molmo2-based multi-frame vision-language model with a flow-matching action head; MolmoBot-Pi0, which replicates the pi_0 architecture to enable direct comparison; and MolmoBot-SPOC, a lightweight policy suitable for edge deployment and amenable to RL fine-tuning. We evaluate on two robotic platforms - the Franka FR3 for tabletop manipulation tasks and the Rainbow Robotics RB-Y1 mobile manipulator for door opening, drawer manipulation, cabinet interaction, and mobile pick-and-place. Without any real-world fine-tuning, our policies achieve zero-shot transfer to unseen objects and environments. On tabletop pick-and-place, MolmoBot achieves a success rate of 79.2% in real-world evaluations across 4 settings, outperforming pi_0.5 at 39.2%. Our results demonstrate that procedural environment generation combined with diverse articulated assets can produce robust manipulation policies that generalize broadly to the real world.

# Summary. An optional shortened abstract.
summary: MolmoB0T is a suite of general-purpose robotic manipulation policies trained on 2.5 million simulated trajectories that achieve state-of-the-art zero-shot transfer to diverse real-world tasks and environments.

tags:
  - Robotics
  - Manipulation
  - Vision-Language Models
  - Simulation
  - Zero-Shot Transfer
  - MolmoBot

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/pdf/2603.16861'
url_code: 'https://allenai.github.io/MolmoBot'
url_dataset: 'https://huggingface.co/datasets/allenai/molmobot-data'
url_poster: ''
url_project: 'https://allenai.github.io/MolmoBot'
url_slides: ''
url_source: 'https://arxiv.org/abs/2603.16861'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---
