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
  email: mail@konstantingantert.com
  phone: +49 341 9733543
  address:
    street: Grimmaische Straße 12
    city: Leipzig
    region: Saxony
    postcode: '04109'
    country: Germany
    country_code: DE
  coordinates:
    latitude: '51.33953147119495'
    longitude: '12.378558772656167'
  directions: Institutsgebäude Room I209
  office_hours:
    - ''
  appointment_url: ''
  contact_links:

design:
  columns: '2'
---
