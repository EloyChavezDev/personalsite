---
title: Contacto
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |+
      Para ponerse en contacto por favor complete el siguiente formulario.

    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Nombre
        label: Nombre
        default_value: Your name
        is_required: true
        options: []
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: Asunto
        label: Asunto
        default_value: Please select
        options:
          - Charlemos
          - Colaboración/Patrocinio
          - Reportar error en el sitio
          - Otro
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario está almacenando mi información enviada
          para que puedan ser contactado.
    submit_label: Enviar
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
