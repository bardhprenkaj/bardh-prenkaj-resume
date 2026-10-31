---
title: 'TabSCM: A practical Framework for Generating Realistic Tabular Data'

authors:
  - Sven Jacob
  - Bardh Prenkaj
  - Weijia Shao
  - Gjergji Kasneci

date: '2026-04-24T00:00:00Z'
doi: '10.48550/arXiv.2604.22337'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

publication: '*arXiv preprint* arXiv:2604.22337'
publication_short: '*arXiv*'

abstract: 'Most tabular-data generators match marginal statistics yet ignore causal structure, leading downstream models to learn spurious or unfair patterns. We present TabSCM, a mixed-type generator that preserves those causal dependencies. Starting from a Completed Partially Directed Acyclic Graph (CPDAG) found by any causal structure discovery algorithm, TabSCM (i) orients edges to a DAG, (ii) fits root-node marginals with KDE or categorical frequencies, and (iii) learns topologically ordered structural assignments. Such assignments are achieved using conditional diffusion models for continuous variables as child nodes and gradient-boosted trees for categorical ones. Ancestral sampling yields semantically valid records and enables exact counterfactual queries. On seven public datasets, encompassing healthcare, finance, housing, environment, TabSCM matches or surpasses state-of-the-art GAN, diffusion, and LLM baselines in statistical fidelity, downstream utility, and privacy risk, while also cutting rule-violation rates and providing causally meaningful and robust conditional interventions. Because generation is decomposed into explicit equations, it runs up to 583$\times$ faster than diffusion-only models and exposes interpretable knobs for fairness auditing and policy simulation, making TabSCM a practical choice for realism, explainability, and causal soundness.'

tags: ['tabular data generation','causality']

featured: false

url_pdf: 'https://arxiv.org/pdf/2604.22337'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
