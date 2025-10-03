---
title: 'Moving Horizon Estimation for Simultaneous Localization and Mapping with Robust Estimation Error Bounds'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alexandre Didier
  - Simon Muntwiler
  - Melanie N. Zeilinger

# Author notes (optional)
author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2025-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In IEEE European Control Conference 2025
#publication_short: In *ICW*

abstract: This paper presents a robust moving horizon estimation (MHE) approach with provable estimation error bounds for solving the simultaneous localization and mapping (SLAM) problem. We derive sufficient conditions to guarantee robust stability in ego-state estimates and bounded errors in landmark position estimates, even under limited landmark visibility which directly affects overall system detectability. This is achieved by decoupling the MHE updates for the ego-state and landmark positions, enabling individual landmark updates only when the required detectability conditions are met. The decoupled MHE structure also allows for parallelization of landmark updates, improving computational efficiency. We discuss the key assumptions, including ego-state detectability and Lipschitz continuity of the landmark measurement model, with respect to typical SLAM sensor configurations, and introduce a streamlined method for the range measurement model. Simulation results validate the considered method, highlighting its efficacy and robustness to noise.

## Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - MHE
  - SLAM
  
# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
#hugoblox:
#  ids:
#    doi: 10.5555/123456


# Custom links
links:
  - type: pdf
    url: "https://arxiv.org/abs/2411.13310"
#  - type: code
#    url: https://github.com/HugoBlox/hugo-blox-builder
#  - type: dataset
#    url: https://github.com/HugoBlox/hugo-blox-builder
#  - type: slides
#    url: https://www.slideshare.net/
#  - type: source
#    url: https://github.com/HugoBlox/hugo-blox-builder
#  - type: video
#    url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

slides: ""
---

