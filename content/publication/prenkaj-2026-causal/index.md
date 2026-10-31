---
title: 'Causal Routing for Unlearning'

authors:
  - Bardh Prenkaj
  - Andrea D'Angelo
  - Davide Mottin
  - Federico Fontana
  - Davide Gabrielli
  - Paola Velardi
  - Stefano Faralli

date: '2026-09-28T00:00:00Z'
doi: '10.48550/arXiv.2609.34475'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

publication: *arXiv preprint* arXiv:2609.34475
publication_short: *arXiv*

abstract: 'LLMs cannot forget the way we delete a file. Strangely, we are asked to remove something that was never put anywhere in particular. What the model took from a piece of text is now smeared across billions of weights. Existing methods rewrite all of them to change one thing, and none of them say which part produced that change. To address this, we introduce Causal Routing for Unlearning (CRU) by asking where the concept is expressed in the model and suppressing only that part. One untrained forward pass over the forget set ranks neurons by how their activations vary. Then, small routing modules on those neurons gate and suppress only the concepts that need to be forgotten. In CRU, the base model is frozen, and any change in behavior is caused only by the gated neurons; hence, why the routing is causal. Due to our parameter efficiency (only ~0.01% as many parameters as the base model), unlearning a concept costs 14 GiB, whereas the baselines require 71 GiB. On TOFU, CRU is indistinguishable from the retained model (p>0.05, KS test) and is never Pareto-dominated, whereas every compared baseline matches its forgetting on the larger-forget batches only by collapsing utility. On RWKU, it achieves an adversarial-probe recall of 0.052, compared to 0.250 for the strongest baseline, meaning the knowledge is gone, not merely harder to reach. Thus, deciding on the intervention at query time, rather than fixing it beforehand, is the axis along which we argue that unlearning should proceed.'

tags: ['machine unlearning','causality','LLMs']

featured: false

url_pdf: 'https://arxiv.org/pdf/2609.34475'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
