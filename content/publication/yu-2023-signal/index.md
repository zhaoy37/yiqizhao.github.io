---
title: 'Signal Temporal Logic Control Synthesis among Uncontrollable Dynamic Agents with Conformal Prediction'
date: '2023-12-07'
authors:
- Xinyi Yu
- admin
- Xiang Yin
- Lars Lindemann
publication_types:
- preprint
publication: '*arXiv preprint arXiv:2311.04242*'

abstract: The control of dynamical systems under temporal logic specifications among uncontrollable dynamic agents is challenging due to the agents' a-priori unknown behavior. Existing works have considered the problem where either all agents are controllable, the agent models are deterministic and known, or no safety guarantees are provided. We propose a predictive control synthesis framework that guarantees, with high probability, the satisfaction of signal temporal logic (STL) tasks that are defined over the system and uncontrollable stochastic agents. We use trajectory predictors and conformal prediction to construct probabilistic prediction regions for each uncontrollable agent that are valid over multiple future time steps. Specifically, we reduce conservatism and increase data efficiency compared to existing works by constructing a normalized prediction region over all agents and time steps. We then formulate a worst-case mixed integer program (MIP) that accounts for all agent realizations within the prediction region to obtain control inputs that provably guarantee task satisfaction with high probability. To efficiently solve this MIP, we propose an equivalent MIP program based on KKT conditions of the original one. We illustrate our control synthesis framework on two case studies.
# Summary. An optional shortened abstract.
summary: '*STL control synthesis among uncontrollable agents*'
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: "https://arxiv.org/pdf/2312.04242.pdf"
url_code: 'https://github.com/SAIDS-Lab/STL-Synthesis-among-Uncontrollable-Agents'
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
<small>The result of the temperature control of the first case study.</small>

</center>
