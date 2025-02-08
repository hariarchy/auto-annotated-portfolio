---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      Sophie Maryke, I am SO so in love with you, will you be my valentine, this
      year, and for every year of our lives?
    subtitle: >-
      Sophie, you are the most incredible person I’ve ever met. You light up
      every room you walks into—not just with your beautiful smile, but with the
      warmth, kindness, and energy you carries so effortlessly. You have this
      amazing ability to make even the most ordinary moments feel special, and
      every day with you is an adventure I never want to end. You're my best
      friend, my greatest support, and the person who makes my life infinitely
      better just by being in it. I want you to be my Valentine because there’s
      no one else I’d rather celebrate love with—not just on February 14th, but
      every single day.
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
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
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
    subtitle: 'Reasons you should say yes:'
  - type: CtaSection
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Link
        label: Learn more
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
---
