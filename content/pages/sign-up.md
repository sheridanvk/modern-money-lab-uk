---
type: PageLayout
title: Sign Up
sections:
  - type: ContactSection
    title: Subscribe
    text: Join my newsletter to stay up-to-date
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: EmailFormControl
          name: email
          label: Name
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
