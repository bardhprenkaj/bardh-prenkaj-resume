---
title: Robust Stochastic Graph Generator for Counterfactual Explanations


event: Microsoft Israel
#event_url: 

location: Online

summary: I gave a talk on my paper on Generative Graph Counterfactuality accepted as oral presentation at AAAI'24.
abstract: Counterfactual Explanation (CE) techniques have garnered attention as a means to provide insights to the users engaging with AI systems. While extensively researched in domains such as medical imaging and autonomous vehicles, Graph Counterfactual Explanation (GCE) methods have been comparatively under-explored. GCEs generate a new graph similar to the original one, with a different outcome grounded on the underlying predictive model. Among these GCE techniques, those rooted in generative mechanisms have received relatively limited investigation despite demonstrating impressive accomplishments in other domains, such as artistic styles and natural language modelling. The preference for generative explainers stems from their capacity to generate counterfactual instances during inference, leveraging autonomously acquired perturbations of the input graph. Motivated by the rationales above, our study introduces RSGG-CE, a novel Robust Stochastic Graph Generator for Counterfactual Explanations able to produce counterfactual examples from the learned latent space considering a partially ordered generation sequence. Furthermore, we undertake quantitative and qualitative analyses to compare RSGG-CE's performance against SoA generative explainers, highlighting its increased ability to engendering plausible counterfactual candidates.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-06-15T17:00:00Z'
date_end: '2024-06-15T18:00:00Z'
all_day: false

authors: [Bardh Prenkaj]
tags: [deep learning, explainability]

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Microsoft Logo'
  focal_point: Right


# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/aiim-research/GRETEL'
url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/30149/32036'
url_slides: '../../../uploads/speeches/microsoft_16_06_2024_speech.pdf'
url_video: ''
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