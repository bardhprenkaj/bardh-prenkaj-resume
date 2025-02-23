---
title: Unifying Evolution, Explanation, and Discernment, A Generative Approach for Dynamic Graph Counterfactuals


event: Temporal Graph Learning (TGL) Reading Group, University of Manheim (Germany) + Mila (Canada)
event_url: https://shenyanghuang.github.io/rg.html#24oct17bio

location: Online

summary: I gave a talk on my paper on Dynamic Graph Counterfactuality accepted as oral presentation at KDD'24.
abstract: We present GRACIE (Graph Recalibration and Adaptive Counterfactual Inspection and Explanation), a novel approach for generative classification and counterfactual explanations of dynamically changing graph data. We study graph classification problems through the lens of generative classifiers. We propose a dynamic, self-supervised latent variable model that updates by identifying plausible counterfactuals for input graphs and recalibrating decision boundaries through contrastive optimization. Unlike prior work, we do not rely on linear separability between the learned graph representations to find plausible counterfactuals. Moreover, GRACIE eliminates the need for stochastic sampling in latent spaces and graph-matching heuristics. Our work distills the implicit link between generative classification and loss functions in the latent space, a key insight to understanding recent successes with this architecture. We further observe the inherent trade-off between validity and pulling explainee instances towards the central region of the latent space, empirically demonstrating our theoretical findings. In extensive experiments on synthetic and real-world graph data, we attain considerable improvements, reaching ∼99% validity when sampling sets of counterfactuals even in the challenging setting of dynamic data landscapes. 

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-10-17T17:00:00Z'
date_end: '2024-10-17T18:00:00Z'
all_day: false

authors: [Bardh Prenkaj]
tags: [deep learning, explainability]

# Is this a featured talk? (true/false)
featured: true

#image:
#  caption: 'AAAI 2024 Banner'
#  focal_point: Right


# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/bardhprenkaj/HANSEL'
url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3637528.3671831'
url_slides: ''
url_video: 'https://www.youtube.com/watch?v=LZ47oqbfYJU'
# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---