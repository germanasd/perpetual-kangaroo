---
title: Contact
sections:
  - type: hero_section
    subtitle: Напишите или позвоните и мы договоримся о встрече и подберем шторы для вас
    align: center
    padding_top: none
    padding_bottom: none
    background_color: none
    title: Вам нужны шторы?
    has_border: true
  - type: form_section
    content: "### Позвонить\_[**0997737719**](tel:+380997737719)\n\n### Написать в\_[**Viber**]()\n\n### Написать в\_[**Telegram**]()\n"
    content_align: center
    form_position: bottom
    form_width: fourty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Имя
        label: Имя
        default_value: Ваше Имя
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Ваш email адрес
        is_required: false
      - input_type: textarea
        name: message
        label: Сообщение
        default_value: Ваше сообщение
      - input_type: checkbox
        name: consent
        label: >-
          Нажимая на кнопку, вы даете согласие на обработку своих персональных
          данных и соглашаетесь с Политикой конфиденциальности
        is_required: true
      - input_type: tel
        label: Номер телефон
        default_value: lorem-ipsum
        options: []
        is_required: false
        type: form_field
        name: тел
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
    title_align: left
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
