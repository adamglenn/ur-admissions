---
_schema: guide_page_test
title: New Guide Page Test
description:
topper:
  _bookshop_name: design-system/topper/hero
  label: ''
  background_image: ''
  alt_text: ''
  heading:
    - text: Heading Test
      highlight: ''
  subheading: Subheading.
  body_text: ''
  styles:
    vibe: down-to-business
    background_c:
    gradient_1:
    gradient_2:
    gradient_3:
    heading_c:
    enable_blend: false
    enable_pattern: false
    tint_opacity: '0.5'
    container_margin:
  layout: {}
  config:
    show_label: true
content_blocks:
  - _bookshop_name: design-system/section/alternating-grid-test-2
    heading: Alternating Grid Heading Test
    subheading: Subheading goes here.
    items:
      - heading: Item Heading
        image: /uploads/34750-s-bfp-0046-xx.jpg
        alt_text:
        copy: Here is some copy. Are we still fast?
        ctas:
          - text: CTA Text
            icon: book
            url:
    postscript:
      copy:
      ctas:
    settings:
      styles:
        background_c: wvu-accent--blue-light
      layout:
        butter:
        margin: mt-n9 p-5 p-xl-6
      config:
        edit_mode_only: false
        include_heading_postscript: true
  - _bookshop_name: design-system/section/tabs
    heading:
    tabs:
      - name: Tab 1
        image: /uploads/34750-s-bfp-0046-xx.jpg
        label: Label
        heading: Tab Heading Are We Fast? Still fast?
        text: Tab 1 text.
        ctas:
          - text: CTA
            icon: book
            url:
    settings:
      styles:
        background_c: wvu-accent--blue-light
      layout:
        butter:
        margin:
      config:
        edit_mode_only: false
        include_heading_postscript: false
  - _bookshop_name: design-system/section/accordion
    panels:
      - name: Panel Title Test
        image:
        alt_text:
        heading: Panel Heading Test
        text: Panel text.
        ctas:
          - text: CTA
            icon: book
            url:
      - name: Panel Title 2
        image:
        alt_text:
        heading: Panel Heading
        text: Panel text.
        ctas:
    settings:
      styles:
        background_c:
      layout:
        butter:
        margin:
      config:
        edit_mode_only: false
        include_heading_postscript: false
  - _bookshop_name: design-system/section/cards
    heading: Heading Test
    subheading: Subheading.
    items:
      - title: Item 1 Title
        image: /uploads/34750-s-bfp-0046-xx.jpg
        alt_text:
        label:
        badge:
        text: Item 1 text.
        ctas:
        background_c:
        accent_c:
      - title: Item 1 Title
        image: /uploads/34750-s-bfp-0046-xx.jpg
        alt_text:
        label:
        badge:
        text: Item 1 text.
        ctas:
        background_c:
        accent_c:
    postscript:
      copy:
      ctas:
    settings:
      layout:
        buffer:
        margin:
      styles:
        background_c:
        tint_shade:
        panel_font:
        accent_c:
      config:
        edit_mode_only: false
        include_heading_postscript: true
  - _bookshop_name: design-system/section/cards-simple
    heading: Heading
    subheading: Subheading.
    items:
      - title: Item 1 Title
        image:
        alt_text:
        label:
        badge:
        text: Item 1 text.
        url:
        background_c:
        accent_c:
    postscript:
      copy:
      ctas:
    settings:
      layout:
        buffer:
        margin: mt-n9 p-5 p-xl-6
      styles:
        background_c:
        tint_shade:
        panel_font:
        accent_c:
      config:
        edit_mode_only: false
        include_heading_postscript: true
  - _bookshop_name: design-system/generic/separator
    separator_c: wvu-gold
    settings:
      styles:
        background_c: wvu-blue
      layout:
        margin:
        padding: py-xl-0 py-xxl-0
      config:
        include_heading_postscript: false
  - _bookshop_name: design-system/section/cta-banner
    heading: Heading
    subheading: Subheading goes here.
    text:
    buttons:
      - text: Button Text
        url: https://www.wvu.edu
        icon: book
        button_c: wvu-gold
    settings:
      styles:
        background_c:
        buttons_c:
      layout:
        margin:
        buffer:
      config:
        edit_mode_only: false
        include_heading_postscript: true
  - _bookshop_name: design-system/section/columns-2-1
    heading: Heading Test
    subheading: Subheading goes here.
    column_a:
      _bookshop_name: design-system/column/factoids
      heading: By the Numbers
      items:
        - pre: According to Adam
          stat: 95%
          post: of statistics are made up
          source: Adam
      config:
        edit_mode_only: false
      styles:
    column_b:
      _bookshop_name: design-system/column_sm/factoids
      heading: By the Numbers
      items:
        - pre: Pre text
          stat: 95%
          post: Post text.
          source: Source
      config:
        edit_mode_only: false
        source:
          disable: false
      styles:
        container:
          margin_bottom: mb-4
        factoid:
          font: wvu-shout
          size: display-1
          color: text-wvu-gold
        divider:
    postscript:
      copy: Copy
      ctas:
        - text: CTA
          icon: book
          url:
    settings:
      styles:
        background_c:
      layout:
        margin:
        buffer:
      config:
        edit_mode_only: false
        include_heading_postscript: true
  - _bookshop_name: design-system/section/columns-2
    heading: Heading
    subheading: Subheading goes here.
    column_a:
      _bookshop_name: design-system/column/factoids
      heading: By the Numbers
      items:
        - pre: According to Adam
          stat: 95%
          post: of statistics are made up.
          source: Adam
      config:
        edit_mode_only: false
      styles:
    column_aa:
      _bookshop_name: design-system/column/youtube-video
      heading: Featured Video
      title: Video Title
      description: Video description.
      video_id: EMhV-NvxrAo
    postscript:
      copy:
      ctas:
    settings:
      styles:
        background_c:
      layout:
        margin:
        buffer:
      config:
        edit_mode_only: false
        include_heading_postscript: true
  - _bookshop_name: design-system/section/columns-2-1-1
    heading: Heading
    subheading: Subheading goes here.
    column_a:
      _bookshop_name: design-system/column/factoids
      heading: By the Numbers
      items:
        - pre: According to Adam
          stat: 95%
          post:
          source:
      config:
        edit_mode_only: false
      styles:
    column_b:
      _bookshop_name: design-system/column_sm/factoids
      heading: By the Numbers
      items:
        - pre: Pre text
          stat: 95%
          post: Post text.
          source: Source
      config:
        edit_mode_only: false
        source:
          disable: false
      styles:
        container:
          margin_bottom: mb-4
        factoid:
          font: wvu-shout
          size: display-1
          color: text-wvu-gold
        divider:
    column_c:
      _bookshop_name: design-system/column_sm/poster
      heading: Headline
      subheading: Subheading goes here.
      body: Here is some body copy.
      ctas:
        - text: CTA
          url:
    postscript:
      copy:
      ctas:
    settings:
      styles:
        background_c:
      layout:
        margin:
      config:
        edit_mode_only: false
        include_heading_postscript: true
  - _bookshop_name: design-system/section/faculty-members
    heading: Heading
    subheading: Subheading goes here.
    tags:
      - Eberly Faculty
    postscript:
      copy:
      ctas:
    settings:
      styles:
        background_c:
      layout:
        margin:
        buffer:
      config:
        edit_mode_only: false
        include_heading_postscript: true
        show_content: false
uuid: 68221203-9475-44af-afa0-b4d81543c569
type: guide-test
---
