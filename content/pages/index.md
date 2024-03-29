---
title: Poly's Mind Home
layout: PageLayout
colors: colors-a
backgroundImage:
  url: /images/Nikon-d3200-me-5.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 31
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      I'm an Autistic Twitch Streamer, Software Quality Assurance Tester, Gamer,
      Learner, and Nerd.
    subtitle: >-
      This is my site-my info so you can get to know me and what I do a little
      more. Welcome to my mind. Poly's Mind.
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: Twitch
        altText: Twitch Stream Page
        url: 'https://www.twitch.tv/EpistemicPolymath'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
      - type: Link
        label: Youtube
        altText: ''
        url: 'https://www.youtube.com/c/EpistemicPolymath'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
      - type: Link
        label: Twitter
        altText: EpistemicPolymath's Twitter Link
        url: 'https://twitter.com/polymathical_'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
      - type: Link
        label: Instagram
        altText: EpistemicPolymath's Instagram
        url: 'https://www.instagram.com/epistemicpolymath/'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: false
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
    subtitle: What I do...
  - type: QuoteSection
    colors: colors-f
    elementId: ''
    quote: |
      “All progress is good progress.”
    name: '- Poly'
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: center
      name:
        fontWeight": 500
        fontStyle: normal
        textAlign: center
      title:
        fontWeight": 400
        fontStyle: normal
        textAlign: center
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Writings
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /writings
    posts:
      - content/pages/writings/post-one.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
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
      actions:
        justifyContent: flex-end
    showAuthor: false
  - type: LabelsSection
    colors: colors-f
    elementId: ''
    title: Skills
    subtitle: Stuff I like to learn about or do...
    items:
      - type: Label
        label: JavaScript
      - type: Label
        label: Java
      - type: Label
        label: Quality Assurance
      - type: Label
        label: OBS Studio
      - type: Label
        label: Firebot
      - type: Label
        label: Streaming
      - type: Label
        label: Writing
      - type: Label
        label: Reading
      - type: Label
        label: Learning
        url: ''
      - type: Label
        label: Full-time nerd
        url: ''
      - type: Label
        label: Philosophy
        url: ''
      - type: Label
        label: Science
        url: ''
      - type: Label
        label: Psychology
        url: ''
      - type: Label
        label: Life and Relationships
        url: ''
      - type: Label
        label: Personal Growth and Development
        url: ''
      - type: Label
        label: Mental Health
        url: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Tell me more about yourself...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: Tell me about yourself...
          hideLabel: true
          placeholder: Tell me about YOU!
          isRequired: true
          width: full
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
