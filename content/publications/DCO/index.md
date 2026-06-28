---
title: "Decoupled Conformal Optimisation: Efficient Prediction Sets via Independent Tuning and Calibration"
authors:
- admin
- Lihua Niu
- Samuel Kaski
- Michele Caprio
date: "2025-09-29T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-29T00:00:00Z"

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ICML EIML Workshop 2026
publication_short: ICML EIML Workshop 2026
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ["article"]

# # Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

abstract: Bayesian conformal optimisation methods often use the same held-out data both to search for efficient prediction sets and to certify coverage or risk. This coupling is natural for high-probability risk-control guarantees, but it is not necessary when the target is standard finite-sample marginal conformal coverage. We propose Decoupled Conformal Optimisation (DCO), a train-tunecalibrate design principle that uses an independent tuning split for efficiency-oriented structural selection and a fresh calibration split for the final conformal quantile. Conditional on the tuned structure, standard split-conformal exchangeability yields finite-sample marginal coverage for any candidate class, without a confidence parameter or multiple-testing correction. DCO therefore targets a different finite-sample guarantee from PAC-style methods: marginal conformal coverage rather than high-probability risk control. Under consistency assumptions on the coupled risk bound, the two approaches nevertheless converge to the same population threshold. Across classification and regression benchmarks, including ImageNet-A, CIFAR-100, Diabetes, California Housing, and Concrete, DCO tracks the nominal coverage level closely while often reducing average prediction-set size or interval width relative to PAC-style calibration. On ImageNet-A, for example, the average set size decreases from 26.52 to 25.26 and the 95th-percentile set size from 58.95 to 53.73; on Diabetes, the average interval width decreases from 2.098 to 1.914.

# Summary. An optional shortened abstract.
summary: We show that optimisation and calibration can be decoupled for Conformal Prediction while maintaining valid marginal coverage guarantee.

tags:
- Machine Learning
- Conformal Prediction

featured: True

# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

links:
- type: preprint
  provider: arxiv
  id: 2605.18354v1

# - type: code
#   url: https://github.com/HugoBlox/hugo-blox-builder
# - type: slides
#   url: B2CP_Fanyi.pdf
# - type: dataset
#   url: "#"
- type: poster
  url: DCO_eiml.pdf
# - type: source
#   url: "#"
# - type: video
#   url: https://youtube.com
# - type: custom
#   label: Custom Link
#   url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Coupled calibration versus DCO-Warmstart. In CRC/BQ-style calibration, the same calibration split is used both to search for an efficient threshold and to certify risk. DCO-Warmstart separates these roles: Dtune is used for score/model/hyperparameter selection, while Dcal is reserved exclusively for the final conformal quantile. This separation is the key condition that allows the standard split-conformal exchangeability argument to apply after tuning.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
