---
title: 'Are we certain it is anomalous?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Alessandro Flaborea
  - Bardh Prenkaj
  - Bharti Munjal
  - Marco Aurelio Sterpa
  - Dario Aragona
  - Luca Podo
  - Fabio Galasso

date: '2023-06-06T00:00:00Z'
doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops*
publication_short: In *CVPR 2023 Workshops*

abstract: The progress in modelling time series and, more generally, sequences of structured data has recently revamped research in anomaly detection. The task stands for identifying abnormal behaviors in financial series, IT systems, aerospace measurements, and the medical domain, where anomaly detection may aid in isolating cases of depression and attend the elderly. Anomaly detection in time series is a complex task since anomalies are rare due to highly non-linear temporal correlations and since the definition of anomalous is sometimes subjective. Here we propose the novel use of Hyperbolic uncertainty for Anomaly Detection (HypAD). HypAD learns selfsupervisedly to reconstruct the input signal. We adopt best practices from the state-of-the-art to encode the sequence by an LSTM, jointly learned with a decoder to reconstruct the signal, with the aid of GAN critics. Uncertainty is estimated end-to-end by means of a hyperbolic neural network. By using uncertainty, HypAD may assess whether it is certain about the input signal but it fails to reconstruct it because this is anomalous; or whether the reconstruction error does not necessarily imply anomaly, as the model is uncertain, e.g. a complex but regular input signal. The novel key idea is that a detectable anomaly is one where the model is certain but it predicts wrongly. HypAD outperforms the current state-of-the-art for univariate anomaly detection on established benchmarks based on data from NASA, Yahoo, Numenta, Amazon, and Twitter. It also yields state-of-theart performance on a multivariate dataset of anomaly activities in elderly home residences, and it outperforms the baseline on SWaT. Overall, HypAD yields the lowest false alarms at the best performance rate, thanks to successfully identifying detectable anomalies.



tags: ['anomaly detection', 'uncertainty estimation']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2023W/VAND/papers/Flaborea_Are_We_Certain_Its_Anomalous_CVPRW_2023_paper.pdf'
url_code: 'https://github.com/aleflabo/HypAD'
url_dataset: ''
url_poster: '../../../uploads/posters/CIKM2023.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'HypAD detects anomalies by the joint use of reconstruction error and uncertainty, learning both aspects end-to-end.'
  focal_point: ''
  preview_only: false


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---