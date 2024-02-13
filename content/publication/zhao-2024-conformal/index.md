---
title: 'Conformal Predictive Programming for Chance Constrained Optimization'
date: '2024-02-12'
authors:
- admin
- Xinyi Yu
- Jyotirmoy V. Deshmukh
- Lars Lindemann
publication_types:
- preprint
publication: '*arXiv preprint arXiv:2402.07407*'

abstract: Motivated by the advances in conformal prediction (CP), we propose conformal predictive programming (CPP), an approach to solve chance constrained optimization (CCO) problems, i.e., optimization problems with nonlinear constraint functions affected by arbitrary random parameters. CPP utilizes samples from these random parameters along with the quantile lemma – which is central to CP – to transform the CCO problem into a deterministic optimization problem. We then present two tractable reformulations of CPP by (1) writing the quantile as a linear program along with its KKT conditions (CPP-KKT), and (2) using mixed integer programming (CPP-MIP). CPP comes with marginal probabilistic feasibility guarantees for the CCO problem that are conceptually different from existing approaches, e.g., the sample approximation and the scenario approach. While we explore algorithmic similarities with the sample approximation approach, we emphasize that the strength of CPP is that it can easily be extended to incorporate different variants of CP. To illustrate this, we present robust conformal predictive programming to deal with distribution shifts in the uncertain parameters of the CCO problem.

# Summary. An optional shortened abstract.
summary: '*Using Conformal Prediction to solve Chance Constrained Optimization Problems*'
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: "https://arxiv.org/pdf/2402.07407.pdf"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: true

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
# slides: example
---


<center>

![MKCT_workflow](featured.png)
<small>Conformal Predictive Programming</small>

</center>
