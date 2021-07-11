---
title: Immersed Boundary pisoFoam Solver
summary: A Project of the course Simulation of Thermofluids with Open-Source Software.
tags:
- CFD
date: "2019-08-28"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Flow around a cylinder using pisoIbFoam.
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: "project/openfoam/report.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

To address the computations of solid particles in a fluid flow, one has to solve the transient
Navier-Stokes (NS) equations in the fluid domain with the imposition of no-slip boundary con-
dition at the interface between the fluid domain and the solid object. One way to achieve this
is by the application of arbitrary Lagrangian-Eulerian method, which combines the advantages
of both Lagrangian descripton following an individual parcel as it moves through space and
Eulerian description focusing on specific locations in the space. However, this method requires
adaptive meshing depending on solid particles displacements as time evolves and therefore leads
to a substantial computational cost. To avoid repeated re-meshing, the whole computational
domain containing the fluid and the solid is meshed with a fixed structured cartesian grid. As a
result, the grid will most probably not conform to the solids boundary. Here, the introduction
of the solid phase to the governing flow equations is achieved by adequately formulating the
source term marked in the NS equation.

