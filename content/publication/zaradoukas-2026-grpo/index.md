---
title: 'Reinforcement Unlearning via Group Relative Policy Optimization'

authors:
  - Efstratios Zaradoukas
  - Bardh Prenkaj
  - Gjergji Kasneci

date: '2026-04-23T00:00:00Z'
doi: '10.48550/arXiv.2601.20568'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

publication: In *Proceedings of the 14th International Conference on Learning Representations*
publication_short: In *ICLR 2026*

abstract: 'During pretraining, LLMs inadvertently memorize sensitive or copyrighted data, posing significant compliance challenges under legal frameworks like the GDPR and the EU AI Act. Fulfilling these mandates demands techniques that can remove information from a deployed model without retraining from scratch. Existing unlearning approaches attempt to address this need, but often leak the very data they aim to erase, sacrifice fluency and robustness, or depend on costly external reward models. We introduce PURGE (Policy Unlearning through Relative Group Erasure), a novel method grounded in the Group Relative Policy Optimization framework that formulates unlearning as a verifiable problem. PURGE uses an intrinsic reward signal that penalizes any mention of forbidden concepts, allowing safe and consistent unlearning. Our approach achieves up to x46 lower token usage per target than state-of-the-art methods, while improving fluency by +5.48% and adversarial robustness by +12.02% over the base model. Extensive evaluation on the Real World Knowledge Unlearning (RWKU) benchmark shows that PURGE reaches 11% unlearning effectiveness while preserving 98% of original utility. PURGE shows that framing LLM unlearning as a verifiable task enables more reliable, efficient, and scalable forgetting, suggesting a promising new direction for unlearning research that combines theoretical guarantees, improved safety, and practical deployment efficiency.'

tags: ['machine unlearning','reinforcement learning','LLMs']

featured: false

url_pdf: 'https://arxiv.org/pdf/2601.20568'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
