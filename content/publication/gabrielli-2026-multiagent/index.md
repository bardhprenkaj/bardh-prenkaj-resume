---
title: 'A Multi-Agent Framework for Interpreting Multivariate Physiological Time Series'

authors:
  - Davide Gabrielli
  - Paola Velardi
  - Stefano Faralli
  - Bardh Prenkaj

date: '2026-03-04T00:00:00Z'
doi: '10.48550/arXiv.2603.04142'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

publication: *arXiv preprint* arXiv:2603.04142
publication_short: *arXiv*

abstract: 'Continuous physiological monitoring is central to emergency care, yet deploying trustworthy AI is challenging. While LLMs can translate complex physiological signals into clinical narratives, it is unclear how agentic systems perform relative to zero-shot inference. To address these questions, we present Vivaldi, a role-structured multi-agent system that explains multivariate physiological time series. Due to regulatory constraints that preclude live deployment, we instantiate Vivaldi in a controlled, clinical pilot to a small, highly qualified cohort of emergency medicine experts, whose evaluations reveal a context-dependent picture that contrasts with prevailing assumptions that agentic reasoning uniformly improves performance. Our experiments show that agentic pipelines substantially benefit non-thinking and medically fine-tuned models, improving expert-rated explanation justification and relevance by +6.9 and +9.7 points, respectively. Contrarily, for thinking models, agentic orchestration often degrades explanation quality, including a 14-point drop in relevance, while improving diagnostic precision (ESI F1 +3.6). We also find that explicit tool-based computation is decisive for codifiable clinical metrics, whereas subjective targets, such as pain scores and length of stay, show limited or inconsistent changes. Expert evaluation further indicates that gains in clinical utility depend on visualization conventions, with medically specialized models achieving the most favorable trade-offs between utility and clarity. Together, these findings show that the value of agentic AI lies in the selective externalization of computation and structure rather than in maximal reasoning complexity, and highlight concrete design trade-offs and learned lessons, broadly applicable to explainable AI in safety-critical healthcare settings.'

tags: ['multi-agent systems','time series','healthcare']

featured: false

url_pdf: 'https://arxiv.org/pdf/2603.04142'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
