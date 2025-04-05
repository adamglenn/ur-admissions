---
title: Home
topper:
  _bookshop_name: design-system/topper/hero
  label:
  background_image:
  alt_text:
  heading:
    - text: It Starts Now Test.
      highlight:
  subheading: Subheading.
  body_text: >-
    Here is some body text. Here is some **bold text**. Here is [a
    link](https://www.wvu.edu).
  styles:
    vibe: wvu-experience
    background_c: bg-wvu-blue text-white
    gradient_1:
    gradient_2:
    gradient_3:
    heading_c: wvu-gold
    enable_blend: false
    enable_pattern: false
    tint_opacity: '0.5'
    container_margin: my-6
  layout:
    container_margin: mb-6
  config:
    show_label: false
content_blocks:
  - _bookshop_name: design-system/section/page-collection
    heading: Heading
    subheading: Subheading.
    items:
      - title: Item 1 Title
        text: Item 1 text.
        url:
        background_c:
      - title: Item 1 Title
        text: Item 1 text.
        url:
        background_c: bg-wvu-accent--sunset text-dark
      - title: Item 1 Title
        text: Item 1 text.
        url:
        background_c: bg-wvu-neutral--cream text-dark
    postscript:
      copy: Test postscript.
      postscript_ctas:
        _bookshop_name: design-system/generic/button-group
        buttons:
          - text: My Button
            url:
            icon: book
          - text: Another Button
            url:
            icon: user
    layout:
      margin: mt-n9 p-5 p-xl-6
    styles:
      background_c: bg-wvu-neutral--warm-gray-light text-dark
      panels:
      item_headings:
      margin:
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/big-search
    label: Label
    heading: Big Search Heading
    subheading: Subheading.
    postscript:
      copy: Postscript.
      postscript_links:
        - text: Here is my Button
          icon: book
          url:
    layout:
      margin: mb-6
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/alternating-grid
    heading: Alternating Grid Heading
    subheading: Subheading goes here.
    items:
      - heading: Item Heading
        image: /uploads/34750-s-bfp-0046-xx.jpg
        alt_text:
        copy: Here is my copy.
        item_ctas:
          _bookshop_name: design-system/generic/buttons
          buttons:
            - text: CTA 1
              url: https://www.wvu.edu
              icon: book
      - heading: Item Heading
        image:
        alt_text:
        copy: ''
        item_ctas:
          _bookshop_name: design-system/generic/link-list
          list_style: wvu-ul-arrows
          items:
            - text: Here is my item
              url: https://www.wvu.edu
    postscript:
      copy: ''
      postscript_ctas:
        _bookshop_name: design-system/generic/button-group
        buttons:
          - text: Button Text
            url: https://www.wvu.edu
            icon: book
    layout:
      margin: my-n9 p-5 p-xl-6
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/quicklinks
    heading: Quicklinks
    links:
      - text: Text
        url: /url
      - text: Text
        url: /url
      - text: Text
        url: /url
    layout:
      margin: mt-6
    styles:
      background_c: bg-wvu-neutral--warm-gray-dark text-white
    config:
      edit_mode_only: false
---
