---
title: 'Beyond Edge Deletion: A Comprehensive Approach to Counterfactual Explanation in Graph Neural Networks'

authors:
  - Matteo De Sanctis
  - Riccardo De Sanctis
  - Stefano Faralli
  - Paola Velardi
  - Bardh Prenkaj

date: '2026-03-04T00:00:00Z'
doi: '10.48550/arXiv.2603.04209'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

publication: '*arXiv preprint* arXiv:2603.04209'
publication_short: '*arXiv*'

abstract: 'Graph Neural Networks (GNNs) are increasingly adopted across domains such as molecular biology and social network analysis, yet their black-box nature hinders interpretability and trust. This is especially problematic in high-stakes applications, such as predicting molecule toxicity, drug discovery, or guiding financial fraud detections, where transparent explanations are essential. Counterfactual explanations - minimal changes that flip a model''s prediction - offer a transparent lens into GNNs''behavior. In this work, we introduce XPlore, a novel technique that significantly broadens the counterfactual search space. It consists of gradient-guided perturbations to adjacency and node feature matrices. Unlike most prior methods, which focus solely on edge deletions, our approach belongs to the growing class of techniques that optimize edge insertions and node-feature perturbations, here jointly performed under a unified gradient-based framework, enabling a richer and more nuanced exploration of counterfactuals. To quantify both structural and semantic fidelity, we introduce a cosine similarity metric for learned graph embeddings that addresses a key limitation of traditional distance-based metrics, and demonstrate that XPlore produces more coherent and minimal counterfactuals. Empirical results on 13 real-world and 5 synthetic benchmarks show up to +56.3% improvement in validity and +52.8% in fidelity over state-of-the-art baselines, while retaining competitive runtime.'

tags: ['explainability','graph learning']

featured: false

url_pdf: 'https://arxiv.org/pdf/2603.04209'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
