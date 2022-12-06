---
title: 'A self-supervised algorithm to detect signs of social isolation in the elderly from daily activity sequences'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bardh Prenkaj
  - Dario Aragona
  - Alessandro Flaborea
  - Fabio Galasso
  - Saverio Gravina
  - Luca Podo
  - Emilia Reda
  - Paola Velardi

date: '2022-11-24T00:00:00Z'
doi: '10.1016/j.artmed.2022.102454'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Artificial Intelligence in Medicine*

abstract: Considering the increasing aging of the population, multi-device monitoring of the activities of daily living (ADL) of older people becomes crucial to support independent living and early detection of symptoms of mental illnesses, such as depression and Alzheimer’s disease. Anomalies can anticipate the diagnosis of these pathologies in the patient’s normal behavior, such as reduced hygiene, changes in sleep habits, and fewer social interactions. These abnormalities are often subtle and hard to detect. Especially using non-intrusive monitoring devices might cause anomaly detectors to generate false alarms or ignore relevant clues. This limitation may hinder their usage by caregivers. Furthermore, the notion of abnormality here is context and patient-dependent, thus requiring untrained approaches. To reduce these problems, we propose a self-supervised model for multi-sensor time series signals based on Hyperbolic uncertainty for Anomaly Detection, which we dub HypAD. HypAD estimates uncertainty end-to-end, thanks to hyperbolic neural networks, and integrates it into the ”classic” notion of reconstruction loss in anomaly detection. Based on hyperbolic uncertainty, HypAD introduces the principle of a detectable anomaly. HypAD assesses whether it is sure about the input signal and fails to reconstruct it because it is anomalous or whether the high reconstruction loss is due to the model uncertainty, e.g., a complex but regular signal (cf. this parallels the residual model error upon training). The proposed solution has been incorporated into an end-to-end ADL monitoring system for elderly patients in retirement homes, developed within a funded project leveraging an interdisciplinary consortium of computer scientists, engineers, and geriatricians. Healthcare professionals were involved in the design and verification process to foster trust in the system. In addition, the system has been equipped with explainability features.

tags: ['anomaly detection', 'activities of daily living', 'elderly social isolation', 'hyperNN', 'hyperbolic uncertainty']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: ''
url_code: 'https://github.com/aleflabo/HypAD'
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1ROtp9cSSF2hC6f42cAHvp9JRl4BMucjk/view?usp=share_link'
url_project: ''
url_slides: ''
url_source: 'https://anomalybyclick.github.io/'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Abstract schema of HypAD'
  focal_point: ''
  preview_only: false


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---