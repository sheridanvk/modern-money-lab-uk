---
type: PageLayout
title: About
colors: colors-b
sections:
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: 'Modern Money Lab UK is:'
    images:
      - type: ImageBlock
        url: /images/sheridan_headshot_cropped.jpg
        altText: 'Image of Sheridan Kates, in front of some plants'
        caption: Sheridan Kates
      - type: ImageBlock
        url: /images/logo2.svg
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/logo3.svg
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/logo4.svg
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/logo5.svg
        altText: Logo five
        caption: Logo five
    spacing: 3
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: 'WEB 1, 2, 3'
      - type: Label
        label: React
      - type: Label
        label: Microsoft Office
      - type: Label
        label: Next.js
      - type: Label
        label: Netlify
      - type: Label
        label: Pancakes
      - type: Label
        label: C++
      - type: Label
        label: Swift
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [thisismyemail.@myemail.me](mailto:thisismyemail.@myemail.me)
---
