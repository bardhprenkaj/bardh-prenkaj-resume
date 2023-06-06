---
title: 'CoRoNNa: a deep sequential framework to predict epidemic spread'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dario Aragona
  - Luca Podo
  - Bardh Prenkaj
  - Paola Velardi

date: '2021-03-22T00:00:00Z'
doi: '10.1145/3412841.3441883'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 36th Annual ACM Symposium on Applied Computing*
publication_short: In *SAC 2021*

abstract: We propose CoRoNNa, a deep framework for epidemic prediction to analyse the spread of COVID-19 and, potentially, of other unknown viruses, based on a flexible integration of sequential and convolutional components. Importantly, our framework is general and can be specialised according to different analysis objectives. In this paper, the specific purpose is to optimise CoRoNNa for analysing the impact of different mobility containment policies on the epidemic. To this end, we integrate cumulative viral diffusion statistics and local demographic and mobility information of several countries. Our analysis confirms that mobility data have a strong, but delayed, effect on the viral spread. In this context, CoRoNNa has superior performances when compared with other frameworks that incorporate multivariate lagged predictors, and with simple LSTM models. On the contrary, no method is able to predict daily cases based only on lagged viral diffusion statistics.


tags: ['time series', 'deep learning']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Detailed view of a single CoRoNNa block with a simple RNN component (a) and an LSTM cell (b)'
  focal_point: ''
  preview_only: false


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---