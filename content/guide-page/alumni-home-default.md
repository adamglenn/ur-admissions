---
_schema: guide_page
title: Alumni Home - Default
topper:
  _bookshop_name: design-system/topper/hero
  heading: Heading
  subheading: Subheading.
  ctas: []
  settings:
    styles:
      audience: general
      tone: default
      color_palette: option-1
      enable_blend: false
      enable_pattern: false
      tint_opacity: '0.7'
    layout:
      text_placement: mx-auto text-center
    config:
      show_label: true
content_blocks:
  - _bookshop_name: design-system/section/icon-bar
    items:
      - icon: book
        text: Scholarships
        url:
      - icon: book
        text: Benefits
        url:
      - icon: book
        text: Renew Your Membership
        url:
      - icon: book
        text: Update Your Information
        url:
      - icon: globe-americas
        text: Alumni Trips
        url:
    settings:
      styles:
        audience: general
        tone: loud
        color_palette: option-8
      layout:
        margin:
        buffer:
        padding: py-5
      config:
        edit_mode_only: false
        include_heading_postscript: false
  - _bookshop_name: design-system/section/columns-2-1-1
    background_image:
    column_a:
      _bookshop_name: design-system/column/top-story
      heading: Top Story
      article_tags:
        - Custom Label
      config:
        edit_mode_only: false
        hide_author: false
        show_content: false
    column_b:
      _bookshop_name: design-system/column_sm/poster
      heading: Alumni News
      subheading: Check out alumni news on WVUToday.
      body: ''
      ctas: []
    column_c:
      _bookshop_name: design-system/column_sm/teasers-generic
      items:
        - heading: Spotlight
          icon: lightbulb-on
          tags: []
          ctas:
            - text: All Spotlights
              icon: arrow-circle-right
              url:
        - heading: ALL 'EERS Podcast
          icon: podcast
          tags: []
          ctas: []
        - heading: From Down the Hall
          icon: rss
          tags: []
          ctas: []
    settings:
      styles:
        background_c:
        gradient:
        heading_c:
        enable_blend: false
        enable_pattern: false
        tint_opacity: '0.5'
      layout:
        buffer:
        padding: py-5 py-xxl-6
      config:
        show_label: true
        include_heading_postscript: false
properties:
  exclude_from_navigation: false
  exclude_from_search_engines: false
  meta_description:
  social_image:
uuid: 5ae2fc2e-b868-4ce3-9c6e-c31f9e4cdbd8
type: guide
---
