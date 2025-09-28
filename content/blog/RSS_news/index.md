---
title: 🎉 Presented my first poster at 2025 RSS Conference
summary: Presented poster'Bayesian Infused Conformal Prediction' at 2025 RSS (Royal Statistical Society) in Edinburgh
date: 2025-09-03

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Photo crdeit to: [Yunqi Zhang](https://www.linkedin.com/in/yunqi-zhang-407008258/)'

authors:
  - admin

tags:
  - Academic
  - Poster
  - Conference

content_meta:
  trending: true
---

 Presented poster'Bayesian Infused Conformal Prediction' at 2025 RSS (Royal Statistical Society) in Edinburgh

{{< toc mobile_only=true is_open=true >}}

## Poster Summary

Conformal Prediction (CP) is a frequentist method that constructs prediction regions with guaranteed marginal coverage, requiring no distributional assumptions beyond exchangeability. These regions contain the true outcome with a user pre-specified probability (1−α), regardless of the underlying (exchangeable) data distribution. This ability to provide reliable uncertainty quantification makes CP especially valuable in domains such as medicine, finance, and machine learning, where trustworthy decision-making is critical.

On the other hand, Bayesian prediction provides well-calibrated uncertainty when the assumed model is correct but may exhibit poor coverage under model misspecification (M-open perspective). CP addresses this limitation by providing finite-sample statistical guarantees without requiring model fidelity. Incorporating the Bayesian mechanism into CP can make the prediction more efficient and informative.

Fong and Holmes (2021) showed that Bayesian posterior predictive distributions can be used as nonconformity scores to correct Bayesian model misspecification and guarantee frequentist-style coverage. We have shown that this method achieves Type-2 validity, as traditional CP does, thereby not only ensuring the marginal coverage property of BCP but also highlighting the frequentist characteristics of the Bayesian procedure. Furthermore, Vovk et al. (2005, Theorem 2.10) established that conformal predictors are at least conservatively valid. Building on this property, we examine how nonconformity scores derived from posterior predictive distributions can preserve statistical guarantees while producing more efficient prediction regions. Finally, Snell & Griffiths (2025) showed that CP can be re-written as a decision risk problem and proposed a Bayesian Quadrature framework that treated conformal prediction as risk integration, thereby enabling more efficient and interpretable prediction sets. This method provides us with insights for optimizing BCP by reformulating it as a decision risk problem and minimising the set size by selecting thresholds that minimize expected risk while still meeting the coverage guarantee.

This project seeks to combine Bayesian and frequentist CP in a way that ensures coverage while systematically optimizing the size of prediction sets. Our objective is to develop methodologies that leverage the strengths of both paradigms—incorporating structured prior information from Bayesian statistics while maintaining the rigorous coverage guarantees of conformal prediction. We also explore the potential applications of these enhanced methods across a variety of domains.
