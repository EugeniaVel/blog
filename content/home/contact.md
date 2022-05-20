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
  email: test@example.org
  phone: 888 888 88 88
  address:
    street: 450 Serra Mall
    city: Stanford
    region: CA
    postcode: '94305'
    country: United States
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'
    - icon: 
      icon_pack: 
      name: library resourses
      link: 'https://www.elibrary.ru/defaultx.asp?'
      'https://scholar.google.com/'
      'https://scholar.google.com/'
      'https://orcid.org/my-orcid?orcid=0000-0002-6694-8692'
      'https://www.mendeley.com/settings/account/'
      'https://www.researchgate.net/profile/Eugenia-Velikodneva'
      'https://independent.academia.edu/EugeniaVel'
      'https://arxiv.org/'

design:
  columns: '2'
---
