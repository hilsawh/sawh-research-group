---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 85

# title: Address
#subtitle:

content:
  # Contact (edit or remove options as required)
  address: 
    street: MaRS Centre, West Tower
    city: Toronto
    region: Ontario
    postcode: M5G 1M1
    country: Canada
    country_code: CAN
#  phone: 888 888 88 88
#  email: max.shafer@gmail.com
  map:
    provider: 'mapbox'
    api_key: ''
    zoom: 10
  coordinates:
    latitude: '43.65959229544895'
    longitude: '-79.38967784450094'
#  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#  office_hours:
#    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
#  form:
#    provider: netlify
#    formspree:
#      id:
#    netlify:
      # Enable CAPTCHA challenge to reduce spam?
#      captcha: false

design:
  columns: '1'
  spacing:
    padding: ['50', '0', '50', '0']
  background:
    color: 'black'
    text_color_light: true
---