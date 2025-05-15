---
_schema: guide_page_test
title: Link Lists
description:
topper:
  _bookshop_name: design-system/topper/hero
  label: ''
  background_image: ''
  alt_text: ''
  heading: Heading
  subheading: Subheading.
  body_text: ''
  settings:
    styles:
      audience: general
      tone: 1
      color_palette: option-3
      gradient:
      enable_blend: false
      enable_pattern: false
      tint_opacity: '0.5'
    layout:
      margin:
      buffer: pb-6
      text_placement: mx-auto
    config:
      show_label: true
content_blocks:
  - _bookshop_name: design-system/section/link-lists
    heading: Heading
    subheading:
    lists:
      - topic: My Topic
        description: My description.
        items:
          - text: Link Text
            url: https://www.wvu.edu
          - text: Another Link
            url:
      - topic: Second Topic
        description: Another description.
        items: []
    settings:
      styles:
        audience: general
        tone: 3
        color_palette: option-2
      layout:
        margin:
        buffer: mt-n9
        padding: py-6 py-xxl-7
      config:
        edit_mode_only: false
        include_heading_postscript: false
uuid: 125799f9-331b-47d4-baa2-a2026deaeef0
type: guide
---
