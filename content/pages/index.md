---
type: PageLayout
title: Home
colors: colors-b
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Dr John Mills
    subtitle: Psychologist + Open Science Advisor
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-0
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
        fontWeight: 500
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: >+
      #### Hi, I'm John, a Psychologist and Open Science Advisor based between
      London and Rotterdam.



    media:
      type: ImageBlock
      url: 'https://assets.stackbit.com/components/images/default/default-image.png'
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
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
    colors: colors-a
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-7
          - pb-7
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
