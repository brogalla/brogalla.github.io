---
title: ''
date: 2022-10-24
type: landing

sections:
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      # phone: 888 888 88 88
      # address:
      #  street: 450 Serra Mall
      #  city: Stanford
      #  region: CA
      #  postcode: '94305'
      #  country: United States
      #  country_code: US
     # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #  latitude: '37.4275'
      #  longitude: '-122.1697'  
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
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
    design:
      columns: '2'
---
