---
type: PageLayout
title: Custom Content
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic section with a video
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: Section with a video subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: VideoBlock
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: true
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
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Automated Content Generation
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: We create new content based on your existing images and videos
    items:
      - type: FeaturedItem
        title: Image Generation
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Video Generation
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first awesome Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
    actions: []
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
slug: content
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
