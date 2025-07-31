---
type: PageLayout
title: Sign Up
sections:
  - type: ContactSection
    title: Subscribe
    text: Join my newsletter to stay up-to-date
    form:
      type: FormBlock
      title: Join our mailing list
      fields:
        - type: TextFormControl
          name: firstname
          label: First Name
          hideLabel: false
          placeholder: ''
          width: 1/2
          isRequired: false
        - type: TextFormControl
          name: Last name
          label: Last name
          hideLabel: false
          placeholder: ''
          width: 1/2
          isRequired: false
        - type: EmailFormControl
          name: email
          label: First Name
          hideLabel: false
          placeholder: Your email
          width: full
          isRequired: 'true'
      submitLabel: Sign Up
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-c
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
addTitleSuffix: true
metaTags: []
colors: colors-b
---
