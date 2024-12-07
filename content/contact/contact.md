---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact Us
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true
      
  email: arclabuno@gmail.com
  phone: +1 402 554 2800
  address:
    street: 6001 Dodge Street
    city: Omaha
    state: NE
    postcode: '68182'

design:
  columns: '1'
---