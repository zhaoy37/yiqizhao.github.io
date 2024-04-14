---
title: 'Fairguard: Harness Logic-based Fairness Rules in Smart Cities'
date: '2023-02-22'
authors:
- admin
- Ziyan An
- Xuqing Gao
- Ayan Mukhopadhyay
- Meiyi Ma
publication_types: 
- conference
publication: '8th ACM/IEEE Conference on Internet of Things Design and Implementation'

abstract: Smart cities operate on computational predictive frameworks that collect, aggregate, and utilize data from large-scale sensor networks. However, these frameworks are prone to multiple sources of data and algorithmic bias, which often lead to unfair prediction results. In this work, we first demonstrate that bias persists at a micro-level both temporally and spatially by studying real city data from Chattanooga, TN. To alleviate the issue of such bias, we introduce Fairguard, a micro-level temporal logic-based approach for fair smart city policy adjustment and generation in complex temporal-spatial domains. The Fairguard framework consists of two phases. First, we develop a static generator that is able to reduce data bias based on temporal logic conditions by minimizing correlations between selected attributes. Then, to ensure fairness in predictive algorithms, we design a dynamic component to regulate prediction results and generate future fair predictions by harnessing logic rules. Evaluations show that logic-enabled static Fairguard can effectively reduce the biased correlations while dynamic Fairguard can guarantee fairness on protected groups at run-time with minimal impact on overall performance.
# Summary. An optional shortened abstract.
summary: '<font color=DAB88B>IoTDI 23.</font> *A micro-level temporal logic-based approach for fair smart city policy adjustment and generation in complex temporal-spatial domains*'
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: "https://arxiv.org/pdf/2302.11137.pdf"
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
<small>Fairguard overview (feature data - demographic or socioeconomic feature values
associated with studied city regions, e.g., household mean income)</small>

</center>
---
