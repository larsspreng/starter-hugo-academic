---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: formspree
    formspree:
      id: xdobdbyk
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

  # Contact details (edit or remove options as required)
#  email: test@example.org
#  phone: 888 888 88 88
#  address:
#    street: 450 Serra Mall
#    city: Stanford
#    region: CA
#    postcode: '94305'
#    country: United States
#    country_code: US
#  contact_links:
#    - icon: twitter
#      icon_pack: fab
#      name: DM Me
#      link: 'https://twitter.com/Twitter'

design:
  columns: '2'
---
