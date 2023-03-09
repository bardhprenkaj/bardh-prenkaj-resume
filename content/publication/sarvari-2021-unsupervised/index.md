---
title: 'Unsupervised boosting-based autoencoder ensembles for outlier detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hamed Sarvari
  - Carlotta Domeniconi
  - Bardh Prenkaj
  - Giovanni Stilo

date: '2021-05-11T00:00:00Z'
doi: '10.1007/978-3-030-75762-5_8'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Pacific-Asia Conference on Knowledge Discovery and Data Mining 2021*

abstract: Autoencoders have been recently applied to outlier detection. However, neural networks are known to be vulnerable to overfitting, and therefore have limited potential in the unsupervised outlier detection setting. The majority of existing deep learning methods for anomaly detection is sensitive to contamination of the training data to anomalous instances. To overcome the aforementioned limitations we develop a Boosting-based Autoencoder Ensemble approach (BAE). BAE is an unsupervised ensemble method that, similarly to boosting, builds an adaptive cascade of autoencoders to achieve improved and robust results. BAE trains the autoencoder components sequentially by performing a weighted sampling of the data, aimed at reducing the amount of outliers used during training, and at injecting diversity in the ensemble. We perform extensive experiments and show that the proposed methodology outperforms state-of-the-art approaches under a variety of conditions.


tags: ['anomaly detection']

# Display this page in the Featured widget?
featured: true

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
  caption: 'This is how BAE works.'
  focal_point: ''
  preview_only: false


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---