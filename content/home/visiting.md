---
widget: experience
active: true
date_format: Jan 2006
experience:
  - title: Visiting Researcher
    company: Technical University of Munich
    company_url: ""
    company_logo: tum-logo
    location: Munich, Germany
    date_start: 2023-06-01
    date_end: 2023-09-01
    description: >-2
        Visiting period at the [Responsible Data Science](https://www.gov.sot.tum.de/rds/overview/) research group with head Prof Kasneci, School of Social Sciences and Technology. Research on explainability in dynamic data landscapes and graph learning.
  - title: Visiting PhD Student
    company: George Mason University
    company_url: ""
    company_logo: george-mason
    location: Fairfax, VA, USA
    date_start: 2021-04-01
    date_end: 2021-06-30
    description: >-2
        Visiting period at Prof Domeniconi's [Data Mining and Machine Learning](https://cs.gmu.edu/~dmml/) lab. I worked on deep learning applications and anomaly detection in e-learning and learning analytics.
widget_id: visiting_periods
# Places shown on the map above the list (rendered by the places_map shortcode in the body below).
places:
  - name: Technical University of Munich
    location: Munich, Germany
    dates: Jun 2023 – Sep 2023
    people: '[Gjergji Kasneci](https://www.professoren.tum.de/en/kasneci-gjergji)'
    logo: tum-logo
    card_text: |-
      We worked on dynamic graph counterfactual data, where the underlying data distribution changes and the classifier (in this case binary) can't be trusted in subsequent iterations. During the visiting period I wanted to bring my expertise in anomaly detection and counterfactuality together. We submitted a working draft to AAAI'24 (Aug 2023; we got rejected in the second phase). I continued working on the paper after my visiting period was officially over and was confident enough to send the second version to KDD'24 (Feb 2024), where [it was accepted](/publication/prenkaj-2024-gracie/). Here I met long-lasting friends, Mario and Tobias, with whom I kept working after this period too.

      After my visiting period was over, Gjergji offered me a postdoctoral position at the [Responsible Data Science](https://www.gov.sot.tum.de/rds/overview/) lab.
    lat: 48.1497
    lng: 11.5679
  - name: George Mason University
    location: Fairfax, VA, USA
    dates: Apr 2021 – Jun 2021
    people: '[Carlotta Domeniconi](https://scholar.google.com/citations?user=aKkIMogAAAAJ&hl=en) and [Hamed Sarvari](https://scholar.google.com/citations?user=ybhE0WYAAAAJ&hl=en)'
    logo: george-mason
    card_text: |-
      This is just a part of my visiting period, which was supposed to happen in March 2020. However, due to COVID-19 and the Italian government's decision to close the borders on March 8th, 2020, I couldn't travel. So I did my "visiting period" in my bedroom where, for the first time, I explored reconstruction-based autoencoders. Alongside, Hamed worked on BAE, a boosting mechanism that at every iteration becomes better at representing the inlier instances (tabular data).

      The paper got rejected twice (I don't remember where we sent it, probably CIKM'20) before Carlotta and Giovanni (the two senior authors) decided to try with PAKDD, where, to our surprise, [it had a big impact in the field](/publication/sarvari-2021-unsupervised/). This was Hamed's central contribution to his PhD thesis at GMU, and my first stepping stone in the anomaly detection field. This collaboration lasted from February 2020 to June 2021.
    lat: 38.8298
    lng: -77.3074
  - name: Massachusetts Institute of Technology
    location: Cambridge, MA, USA
    dates: Jan 2026
    people_label: Visited
    people: '[Antonio Norelli](https://noranta4.com)'
    logo: mit-logo
    card_text: |-
      Worked on a very cool project alongside Francesco De Benedittis and Oscar Norelli that will have a huge impact on how science is evaluated. Today's overflow of noise, especially with AI-generated papers, makes it very hard for researchers to parse their fields and understand which papers are actually worth their time. [BetterScholar.org](https://betterscholar.org/) is that solution! Stay tuned for the launch (Q2 2027).
    lat: 42.3601
    lng: -71.0942
  - name: University of L'Aquila
    location: L'Aquila, Italy
    dates: Apr 2023 (1 day)
    people_label: Visited
    people: '[Giovanni Stilo](https://giovannistilo.eu/)'
    logo: "university_of_l'aquila"
    card_text: Taught a hands-on tutorial on detecting handwritten digits (MNIST) with autoencoders and transformers for the master's course Deep Neural Networks.
    lat: 42.3676
    lng: 13.3527
  - name: Heimerer College
    location: Pristina, Kosovo
    dates: May 2024 – Jun 2024
    people: '[Rona Karahoda](https://scholar.google.com/citations?user=FbAlBYUAAAAJ&hl=en)'
    logo: heimerer
    card_text: |-
      I was General Chair of the 4th International Summer School on "Artificial Intelligence for Healthcare and Societal Impact", hosted at Heimerer College in Pristina. Rona helped with the logistics of the school, and I took care of inviting the keynote speakers ([Giovanni Stilo](https://giovannistilo.eu/), [Andrea Aliverti](https://www.deib.polimi.it/eng/people/details/569774), [Olav Götz](https://science.rsu.lv/en/persons/olav-goetz/), and [Valerio Pellegrini](https://www.linkedin.com/in/valerio-p-2580916b/)) and organizing the workshops.
    lat: 42.6629
    lng: 21.1655
headless: true
weight: 30
title: Visiting Periods
subtitle: null
design:
  columns: "2"
  view: compact
---

{{< places_map >}}
