---
title: 'Doubling Your Data in Minutes: Ultra-fast Tabular Data Generation via LLM-Induced Dependency Graphs'

authors:
  - Shuo Yang
  - Zheyu Zhang
  - Bardh Prenkaj
  - Gjergji Kasneci

date: '2025-11-04T00:00:00Z'
doi: '10.48550/arXiv.2507.19334'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

publication: 'In *Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing*'
publication_short: 'In *EMNLP 2025*'

abstract: 'Tabular data is critical across diverse domains, yet high-quality datasets remain scarce due to privacy concerns and the cost of collection. Contemporary approaches adopt large language models (LLMs) for tabular augmentation, but exhibit two major limitations: (1) dense dependency modeling among tabular features that can introduce bias, and (2) high computational overhead in sampling. To address these issues, we propose SPADA for SPArse Dependency-driven Augmentation, a lightweight generative framework that explicitly captures sparse dependencies via an LLM-induced graph. We treat each feature as a node and synthesize values by traversing the graph, conditioning each feature solely on its parent nodes. We explore two synthesis strategies: a non-parametric method using Gaussian kernel density estimation, and a conditional normalizing flow model that learns invertible mappings for conditional density estimation. Experiments on four datasets show that SPADA reduces constraint violations by 4% compared to diffusion-based methods and accelerates generation by nearly 9,500 times over LLM-based baselines.'

tags: ['tabular data generation','LLMs']

featured: false

url_pdf: 'https://arxiv.org/pdf/2507.19334'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
