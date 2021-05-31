---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |
      随意勾搭
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: 尊姓大名
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: text
        name: subject
        label: Subject
        options:
          - Error on the site
          - Sponsorship
          - Other
        default_value: Subject
      - input_type: textarea
        name: message
        label: Message
        default_value: Your question
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
