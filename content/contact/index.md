---
title: Contact
date: 2024-08-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        For general inquiries or specific questions, please send us an email. If you wish to visit our office or discuss a project in detail, please schedule an appointment by emailing or calling us in advance. This helps us ensure that the right person is available to meet with you. Follow us on our social media channels for the latest updates and news from our lab.

      email: yaxiong@nercita.org.cn
      phone: +8618310862481
      address:
        street: No. 9 Shuguang Huayuan Middle Road
        District: Haidian
        city: Beijing
       # region: Beijing
        postcode: '100097'
        country: China
        country_code: CN
      coordinates:
        latitude: '39.94388728306'
        longitude: '116.2873943'
      directions: Enter Building A and take the stairs to Office A1101 on Floor 11
      office_hours:
        - 'Monday to Friday 9:00 to 18:00'
      #appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
