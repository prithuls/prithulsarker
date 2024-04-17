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
      captcha: true

  # Contact details (edit or remove options as required)
  email: prithuls [at] unr [dot] edu
  address:
    street: 1664 N. Virginia St
    city: Reno
    region: NV
    postcode: '89557'
    country: United States
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: WPEB 422
  office_hours:
    - 'Monday - Friday 10:00 to 18:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Reach Out
      link: 'https://www.linkedin.com/in/prithulsarker/'
    - icon: instagram
      icon_pack: fab
      name: DM Me
      link: 'https://www.instagram.com/prithul_sarker'

design:
  columns: '2'
---
