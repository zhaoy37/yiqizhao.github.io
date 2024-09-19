---
title: 'Formal Verification and Control with Conformal Prediction'
date: '2023-08-31'
authors:
- Lars Lindemann
- admin
- Xinyi Yu
- George J. Pappas
- Jyotirmoy V. Deshmukh
publication_types:
- preprint
publication: '*arXiv preprint arXiv:2409.00536*'

abstract: In this survey, we design formal verification and control algorithms for autonomous systems with practical safety guarantees using conformal prediction (CP), a statistical tool for uncertainty quantification. We focus on learning-enabled autonomous systems (LEASs) in which the complexity of learning-enabled components (LECs) is a major bottleneck that hampers the use of existing model-based verification and design techniques. Instead, we advocate for the use of CP, and we will demonstrate its use in formal verification, systems and control theory, and robotics. We argue that CP is specifically useful due to its simplicity (easy to understand, use, and modify), generality (requires no assumptions on learned models and data distributions, i.e., is distribution-free), and efficiency (real-time capable and accurate). We pursue the following goals with this survey. First, we provide an accessible introduction to CP for non-experts who are interested in using CP to solve problems in autonomy. Second, we show how to use CP for the verification of LECs, e.g., for verifying input-output properties of neural networks. Third and fourth, we review recent articles that use CP for safe control design as well as offline and online verification of LEASs. We summarize their ideas in a unifying framework that can deal with the complexity of LEASs in a computationally efficient manner. In our exposition, we consider simple system specifications, e.g., robot navigation tasks, as well as complex specifications formulated in temporal logic formalisms. Throughout our survey, we compare to other statistical techniques (e.g., scenario optimization, PAC-Bayes theory, etc.) and how these techniques have been used in verification and control. Lastly, we point the reader to open problems and future research directions.
# Summary. An optional shortened abstract.
summary: '*Survey on Formal Verification and Control with Conformal Prediction*'
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: "https://arxiv.org/pdf/2409.00536"
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
<small>Formal verification and control of LEASs.</small>

</center>
