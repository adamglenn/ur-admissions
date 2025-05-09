---
_schema: guide_page_test
title: Articles
description:
topper:
  _bookshop_name: design-system/topper/hero
  label: ''
  background_image: ''
  alt_text: ''
  heading:
    - text: Heading
      highlight: ''
  subheading: Subheading.
  body_text: ''
  settings:
    styles:
      background_c:
      gradient:
      heading_c:
      enable_blend: false
      enable_pattern: false
      tint_opacity: "0.5"
    layout:
      margin:
      buffer:
      text_placement:
    config:
      show_label: true
content_blocks:
  - _bookshop_name: design-system/section/columns-2-1-1
    heading: Heading
    subheading: Subheading goes here.
    column_a:
      _bookshop_name: design-system/column/article-collection
      heading: Article Collection Heading
      article_tags:
        - Custom Label
      postscript:
        copy:
        ctas:
      settings:
        styles:
          background_c:
        layout:
          margin:
          buffer:
          max_cols:
        config:
          edit_mode_only: false
          limit:
          show_content: false
    column_b:
      _bookshop_name: design-system/column_sm/article-collection
      heading: Articles
      article_tags:
        - Custom Label
      limit: 5
      config:
        edit_mode_only: false
        show_content: false
    column_c:
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
uuid: cab525a2-6f5e-497f-9cf0-185bc7eafa9b
type: guide-test
---
