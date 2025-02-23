---
title: 'Robust Stochastic Graph Generator for Counterfactual Explanations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mario Alfonso Prado-Romero
  - Bardh Prenkaj
  - Giovanni Stilo

date: '2024-02-25T00:00:00Z'
doi: '10.48550/arXiv.2312.11747'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 38th Annual AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI 2024*

abstract: Counterfactual Explanation (CE) techniques have garnered attention as a means to provide insights to the users engaging with AI systems. While extensively researched in domains such as medical imaging and autonomous vehicles, Graph Counterfactual Explanation (GCE) methods have been comparatively under-explored. GCEs generate a new graph akin to the original one, having a different outcome grounded on the underlying predictive model. Among these GCE techniques, those rooted in generative mechanisms have received relatively limited investigation, despite demonstrating impressive accomplishments in other domains, such as artistic styles and natural language modelling. The preference for generative explainers stems from their capacity to generate counterfactual instances during inference, leveraging autonomously acquired perturbations of the input graph. Motivated by the rationales above, our study introduces RSGG-CE, a novel Robust Stochastic Graph Generator for Counterfactual Explanations able to produce counterfactual examples from the learned latent space considering a partially ordered generation sequence. Furthermore, we undertake both quantitative and qualitative analyses to compare RSGG-CE’s performance against SoA generative explainers, highlighting its increased abilities in engendering plausible counterfactual candidates.


tags: ['explainability', 'graph learning']

# Display this page in the Featured widget?
featured: True

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/aiim-research/GRETEL'
url_dataset: ''
url_poster: '/uploads/posters/AAAI2024.pdf'
url_project: 'https://aiimlab.org/blog/2023/12/19/AAAI_24_Robust_Stochastic_Graph_Generator_for_Counterfactual_Explanations'
url_slides: '/uploads/conference_slides/AAAI2024.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Generator vs Discriminator on RSGG-CE for graph counterfactual engendering.'
  focal_point: ''
  preview_only: false


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---