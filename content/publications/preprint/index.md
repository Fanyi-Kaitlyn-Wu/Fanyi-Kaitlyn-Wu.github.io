---
title: "Bayesian Conformal Prediction as a Decision Risk Problem"
authors:
- admin
- Veronika Lohmanova
- Samuel Kaski
- Michele Caprio
date: "2025-09-29T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-29T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We propose an optimised Bayesian Conformal Prediction (BCP) framework that selects the conformal threshold via a decision-theoretic risk minimisation criterion. BCP uses Bayesian posterior predictive densities as non-conformity scores and Bayesian quadrature to estimate and minimise the expected prediction set size. Operating within a split conformal framework, BCP provides valid coverage guarantees and demonstrates reliable empirical coverage under model misspecification. Across regression and classification tasks, including distribution-shifted settings such as ImageNet-A, BCP yields prediction sets of comparable size to split conformal prediction, while exhibiting substantially lower run-to-run variability in set size. In sparse regression with nominal coverage of 80 percent, BCP achieves 81 percent empirical coverage under a misspecified prior, whereas Bayesian credible intervals under-cover at 49 percent.

# Summary. An optional shortened abstract.
summary: We present a unified Bayesian decision-theoretic framework for conformal prediction (CP) that integrates Bayesian posterior predictive scores with risk minimization via Bayesian quadrature (BQ).

tags:
- Machine Learning
- Conformal Prediction
- Bayesian statistics

featured: True

# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

links:
# - type: preprint
#   provider: arxiv
#   id: 1512.04133v1
# - type: code
#   url: https://github.com/HugoBlox/hugo-blox-builder
- type: slides
  url: B2CP_Fanyi.pdf
# - type: dataset
#   url: "#"
- type: poster
  url: Poster_WUML_2026.pdf
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
  caption: 'Comparison between Bayesian prediction and Bayesian Conformal Prediction (BCP) under different prior scales. (a) Coverage vs. average interval width. (b) Interval visualization for individual test samples. (c, d) Interval widths for a range of test cases with prior scale c=0.02 (misspecified) and c=1 (well-specified).'
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
