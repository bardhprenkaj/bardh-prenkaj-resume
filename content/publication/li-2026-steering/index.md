---
title: 'Analysing the Safety Pitfalls of Steering Vectors'

authors:
  - Yuxiao Li
  - Alina Fastowski
  - Efstratios Zaradoukas
  - Bardh Prenkaj
  - Gjergji Kasneci

date: '2026-03-25T00:00:00Z'
doi: '10.48550/arXiv.2603.24543'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

publication: 'In *Findings of the Association for Computational Linguistics: ACL 2026*'
publication_short: 'In *Findings of ACL 2026*'

abstract: 'Activation steering has emerged as a powerful tool to shape LLM behavior without the need for weight updates. While its inherent brittleness and unreliability are well-documented, its safety implications remain underexplored. In this work, we present a systematic safety audit of steering vectors obtained with Contrastive Activation Addition (CAA), a widely used steering approach, under a unified evaluation protocol. Using JailbreakBench as benchmark, we show that steering vectors consistently influence the success rate of jailbreak attacks, with stronger amplification under simple template-based attacks. Across LLM families and sizes, steering the model in specific directions can drastically increase (up to 57%) or decrease (up to 50%) its attack success rate (ASR), depending on the targeted behavior. We attribute this phenomenon to the overlap between the steering vectors and the latent directions of refusal behavior. Thus, we offer a traceable explanation for this discovery. Together, our findings reveal the previously unobserved origin of this safety gap in LLMs, highlighting a trade-off between controllability and safety.'

tags: ['LLMs','AI safety']

featured: false

url_pdf: 'https://arxiv.org/pdf/2603.24543'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
