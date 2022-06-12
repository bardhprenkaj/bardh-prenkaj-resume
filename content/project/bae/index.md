---
title: Boosting-based Autoencoder
summary: BAE is an unsupervised ensemble method that builds an adaptive cascade of autoencoders to achieve improved and robust results. BAE trains the autoencoder components sequentially by performing a weighted sampling of the data, aimed at reducing the amount of outliers used during training, and at injecting diversity in the ensemble.
tags:
  - Anomaly detection
date: '2019-01-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
url_code: 'https://gitlab.com/bardhp95/bae' # change to github
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

• Adapted boosting mechanisms on simple autoencoders for outlier detection purposes specialised in discarding outliers in each boosting iteration.

• Surpassed state-of-the-art and classic anomaly detection strategies achieving an average AUCPR score of 46.2%.

• Examined the relationship between the data distribution and the correct prediction rate of BAE with respect to the other approaches proposed in the literature.

• Performed exhaustive experiments on the performances of BAE and their superiority on all test-beds according to statistical significance methods.

• Collaborated in writing and formalising the methodology’s workflow by relying on mathematical notation of algebra and first order logic.
