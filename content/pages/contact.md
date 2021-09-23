---
title: ¡Hablemos!
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >-
      ¡Hola! Muchas gracias por su interés en trabajar juntos. Complete el formulario de contacto a continuación o envíenos un correo electrónico
      [pedro@rojascorona.online](mailto:pedro@rojascorona.online).
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Tu nombre es...
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu correo electrónico es...
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Selecciona...
        options:
          - Asesoría Web
          - Diseño de Sitio Web
          - Otros
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Tu mensaje es...
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario almacena la información enviada, por lo que
          puede ser contactado
    submit_label: ¡Enviar!
seo:
  title: ¡Hablemos!
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
