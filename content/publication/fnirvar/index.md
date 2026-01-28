---
title: "Factor-Driven Network Informed Restricted Vector Autoregression"
draft: false

authors:
  - admin
  # If you have author profile folders for coauthors, add them here (recommended):
  # - mihai-cucuringu
  # - alessandra-luati
  # - francesco-sanna-passino
  #
  # If you *don’t* have profiles for coauthors, you can usually still list names
  # by creating profiles later, or keep just `admin` and put coauthors in the citation file.

date: "2025-11-14T00:00:00Z"
publishDate: "2025-11-14T00:00:00Z"

doi: "10.1145/3768292.3770412"

publication_types: ["paper-conference"]

publication: "In *Proceedings of the 6th ACM International Conference on AI in Finance (ICAIF ’25)*, pp. 431–439"
publication_short: "ICAIF ’25"

abstract: >
  High-dimensional financial time series often exhibit complex dependence relations driven by both common market structures and latent connections among assets. To capture these characteristics, this paper proposes Factor-Driven Network Informed Restricted Vector Autoregression (FNIRVAR), a model for the common and idiosyncratic components of high-dimensional time series with an underlying unobserved network structure. The common component is modelled by a static factor model, which allows for strong cross-sectional dependence, whilst a network vector autoregressive process captures the residual co-movements due to the idiosyncratic component. An assortative stochastic block model underlies the network VAR, leading to groups of highly co-moving variables in the idiosyncratic component. For estimation, a two-step procedure is proposed, whereby the static factors are estimated via principal component analysis, followed by estimation of the network VAR parameters. The method is demonstrated in financial applications to daily returns, intraday returns, and FRED-MD macroeconomic variables. In all cases, the proposed method outperforms a static factor model, as well as a static factor plus LASSO-estimated sparse VAR model, in terms of forecasting and financial performance metrics.

summary: "FNIRVAR: a factor-driven, network-informed restricted VAR for high-dimensional time series."

tags:
  - Time Series
  - Econometrics
  - Networks
  - Factor Models

# Buttons/links (use what you have)
url_source: "https://doi.org/10.1145/3768292.3770412"
url_pdf: "https://arxiv.org/pdf/2508.02198.pdf"
# url_code: "https://github.com/<your-repo>"
# url_slides: "https://<your-slides-link>"

# Optional featured image
# Place `featured.jpg` or `featured.png` in this folder.
image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---