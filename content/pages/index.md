---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: 'I solve user problems through design, backed by strong UX skills'
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >

      As the CEO and Founder of **NexGen Design Solution**, I provide the
      best-awarded SaaS product design service in Bangladesh. With expertise in
      Figma and Spline, I create user-centric designs that drive growth and
      engagement, helping businesses achieve their digital goals.
    actions:
      - label: Live Chat On WhatsApp
        altText: ''
        url: 'https://wa.link/xzsc32'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Recent Designs
        altText: ''
        url: 'https://www.behance.net/uxaminul'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
      url: /images/SaaS Dashboard ui ux design.svg
    badge:
      label: SaaS Solutions Specialist
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - subtitle: Award winning enterprises trust us
    images:
      - url: /images/empathy-logo.svg
        altText: Empathy logo
        type: ImageBlock
      - url: /images/wellster-logo.svg
        altText: Wellster logo
        type: ImageBlock
      - url: /images/vise-logo.svg
        altText: Vise logo
        type: ImageBlock
      - url: /images/telus-logo.svg
        altText: Telus logo
        type: ImageBlock
      - url: /images/contenful-logo.svg
        altText: Contentful logo
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Sanity logo
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - title:
      text: >-
        How NexGen Design Solution Transforms Ideas into Seamless SaaS
        Experiences
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    text: >
      Watch our video to see how we craft intuitive **SaaS product** designs
      that drive engagement and business success. Explore our proven process,
      user-focused strategies, and cutting-edge tools like Figma and Spline in
      action.
    media:
      title: SaaS Website UI/UX Design
      url: 'https://vimeo.com/456147878?signup=true'
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
      autoplay: true
      loop: true
      muted: true
    badge:
      label: Discover the Power of SaaS Design
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
  - type: RecentPostsSection
    title:
      type: TitleBlock
      text: Recent posts
      color: text-dark
      styles:
        self:
          textAlign: center
    recentCount: 3
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    hoverEffect: thin-underline
    styles:
      self:
        justifyContent: center
  - title:
      text: Aminul Islam – CEO & Founder of NexGen Design Solution
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Aminul Islam is a skilled UI/UX designer and the founder of **NexGen
      Design Solution**, specializing in intuitive, scalable SaaS product
      designs using Figma and Spline to help businesses grow.
    actions:
      - label: Get started
        url: 'https://wa.link/xzsc32'
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: Portfolio
        url: 'https://www.behance.net/uxaminul'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      altText: uxaminul.com
      type: ImageBlock
      url: /images/uxaminul.svg
    badge:
      label: Meet the Founder
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Get in Touch with NexGen Design Solution
      color: text-dark
      type: TitleBlock
    subtitle: We’re Here to Bring Your Ideas to Life
    text: >
      Have a project in mind or need help with your SaaS product or UI/UX
      design? Reach out to us today! Our team is ready to collaborate and create
      impactful designs tailored to your needs.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Let's Collaborate
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
