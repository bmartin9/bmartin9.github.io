---
title: "NIRVAR: Network Informed Restricted Vector Autoregression"
authors:
- admin
date: "2024-08-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: High-dimensional panels of time series arise in many scientific disciplines such as neuroscience, finance,
          and macroeconomics. Often, co-movements within groups of the panel components occur. Extracting these
          groupings from the data provides a course-grained description of the complex system in question and can in-
          form subsequent prediction tasks. We develop a novel methodology to model such a panel as a restricted vector
          autoregressive process, where the coefficient matrix is the weighted adjacency matrix of a stochastic block
          model. This network time series model, which we call the Network Informed Restricted Vector Autoregres-
          sion (NIRVAR) model, yields a coefficient matrix that has a sparse block-diagonal structure. We propose an
          estimation procedure that embeds each panel component in a low-dimensional latent space and clusters the
          embedded points to recover the blocks of the coefficient matrix. Crucially, the method allows for network-
          based time series modelling when the underlying network is unobserved. We derive the bias, consistency and
          asymptotic normality of the NIRVAR estimator. Simulation studies suggest that the NIRVAR estimated embed-
          ded points are Gaussian distributed around the ground truth latent positions. On three applications to finance,
          macroeconomics, and transportation systems, NIRVAR outperforms competing models in terms of prediction
          and provides interpretable results regarding group recovery.

# Summary. An optional shortened abstract.
summary: Combining Vector Autoregressive Models with Stochastic Blockmodels
tags:
- Network Time Series

featured: true

links:
- name: arxiv
  url: https://arxiv.org/abs/2407.13314
  url_pdf: https://arxiv.org/pdf/2407.13314
  url_code: 'https://github.com/bmartin9/NIRVAR'
url_dataset: ''
url_poster: Imperial_PhD_Symposiam.pdf
url_project: ''
url_slides: UIUC_Slides_15-10-24.pdf
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
