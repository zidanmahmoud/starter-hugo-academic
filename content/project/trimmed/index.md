---
title: Isogeometric analyis of trimmed membrane structures
summary: A Project of the course Advanced FEM.
tags:
- Structural Analysis
- IGA
- Formfinding
date: "2018-08-15"

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
url_code: ""
url_pdf: "project/trimmed/trimmed.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

The task was to extend a given code for the IGA of untrimmed membranes to the application of trimmed IGA. IGA uses the CAD information as an analysis model, instead of constructing a separate computational model. In order to get accurate results, a k-refinement is performed on the geometrical model. To represent complex geometries trimmed NURBS geometries are employed. In this present work, form finding is done on trimmed membrane surfaces. This project is implemented using MATLAB for the analysis and Rhino to define the geometries.
