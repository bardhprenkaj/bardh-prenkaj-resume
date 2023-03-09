---
title: 'Latent and sequential prediction of the novel coronavirus epidemiological spread'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dario Aragona
  - Luca Podo
  - Bardh Prenkaj
  - Paola Velardi

date: '2021-10-20T00:00:00Z'
doi: '10.1145/3493499.3493500'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *ACM SIGAPP Applied Computing Review*

abstract: In this paper we present CoRoNNa a deep sequential framework for epidemic prediction that leverages a flexible combination of sequential and convolutional components to analyse the transmission of COVID-19 and, perhaps, other undiscovered viruses. Importantly, our methodology is generic and may be tailored to specific analysis goals. We exploit CoRoNNa to analyse the impact of various mobility containment policies on the pandemic using cumulative viral dissemination statistics with local demographic and movement data from several nations. Our experiments show that data on mobility has a significant, but delayed, impact on viral propagation. When compared to alternative frameworks that combine multivariate lagged predictors and basic LSTM models, CoRoNNa outperforms them. On the contrary, no technique based solely on lagged viral dissemination statistics can forecast daily cases.


tags: ['time series prediction', 'deep learning']

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
  caption: 'Comparison of the distribution of Normalised RMSE (NRMSE) of CoRoNNa+LSTM with the average performances
of CoRoNNa+GRU and CoRoNNa+RNN for all countries in examination'
  focal_point: ''
  preview_only: false


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---