---
title: 'Single-View Height Map Prediction for Satellite Imagery'

authors:


date: '2018-07-01T00:00:00Z'
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: '2018-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: 

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We explore the problem of predicting height maps for man- made and natural terrain when seen from a single image captured by a satellite. This is a very challenging, ill-posed problem, and single-view depth prediction models trained for indoor and outdoor scenes do not immediately apply to the satellite domain. This paper explores this problem for flat and sloped terrain. We propose a baseline model using a deep network that regresses directly from the input image to a height map and is trained using a MAE loss designed specif- ically for our domain. Predicting the height for images with sloped terrain proves to be a particularly hard challenge. To solve for slopes, we train a separate network to predict dense surface normal maps and combine the surface nor- mals and the predicted height in a global optimization step to improve results on sloped terrain. However, the standard optimization strategy using a constant weight for all pixels in an image introduces a regression on the performance on flat terrain. We propose a novel weight prediction model that predicts per-pixel weights as input for the optimization step. We show that this proposed solution improves height prediction for sloped terrain without regressing on the flat terrain and perform evaluations on a range of loss functions, data sets, fusion strategies and training strategies.

summary: 

tags:

featured: false

links:
- name: ''
url_pdf: 'https://rohun-tripathi.github.io/files/Single_View_Height_Technical_Report.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
