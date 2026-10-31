---
title: 'Beyond Binary Rewards: A Comparative Study of Reward Design for Reinforcement Unlearning'

authors:
  - Efstratios Zaradoukas
  - Davide Gabrielli
  - Bardh Prenkaj
  - Gjergji Kasneci

date: '2026-07-30T00:00:00Z'
doi: '10.48550/arXiv.2607.27968'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

publication: '*arXiv preprint* arXiv:2607.27968'
publication_short: '*arXiv*'

abstract: 'Machine unlearning seeks to selectively remove specific knowledge from trained language models without full retraining, a growing necessity under privacy regulations such as GDPR and the EU AI Act. Recent work has reformulated unlearning as a Reinforcement Learning with Verifiable Rewards (RLVR) problem, where models are optimized against verifiable rewards computed directly from their outputs. However, existing methods rely on sparse binary rewards that provide minimal learning signal, indicating only whether forbidden content was avoided, and limiting convergence speed. In this paper, we study how reward design affects unlearning efficiency within the Reinforcement Unlearning (RUL) framework. We introduce a principled reward decomposition framework that decouples verifiability from sparsity, and propose two new reward functions: an exponential reward that provides graded penalties based on the count of forbidden-concept occurrences, and a PageRank inspired reward that weights penalties by semantic importance. We conduct experiments on the Real World Knowledge Unlearning (RWKU) benchmark, demonstrating that both rewards consistently outperform the binary setting, while reaching similar forgetting performance up to $3\times$ faster and preserving general model utility. Our results show that reward design is a key driver of unlearning efficiency offering a practical path toward scalable and efficient machine unlearning.'

tags: ['machine unlearning','reinforcement learning','LLMs']

featured: false

url_pdf: 'https://arxiv.org/pdf/2607.27968'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
