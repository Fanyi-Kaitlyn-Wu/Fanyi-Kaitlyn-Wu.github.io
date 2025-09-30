---
title: "Bayesian Infused Conformal Prediction"
authors:
- admin
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

abstract: We present a unified Bayesian decision-theoretic framework for conformal prediction (CP) that integrates Bayesian posterior predictive scores with risk minimization via Bayesian quadrature (BQ). This approach, named BQ-optimised Bayesian-infused Conformal Prediction (BCP), rewrites CP as a decision risk problem and uses Bayesian posterior predictive as non-conformity score. On sparse regression with the diabetes dataset, under prior misspecification, BCP corrects the prediction set to have 81.1 percent coverage, while traditional Bayesian credible intervals drop to 59.4 percent.  BQ-optimised BCP also achieves narrower intervals than traditional CP methods while maintaining the same coverage. In breast cancer classification, BCP matches classical CP with 81.2 percent coverage, and BQ optimization reduces the set size from 0.919 to 0.889. These results show that our framework provides sharper and more efficient prediction sets without sacrificing validity, offering a principled approach to uncertainty quantification in high-stakes applications.

# Summary. An optional shortened abstract.
summary: We present a unified Bayesian decision-theoretic framework for conformal prediction (CP) that integrates Bayesian posterior predictive scores with risk minimization via Bayesian quadrature (BQ).

tags:
- Machine Learning
- Conformal Prediction
- Bayesian statistics

featured: False

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
  url: Poster_Fanyi_Wu.pdf
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
