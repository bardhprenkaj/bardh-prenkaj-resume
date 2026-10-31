---
title: 'Active Tabular Augmentation via Policy-Guided Diffusion Inpainting'

authors:
  - Zheyu Zhang
  - Shuo Yang
  - Bardh Prenkaj
  - Gjergji Kasneci

date: '2026-05-11T00:00:00Z'
doi: '10.48550/arXiv.2605.10315'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

publication: '*arXiv preprint* arXiv:2605.10315'
publication_short: '*arXiv*'

abstract: 'Generative tabular augmentation is appealing in data-scarce domains, yet the prevailing focus on distributional fidelity does not reliably translate into better downstream models. We formalize a fidelity-utility gap: common generative objectives prioritize distributional plausibility, whereas augmentation succeeds only when injected samples reduce the current learner''s held-out evaluation loss. This gap motivates learning not just how to generate, but what to generate and when to inject as training evolves. We propose TAP (Tabular Augmentation Policy), which couples diffusion inpainting with a lightweight, learner-conditioned policy to steer generation toward high-utility regions and controls safe injection via explicit gating and conservative windowed commitment. Under severe data scarcity, TAP consistently outperforms strong generative baselines on seven real-world datasets, improving classification accuracy by up to 15.6 percentage points and reducing regression RMSE by up to 32%.'

tags: ['tabular data generation','diffusion models']

featured: false

url_pdf: 'https://arxiv.org/pdf/2605.10315'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
