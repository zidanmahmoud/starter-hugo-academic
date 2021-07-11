---
title: Space-Time Finite Elements For 1D Heat Equation
summary: A Project of the course Software Lab.
tags:
- FEM
- transient FEM
date: "2018-11-15"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Wind Velocity Profile
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: "https://gitlab.lrz.de/ga73gix/2018_Software-Lab_SpaceTimeFEM"
url_poster: "project/spacetime/poster.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

An alternate method to model transient PDEs, where time is considered as a dimension, in contrast to the conventional transient FEM, where the space is discretized and a time intrgration scheme is applied. Thus, the 1D problem becomes 2D, and the shape functions are a tensor product of space and time. This approach is advntegous for its exponential convergence in time (when using high order shape functions), the ability to perform local time refinement, etc.
