---
type: PageLayout
title: Home
colors: colors-b
sections:
  - elementId: ''
    colors: colors-b
    backgroundSize: full
    title: Dr John P. Mills
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
          - pt-12
          - pb-0
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
        borderStyle: double
        borderWidth: 0
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
    text: "### Hi, I'm John, a Psychologist and Open Science Advisor based between London and Rotterdam.\n\nI consider myself a problem solver and enjoy coming up with creative solutions. I am currently working on changing the academic culture around research integrity through open science at\_[Erasmus University Rotterdam](https://www.eur.nl/en), and figuring out how best to support online gamers with their mental health at\_[Play Aid](https://www.play-aid.org/).\n"
    media:
      type: ImageBlock
      url: /images/headshot.jpg
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: FeaturedProjectsSection
    subtitle: Current and past projects
    actions:
      - type: Link
        label: See all projects
        altText: See all projects
        url: /projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/project-two.md
    colors: colors-e
    variant: variant-a
    elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    title: What I'm working on...
  - type: FeaturedPostsSection
    title: Today in my little corner of the internet…
    actions:
      - type: Link
        label: See all posts
        altText: See all posts
        url: /blog
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    posts:
      - content/pages/blog/test.md
    colors: colors-a
    variant: variant-d
    elementId: ''
    showDate: false
    showAuthor: false
    showExcerpt: true
    showFeaturedImage: false
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Posts and notes on open science and psychology.
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
    colors: colors-b
    backgroundSize: inset
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
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
