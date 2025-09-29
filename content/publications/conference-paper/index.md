---
title: THCM-CAL Temporal-Hierarchical Causal Modelling with Conformal Calibration for Clinical Risk Prediction

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xin Zhang
  - Qiyu Wei
  - Yingjie Zhu
  - admin
  - Sophia Ananiadou

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: 2025-06-21T22:43:42Z
publishDate: 2025-06-21T22:43:42Z

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: EMNLP 2025
publication_short: EMNLP 2025

abstract: >
  Automated clinical risk prediction from electronic health records (EHRs) demands modeling both structured diagnostic codes and unstructured narrative notes. However, most prior approaches either handle these modalities separately or rely on simplistic fusion strategies that ignore the directional, hierarchical causal interactions by which narrative observations precipitate diagnoses and propagate risk across admissions. In this paper, we propose THCM-CAL, a Temporal-Hierarchical Causal Model with Conformal Calibration. Our framework constructs a multimodal causal graph where nodes represent clinical entities from two modalities: Textual propositions extracted from notes and ICD codes mapped to textual descriptions. Through hierarchical causal discovery, THCM-CAL infers three clinically grounded interactions: intra-slice same-modality sequencing, intra-slice cross-modality triggers, and inter-slice risk propagation. To enhance prediction reliability, we extend conformal prediction to multi-label ICD coding, calibrating per-code confidence intervals under complex co-occurrences. Experimental results on MIMIC-III and MIMIC-IV demonstrate the superiority of THCM-CAL.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Computation and Language 
  - Artificial Intelligence 

# Display this page in the Featured widget?
featured: True

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.48550

# Custom links
links:
  - type: pdf
    url: ""
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview of THCM-CAL. A four-stage pipeline for clinical risk prediction, which consists of: (1) Extracting diagnostic propositions and normalize ICD descriptions, (2) Embeding nodes with BERT, (3) Building and fuse a temporal–hierarchical causal graph via Gumbel–Softmax and message passing, and (4) Appling split conformal prediction for calibrated multi-label ICD coding.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- > [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example. -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
