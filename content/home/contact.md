---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: bardhprenkaj95@gmail.com
  address:
    street: Via Salaria 113
    city: Rome
    region: Lazio
    postcode: '00185'
    country: Italy
    country_code: IT
  coordinates:
    latitude: '41.914110'
    longitude: '12.497350'
  directions: Enter the Faculty Building and take the lift to Office 333 on Floor 3
  office_hours:
    - 'Monday 09:00 to 17:30'
    - 'Tuesday 09:00 to 17:30'
    - 'Wednesday 09:00 to 17:30'
    - 'Thursday 09:00 to 17:30'
    - 'Friday 09:00 to 17:30'
  appointment_url: 'https://calendly.com/bardhprenkaj/15min'
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: DM Me
      link: 'https://www.linkedin.com/in/prenkaj-bardh/'
    - icon: envelope
      icon_pack: fas
      name: Email Me
      link: 'mailto:bardhprenkaj95@gmail.com?Subject=Hello%20Bardh&cc=prenkaj@di.uniroma1.it'

design:
  columns: '2'
---
