---
title: Test Page
topper:
  topper_type: Hero - Big Search
  heading: Heading Test
  subheading: Subheading.
  styles:
    section:
      background_c: bg-wvu-gold
      text_c: text-wvu-blue
content_blocks:
  - _bookshop_name: section/hero
    heading: My Hero
    body:
    ctas:
    postscript_links:
    config:
      is_main: true
  - _bookshop_name: section/quicklinks
    heading: Quicklinks
    links:
      - text: Link 1
        ref:
        url: /url
  - _bookshop_name: section/backpage
    main:
      - _bookshop_name: detail/rich-text
        text: Here is my text.
      - _bookshop_name: detail/accordion
        panels:
          - title: Panel 1 Title
            text: Panel 1 text.
          - title: Panel 2 Title
            text: Panel 2 text.
      - _bookshop_name: detail/tabs
        tabs:
          - link: Tab 1
            text: Tab 1 text.
          - link: Tab 2
            text: Tab 1 text.
      - _bookshop_name: detail/youtube-video
        title: Video Title
        description: Video description.
        video_id: EMhV-NvxrAo
    sidebar: []
  - _bookshop_name: section/profile
    profiles:
      - person:
        name: Firstname Lastname
        heading: Heading
        quote: Quote.
        thumbnail:
        thumbnail_alt:
        also_see: []
        show: '2024-09-01'
        hide: '2030-09-01'
---
