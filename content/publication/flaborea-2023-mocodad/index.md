---
title: 'Multimodal Motion Conditioned Diffusion Model for Skeleton-based Video Anomaly Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Alessandro Flaborea
  - Luca Collorone
  - Guido D'Amely
  - Stefano D'Arrigo
  - Bardh Prenkaj
  - Fabio Galasso

date: '2023-08-28T00:00:00Z'
doi: '10.48550/arXiv.2307.07205'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the IEEE/CVF International Conference on Computer Vision*
publication_short: In *ICCV 2023*

abstract: Anomalies are rare and anomaly detection is often therefore framed as One-Class Classification (OCC), i.e. trained solely on normalcy. Leading OCC techniques constrain the latent representations of normal motions to limited volumes and detect as abnormal anything outside, which accounts satisfactorily for the openset'ness of anomalies. But normalcy shares the same openset'ness property since humans can perform the same action in several ways, which the leading techniques neglect. We propose a novel generative model for video anomaly detection (VAD), which assumes that both normality and abnormality are multimodal. We consider skeletal representations and leverage state-of-the-art diffusion probabilistic models to generate multimodal future human poses. We contribute a novel conditioning on the past motion of people and exploit the improved mode coverage capabilities of diffusion processes to generate different-but-plausible future motions. Upon the statistical aggregation of future modes, an anomaly is detected when the generated set of motions is not pertinent to the actual future. We validate our model on 4 established benchmarks, UBnormal, HR-UBnormal, HR-STC, and HR-Avenue, with extensive experiments surpassing state-of-the-art results.


tags: ['anomaly detection', 'diffusion models']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2307.07205.pdf'
url_code: 'https://github.com/aleflabo/MoCoDAD'
url_dataset: ''
url_poster: '/uploads/posters/ICCV2023.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=IuDzVez--9U'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview of the proposed MoCoDAD.'
  focal_point: ''
  preview_only: false


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---