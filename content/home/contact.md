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
  email: scholar.google.com
  phone: 888 888 88 88

  contact_links:
    - icon: book
      icon_pack: fab
      name: eLibrary
      link: 'https://elibrary.ru/'
    - icon: book
      icon_pack: fas
      name: Google Scholar
      link: 'https://scholar.google.com/'
    - icon: book
      icon_pack: fas
      name: ORCID
      link: 'https://orcid.org/'
    - icon: book
      icon_pack: fas
      name: Mendeley
      link: 'https://www.mendeley.com/'
    - icon: book
      icon_pack: fas
      name: ResearchGate
      link: 'https://www.researchgate.net/'
    - icon: book
      icon_pack: fas
      name: Academia.edu
      link: 'https://independent.academia.edu/AltanaBalkhanova'
    - icon: book
      icon_pack: fas
      name: arXiv
      link: 'https://arxiv.org/'
    - icon: book
      icon_pack: fas
      name: github
      link: 'https://github.com/ayBalkhanova'

design:
  columns: '2'
---
