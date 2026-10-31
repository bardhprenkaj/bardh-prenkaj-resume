---
title: 'Not All Features Deserve Attention: Graph-Guided Dependency Learning for Tabular Data Generation with Language Models'

authors:
  - Zheyu Zhang
  - Shuo Yang
  - Bardh Prenkaj
  - Gjergji Kasneci

date: '2025-07-24T00:00:00Z'
doi: '10.48550/arXiv.2507.18504'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

publication: '*arXiv preprint* arXiv:2507.18504'
publication_short: '*arXiv*'

abstract: 'Large Language Models (LLMs) have shown strong potential for tabular data generation by modeling textualized feature-value pairs. However, tabular data inherently exhibits sparse feature-level dependencies, where many feature interactions are structurally insignificant. This creates a fundamental mismatch as LLMs''self-attention mechanism inevitably distributes focus across all pairs, diluting attention on critical relationships, particularly in datasets with complex dependencies or semantically ambiguous features. To address this limitation, we propose GraDe (Graph-Guided Dependency Learning), a novel method that explicitly integrates sparse dependency graphs into LLMs''attention mechanism. GraDe employs a lightweight dynamic graph learning module guided by externally extracted functional dependencies, prioritizing key feature interactions while suppressing irrelevant ones. Our experiments across diverse real-world datasets demonstrate that GraDe outperforms existing LLM-based approaches by up to 12% on complex datasets while achieving competitive results with state-of-the-art approaches in synthetic data quality. Our method is minimally intrusive yet effective, offering a practical solution for structure-aware tabular data modeling with LLMs.'

tags: ['tabular data generation','LLMs','graph learning']

featured: false

url_pdf: 'https://arxiv.org/pdf/2507.18504'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
