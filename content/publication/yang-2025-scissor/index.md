---
title: 'SCISSOR: Mitigating Semantic Bias through Cluster-Aware Siamese Networks for Robust Classification'

authors:
  - Shuo Yang
  - Bardh Prenkaj
  - Gjergji Kasneci

date: '2025-07-13T00:00:00Z'
doi: '10.48550/arXiv.2506.14587'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

publication: In *Proceedings of the 42nd International Conference on Machine Learning*
publication_short: In *ICML 2025*

abstract: 'Shortcut learning undermines model generalization to out-of-distribution data. While the literature attributes shortcuts to biases in superficial features, we show that imbalances in the semantic distribution of sample embeddings induce spurious semantic correlations, compromising model robustness. To address this issue, we propose SCISSOR (Semantic Cluster Intervention for Suppressing ShORtcut), a Siamese network-based debiasing approach that remaps the semantic space by discouraging latent clusters exploited as shortcuts. Unlike prior data-debiasing approaches, SCISSOR eliminates the need for data augmentation and rewriting. We evaluate SCISSOR on 6 models across 4 benchmarks: Chest-XRay and Not-MNIST in computer vision, and GYAFC and Yelp in NLP tasks. Compared to several baselines, SCISSOR reports +5.3 absolute points in F1 score on GYAFC, +7.3 on Yelp, +7.7 on Chest-XRay, and +1 on Not-MNIST. SCISSOR is also highly advantageous for lightweight models with ~9.5% improvement on F1 for ViT on computer vision datasets and ~11.9% for BERT on NLP. Our study redefines the landscape of model generalization by addressing overlooked semantic biases, establishing SCISSOR as a foundational framework for mitigating shortcut learning and fostering more robust, bias-resistant AI systems.'

tags: ['deep learning','shortcut mitigation']

featured: false

url_pdf: 'https://arxiv.org/pdf/2506.14587'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
