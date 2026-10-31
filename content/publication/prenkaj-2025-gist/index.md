---
title: 'Graph Inverse Style Transfer for Counterfactual Explainability'

authors:
  - Bardh Prenkaj
  - Efstratios Zaradoukas
  - Gjergji Kasneci

date: '2025-07-13T00:00:00Z'
doi: '10.48550/arXiv.2505.17542'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

publication: In *Proceedings of the 42nd International Conference on Machine Learning*
publication_short: In *ICML 2025*

abstract: 'Counterfactual explainability seeks to uncover model decisions by identifying minimal changes to the input that alter the predicted outcome. This task becomes particularly challenging for graph data due to preserving structural integrity and semantic meaning. Unlike prior approaches that rely on forward perturbation mechanisms, we introduce Graph Inverse Style Transfer (GIST), the first framework to re-imagine graph counterfactual generation as a backtracking process, leveraging spectral style transfer. By aligning the global structure with the original input spectrum and preserving local content faithfulness, GIST produces valid counterfactuals as interpolations between the input style and counterfactual content. Tested on 8 binary and multi-class graph classification benchmarks, GIST achieves a remarkable +7.6% improvement in the validity of produced counterfactuals and significant gains (+45.5%) in faithfully explaining the true class distribution. Additionally, GIST''s backtracking mechanism effectively mitigates overshooting the underlying predictor''s decision boundary, minimizing the spectral differences between the input and the counterfactuals. These results challenge traditional forward perturbation methods, offering a novel perspective that advances graph explainability.'

tags: ['explainability','graph learning']

featured: false

url_pdf: 'https://arxiv.org/pdf/2505.17542'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
