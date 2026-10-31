---
title: 'High-Dimensional Online Change Point Detection with Adaptive Thresholding and Interpretability'

authors:
  - Sven Jacob
  - Bardh Prenkaj
  - Weijia Shao
  - Gjergji Kasneci

date: '2026-09-21T00:00:00Z'
doi: '10.48550/arXiv.2609.24278'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

publication: *arXiv preprint* arXiv:2609.24278
publication_short: *arXiv*

abstract: 'Change point detection (CPD) identifies abrupt and significant changes in sequential data, with applications in human activity recognition, financial markets, cybersecurity, manufacturing, and autonomous systems. Traditional CPD methods often face computational challenges in high-dimensional settings and typically provide limited explanations for detected changes, which can restrict their practical usability. This paper introduces a CPD framework that improves scalability and interpretability by leveraging the Sliced Wasserstein (SW) distance. Our contributions are fourfold: (1) we transform multivariate sequential data into one-dimensional scores using the SW distance, making the resulting representation compatible with existing CPD methods; (2) we analyze the distributional behavior of random slices of the SW distance and show that, under suitable assumptions, they can be approximated by a Gamma distribution, providing a principled basis for threshold calibration; (3) we propose a self-adapting online CPD algorithm that combines this SW-based score with an adaptive quantile-based threshold; (4) we introduce a model-specific framework for generating contrastive explanations for annotated change points. Empirically, our method reduces false positives by at least $48\%$ on average compared with popular online and offline CPD baselines, while maintaining competitive or superior detection performance. Code is available at https://github.com/jsve96/SWCPD_Code. At the same time, it produces interpretable change-point annotations, making it practical for deployment in high-stakes applications.'

tags: ['change point detection','time series','interpretability']

featured: false

url_pdf: 'https://arxiv.org/pdf/2609.24278'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
