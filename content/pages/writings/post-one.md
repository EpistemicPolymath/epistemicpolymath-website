---
title: Welcome to Poly's Mind
colors: colors-a
layout: PostLayout
date: '2022-04-15'
featuredImage:
  type: ImageBlock
  url: /images/PXL_20220111_221753566.PORTRAIT.jpg
  altText: 'An image of poly posing '
media:
  url: /images/post-2.jpg
  altText: altText of the image
  caption: Caption of the image
  elementId: ''
  type: ImageBlock
bottomSections:
  - elementId: ''
    type: RecentPostsSection
    colors: colors-f
    variant: variant-d
    subtitle: Recent posts
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 2
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
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    showFeaturedImage: true
    showReadMoreLink: true
  - type: ContactSection
    backgroundSize: full
    title: Stay up-to-date with my words ✍️
    colors: colors-f
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
        - name: updatesConsent
          label: Sign me up to recieve my words
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
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
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
excerpt: Introduction
author: content/data/team/person-clzby8x2c.json
metaTitle: Why I write
metaDescription: Autistic Writers
metaTags: []
---
# Welcome to Poly's Mind... My mind

Now, I have been trying to get a site live for a long time and this is basically a test platform for me to explore. I am desperate to start **WRITING** my thoughts, ideas, short stories, SOMEWHERE. So, for now that will be here.

I am a person that in involved in a lot at all times mentally and physically. So, it will be weird trying to communicate primarily through text in this way when it has been a long time since I have done writing like this. But I am excited to get started again.

