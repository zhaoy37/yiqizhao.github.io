---
title: 'Robust Conformal Prediction for STL Runtime Verification under Distribution Shift'
date: '2023-11-16'
authors:
- admin
- Bardh Hoxha
- Georgios Fainekos
- Jyotirmoy V. Deshmukh
- Lars Lindemann
publication_types:
- preprint
publication: '*arXiv preprint arXiv:2311.09482*'

abstract: Cyber-physical systems (CPS) designed in simulators behave differently in the real-world. Once they are deployed in the real-world, we would hence like to predict system failures during runtime. We propose robust predictive runtime verification (RPRV) algorithms under signal temporal logic (STL) tasks for general stochastic CPS. The RPRV problem faces several challenges (1) there may not be sufficient data of the behavior of the deployed CPS, (2) predictive models are based on a distribution over system trajectories encountered during the design phase, i.e., there may be a distribution shift during deployment. To address these challenges, we assume to know an upper bound on the statistical distance (in terms of an f-divergence) between the distributions at deployment and design time, and we utilize techniques based on robust conformal prediction. Motivated by our results in [1], we construct an accurate and an interpretable RPRV algorithm. We use a trajectory prediction model to estimate the system behavior at runtime and robust conformal prediction to obtain probabilistic guarantees by accounting for distribution shifts. We precisely quantify the relationship between calibration data, desired confidence, and permissible distribution shift. To the best of our knowledge, these are the first statistically valid algorithms under distribution shift in this setting. We empirically validate our algorithms on a Franka manipulator within the NVIDIA Isaac sim environment.
# Summary. An optional shortened abstract.
summary: '*STL runtime verification algorithms robust to distribution shift*'
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: "https://arxiv.org/pdf/2311.09482.pdf"
url_code: 'https://github.com/SAIDS-Lab/Robust-Conformal-Prediction-for-STL-Runtime-Verification-under-Distribution-Shift'
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
<small>Left: A robotic arm manipulating a box in the presence of a human. Right: The robotic
arm performing the same task when the human behavior and the package location changed. We
propose predictive robust runtime verification algorithms to verify systems under such distribution
shift.</small>

</center>
