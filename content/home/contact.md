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
  email: iambunde@nebula.io
  phone: +254 713 1316 ---just email
  address:
    street: 450 Serra Mall
    city: Nairobi
    region: Kenya
    postcode: 00100
    country: Kenya-Pan Africa
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday 09:00 to 17:00'
    - 'Wednesday 09:00 to 10:00'
  personal_hours: Can be arranged  
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

design:
  columns: '2'
---
