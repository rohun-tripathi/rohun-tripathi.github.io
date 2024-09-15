---
title: 'MODEFORMER: Modality-Preserving Embedding For Audio-Video Synchronization Using Transformers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Akash Gupta
  - Rohun Tripathi
  - Won-Dong Jang

# Author notes (optional)
author_notes:

date: '2023-06-04T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In IEEE International Conference on Acoustics, Speech and Signal Processing 
publication_short: In ICASSP

abstract: Lack of audio-video synchronization is a common problem during television broadcasts and video conferencing, leading to an unsatisfactory viewing experience. A widely accepted paradigm is to create an error detection mechanism that identifies the cases when audio is leading or lagging. We propose ModEFormer, which independently extracts audio and video embeddings using modality-specific transformers. Different from the other transformer-based approaches, ModEFormer preserves the modality of the input streams which allows us to use a larger batch size with more negative audio samples for contrastive learning. Further, we propose a tradeoff between the number of negative samples and number of unique samples in a batch to significantly exceed the performance of previous methods. Experimental results show that ModEFormer achieves state-of-the-art performance, 94.5% for LRS2 and 90.9% for LRS3. Finally, we demonstrate how ModEFormer can be used for offset detection for test clips.

# Summary. An optional shortened abstract.
summary: 

tags:
  - 

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://assets.amazon.science/b0/3e/58c50a9d4e0cbc40abe00e147f71/modeformer-modality-preserving-embedding-for-audio-video-synchronization-using-transformers.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/document/10097209'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
