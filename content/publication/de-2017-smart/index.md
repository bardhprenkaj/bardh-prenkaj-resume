---
title: 'A smart peephole on the cloud'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Maria De Marsico
  - Eugenio Nemmi
  - Bardh Prenkaj
  - Gabriele Saturni

date: '2017-09-11T00:00:00Z'
doi: '10.1007/978-3-319-70742-6'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Image Analysis and Processing*

abstract: This paper does not present a novel technique for biometric recognition, but rather a novel way to use it. The proposal is to exploit cloud computing in order to support everyday applications. These are not necessarily bound to security, but span a wide range of possible useful tasks. This work presents a smart peephole able to recognize the person at the door, possibly automatically allowing entrance according to rules decided by the home keeper. The novelty is that very little processing is carried out locally, and biometrics is implemented as a service. The system relies on Microsoft Cognitive Services, a suite of remote services included in Microsoft Azure platform. The single user has to install nothing but a camera with a sound capture facility in correspondence to the peephole, and a lightweight software. A movement detector module triggers the capture/recognition activity. The captured audio and video samples are sent to the service. Most processing and recognition are carried out via the remote suite, and a final result is sent back to possibly trigger a response action. The present prototype includes face, speech and emotion recognition. It does not completely cover all system aspects. The aim is to demonstrate the feasibility of the approach.


tags: ['biometrics', 'cloud computing', 'microsoft cognitive services']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'An example of result from DOPTFlow algorithm'
  focal_point: ''
  preview_only: false


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---