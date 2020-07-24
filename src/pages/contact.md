---
title: Entre em contato
img_path: ""
form_id: contactForm
form_fields:
  - type: form_field
    input_type: text
    name: name
    label: Nome
    default_value: Seu nome
    is_required: true
  - type: form_field
    input_type: email
    name: email
    label: E-mail
    default_value: Seu e-mail
    is_required: true
  - type: form_field
    input_type: select
    name: subject
    label: Assunto
    default_value: Por favor, selecione
    options:
      - Erro no site
      - Publicidade
      - Sugestão
  - type: form_field
    input_type: textarea
    name: message
    label: Mensagem
    default_value: Sua mensagem
  - type: form_field
    input_type: checkbox
    name: consent
    label: Eu entendo que o envio das informações confirma meu consentimento para
      receber informações no e-mail informado.
submit_label: Enviar mensagem
template: contact
---
