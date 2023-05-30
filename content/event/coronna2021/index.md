---
title: CoRoNNa, A Deep Sequential Framework to Predict Epidemic Spread


event: SAC21, Proceedings of the 36th Annual ACM Symposium on Applied Computing
event_url: http://www.sigapp.org/sac/sac2021/

location: Online

summary: CoRoNNa is a deep framework for epidemic prediction that integrates mobility data and demographic information to analyze the impact of containment policies on COVID-19 spread.
abstract: We propose CoRoNNa, a deep framework for epidemic prediction to analyse the spread of COVID-19 and, potentially, of other  unknown viruses, based on a flexible integration of  sequential and convolutional  components. Importantly, our framework is general and can be specialised according to  different analysis objectives. In this paper, the specific purpose is to optimise CoRoNNa for analysing the impact of different mobility containment policies on the epidemic. To this end, we integrate cumulative viral diffusion statistics and local demographic and mobility information of several countries. Our analysis confirms that mobility data have a strong, but delayed, effect on the viral spread. In this context, CoRoNNa has superior performances when compared with other frameworks that incorporate multivariate lagged predictors, and with  simple LSTM models. On the contrary, no method is able to predict daily cases based only on lagged viral diffusion statistics.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2021-03-22T18:00:00Z'
date_end: '2021-03-22T18:10:00Z'
all_day: false

authors: [Dario Aragona, Luca Podo, Bardh Prenkaj, Paola Velardi]
tags: [time series, deep learning]

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Workflow to generate and test an improved version of the Plotly dataset'
#  focal_point: Right


# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3412841.3441883'
url_slides: ../../../uploads/conference_slides/SAC2021.pdf'
url_video: 'https://drive.google.com/file/d/1r_dCz6ZvwI1kSqzNiYAXucye1A4NroeB/view?usp=share_link'
# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---