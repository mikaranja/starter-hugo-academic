---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Get in touch with me.
      # Contact (add or remove contact options as necessary)
      social:
        - icon: envelope
          icon_pack: fas
          link: 'mailto:mikaranja@gmail.com'
          label: Email
        # - icon: twitter
        #   icon_pack: fab
        #   link: https://twitter.com/mikaranja
        #   label: Follow me on Twitter
          # display:
          #   header: true
        # - icon: graduation-cap # Alternatively, use `google-scholar` icon from `ai` icon pack
        #   icon_pack: fas
        #   link: https://scholar.google.com/citations?
        - icon: github
          icon_pack: fab
          link: https://github.com/mikaranja
          label: GitHub
        - icon: linkedin
          icon_pack: fab
          link: https://www.linkedin.com/in/mikaranja
          label: LinkedIn
        - icon: whatsapp
          icon_pack: fab
          link: https://api.whatsapp.com/send?phone=+254705872780&text=Hello,%20I%20just%20saw%20your%20portfolio.
          label: Whatsapp
    email: mikaranja@gmail.com
      phone: +254 705 872 780
    #   appointment_url: 'https://calendly.com'
      address:
        # street: 450 Serra Mall
        city: Nairobi
        region: KE
        # postcode: '94305'
        country: KENYA
        country_code: KE
    #   directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    #   office_hours:
    #     - 'Monday 10:00 to 13:00'
    #     - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: github
          icon_pack: fab
          name: View my GitHub
          link: 'https://github.com/mikaranja'
        - icon: linkedin
          icon_pack: fab
          name: View my LinkedIn
          link: 'https://www.linkedin.com/in/mikaranja'
        - icon: whatsapp
          icon_pack: fab
          name: WhatsApp Me
          link: 'https://api.whatsapp.com/send?phone=+254705872780&text=Hello,%20I%20just%20saw%20your%20portfolio.'
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