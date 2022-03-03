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
  email: rtm (at) american (dot) edu
  phone: +1 202 885 6470
  address:
    street: 4400 Massachusetts Avenue NW
    city: Washington
    region: DC
    postcode: '20016'
    country: United States
    country_code: US
  coordinates:
    latitude: '38.9375'
    longitude: '-77.0869'
  directions: Kerwin Hall
  office_hours:
    - 'Wednesday 10:00 to 11:00'
  appointment_url: 'https://calendly.com/ryantmoore'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/MooreRyanT'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
