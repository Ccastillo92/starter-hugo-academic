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
  email: castc583@newschool.edu
  #phone: 888 888 88 88
  address:
    street: 6E 16th Street
    city: New York
    region: NY
    postcode: '10003'
    country: United States
    country_code: US
  directions: Enter Vera List Building and take the elevator to Floor 11
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/CsarCastillo25'
design:
  columns: '2'
---
