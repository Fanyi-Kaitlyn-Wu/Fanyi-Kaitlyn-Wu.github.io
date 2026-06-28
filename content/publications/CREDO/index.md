---
title: "CREDO: Epistemic-Aware Conformalized Credal Envelopes for Regression"
authors:
- Luben M. C. Cabezas
- Sabina J. Sloman
- Bruno M. Resende
- admin
- Michele Caprio
- Rafael Izbicki
date: "2026-05-06T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05-06T00:00:00Z"

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "ArXiv Preprint"
publication_short: "ArXiv Preprint"
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ["article"]

# # Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

abstract: >-
  Conformal prediction delivers prediction intervals with distribution-free coverage, but its intervals can look overconfident in regions where the model is extrapolating, because standard conformal scores do not explicitly represent epistemic uncertainty. Credal methods, by contrast, make epistemic effects visible by working with sets of plausible predictive distributions, but they are typically model-based and lack calibration guarantees. We introduce CREDO, a simple "credal-then-conformalize" recipe that combines both strengths. CREDO first builds an interpretable credal envelope that widens when local evidence is weak, then applies split conformal calibration on top of this envelope to guarantee marginal coverage without further assumptions. This separation of roles yields prediction intervals that are interpretable: their width can be decomposed into aleatoric noise, epistemic inflation, and a distribution-free calibration slack. We provide a fast implementation based on trimming extreme posterior predictive endpoints, prove validity, and show on benchmark regressions that CREDO maintains target coverage while improving sparsity adaptivity at competitive efficiency.

# Summary. An optional shortened abstract.
summary: We show that optimisation and calibration can be decoupled for Conformal Prediction while maintaining valid marginal coverage guarantee.

tags:
- Conformal Prediction
- Credal sets

featured: false

# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

links:
- type: preprint
  provider: arxiv
  id: 2603.06826v1

# - type: code
#   url: https://github.com/HugoBlox/hugo-blox-builder
# - type: slides
#   url: B2CP_Fanyi.pdf
# - type: dataset
#   url: "#"
# - type: poster
#   url: DCO_eiml.pdf
# - type: source
#   url: "#"
# - type: video
#   url: https://youtube.com
# - type: custom
#   label: Custom Link
#   url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Classification results on ImageNet-A over 50 random splits. (a) Mean prediction set size. (b) Set size distributions. (c) Empirical coverage; dashed line marks 1 − α = 0.8. (d) P95 set size distributions.'
#   focal_point: ""
#   preview_only: false

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
