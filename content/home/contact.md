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
  email: wml@morin.wang
  address:
    street: 601 Nanshan Building, City University of Hong Kong, Address 83 Tat Chee Avenue, Kowloon
    city: Hong Kong


design:
  columns: '2'
---
