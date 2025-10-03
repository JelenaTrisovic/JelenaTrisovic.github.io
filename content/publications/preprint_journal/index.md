---
title: "Uncertainty-Aware Perception-Based Control for Autonomous Racing"
authors:
- admin
- Andrea Carron
- Melanie N. Zeilinger

#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-07-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to IEEE Transactions on Control System Technology"
publication_short: ""

abstract: Autonomous systems operating in unknown environments often rely heavily on visual sensor data, yet making safe and informed control decisions based on these measurements remains a significant challenge. To facilitate the integration of perception and control in autonomous vehicles, we propose a novel perception-based control approach that incorporates road estimation, quantification of its uncertainty, and uncertainty-aware control based on this estimate. At the core of our method is a parametric road curvature model, optimized using visual measurements of the road through a constrained nonlinear optimization problem. This process ensures adherence to constraints on both model parameters and curvature. By leveraging the Frenet frame formulation, we embed the estimated track curvature into the system dynamics, allowing the controller to explicitly account for perception uncertainty and enhancing robustness to estimation errors based on visual input. We validate our approach in a simulated environment, using a high-fidelity 3D rendering engine, and demonstrate its effectiveness in achieving reliable and uncertainty-aware control for autonomous racing.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- MPC
- Perception-based control

featured: false

#hugoblox:
#  ids:
#    arxiv: 1512.04133v1

links:
- type: pdf
  url: "https://arxiv.org/abs/2508.02494"
#- type: preprint
#  provider: arxiv
#  id: 1512.04133v1
#- type: code
#  url: https://github.com/HugoBlox/hugo-blox-builder
#- type: slides
#  url: https://www.slideshare.net/
#- type: dataset
#  url: "#"
#- type: poster
#  url: "#"
#- type: source
#  url: "#"
#- type: video
#  url: https://youtube.com
#- type: custom
#  label: Custom Link
#  url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
 caption: 'The proposed method estimates the centerline of the
road using RGB-D images and ensures safety of the car
with respect to the road borders.'
 focal_point: ""
 preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---




