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
  email: zhaoz233@mcmaster.ca
  phone: 365 888 2336
  address:
    street: Information Technology Building
    city: Hamilton
    region: Ontario
    postcode: 'L8S 1C7'
    country: Canada
    country_code: CA

design:
  columns: '2'
---
