---
title: 'CURE: Controlled Unlearning for Robust Embeddings - Mitigating Conceptual Shortcuts in Pre-Trained Language Models'

authors:
  - Aysenur Kocak
  - Shuo Yang
  - Bardh Prenkaj
  - Gjergji Kasneci

date: '2025-11-04T00:00:00Z'
doi: '10.48550/arXiv.2509.05230'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

publication: In *Findings of the Association for Computational Linguistics: EMNLP 2025*
publication_short: In *Findings of EMNLP 2025*

abstract: 'Pre-trained language models have achieved remarkable success across diverse applications but remain susceptible to spurious, concept-driven correlations that impair robustness and fairness. In this work, we introduce CURE, a novel and lightweight framework that systematically disentangles and suppresses conceptual shortcuts while preserving essential content information. Our method first extracts concept-irrelevant representations via a dedicated content extractor reinforced by a reversal network, ensuring minimal loss of task-relevant information. A subsequent controllable debiasing module employs contrastive learning to finely adjust the influence of residual conceptual cues, enabling the model to either diminish harmful biases or harness beneficial correlations as appropriate for the target task. Evaluated on the IMDB and Yelp datasets using three pre-trained architectures, CURE achieves an absolute improvement of +10 points in F1 score on IMDB and +2 points on Yelp, while introducing minimal computational overhead. Our approach establishes a flexible, unsupervised blueprint for combating conceptual biases, paving the way for more reliable and fair language understanding systems.'

tags: ['LLMs','shortcut mitigation','machine unlearning']

featured: false

url_pdf: 'https://arxiv.org/pdf/2509.05230'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
