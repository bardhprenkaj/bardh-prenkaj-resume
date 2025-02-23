---
title: 'Unifying Evolution, Explanation, and Discernment: A Generative Approach for Dynamic Graph Counterfactuals'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bardh Prenkaj
  - Mario Villaizan-Vallelado
  - Tobias Leemann
  - Gjergji Kasneci

date: '2024-08-24T00:00:00Z'
doi: '10.1145/3637528.3671831'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining*
publication_short: In *KDD 2024*

abstract: We present GRACIE (Graph Recalibration and Adaptive Counterfactual Inspection and Explanation), a novel approach for generative classification and counterfactual explanations of dynamically changing graph data. We study graph classification problems through the lens of generative classifiers. We propose a dynamic, self-supervised latent variable model that updates by identifying plausible counterfactuals for input graphs and recalibrating decision boundaries through contrastive optimization. Unlike prior work, we do not rely on linear separability between the learned graph representations to find plausible counterfactuals. Moreover, GRACIE eliminates the need for stochastic sampling in latent spaces and graph-matching heuristics. Our work distills the implicit link between generative classification and loss functions in the latent space, a key insight to understanding recent successes with this architecture. We further observe the inherent trade-off between validity and pulling explainee instances towards the central region of the latent space, empirically demonstrating our theoretical findings. In extensive experiments on synthetic and real-world graph data, we attain considerable improvements, reaching ~99% validity when sampling sets of counterfactuals even in the challenging setting of dynamic data landscapes. 


tags: ['deep learning','explainability','graph learning']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3637528.3671831'
url_code: 'https://github.com/bardhprenkaj/HANSEL'
url_dataset: ''
url_poster: '/uploads/posters/KDD2024.pdf'
url_project: ''
url_slides: '/uploads/conference_slides/KDD2024.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Example of spurious correlation in sentiment classification tasks, where a classifier takes Spielberg and New York Subway as shortcuts and makes wrong predictions w.r.t. the ground truth. The classifier concentrates on the bold tokens to make the prediction; however, the underlined tokens might be more useful in producing the correct label'
#  focal_point: ''
#  preview_only: false


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---