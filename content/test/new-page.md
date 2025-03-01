---
_schema: guide_page
title: New Page
uuid: 0c23cee6-5171-4aab-a361-5da8583ea4d6
type: guide
description:
topper:
  _bookshop_name: design-system/topper/hero
  topper_type: hero
  name: hero-topper
  label:
  background_image: ''
  alt_text: ''
  heading:
    - text: It Starts
      highlight: ''
    - text: Now
      highlight: ''
  subheading: Subheading. Test how fast.
  body_text: ''
  styles:
    vibe: nostalgic
    color_palette: wvu-blue
    enable_blend: false
    enable_pattern: false
    tint_opacity: 0.5
    margin:
content_blocks:
  - _bookshop_name: design-system/section/alternating-grid
    heading: Test Alternating Grid Component
    items:
      - heading: Item 1
        image: /uploads/woodburn.webp
        alt_text: Woodburn Hall
        copy: Here is my copy.
        ctas:
          - text: Button
            icon: hiking
            url: https://www.wvu.edu
      - heading: Item 2
        image: /uploads/hero-info-ftf-student-computer.jpg
        alt_text: Student working on a computer
        copy: Copy for item 2.
        ctas:
    postscript:
      postscript_links:
      text:
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/alumni-profile
    heading: Heading
    name: Firstname Lastname
    image: https://cloudcannondam.volutus.wvu.edu/admissions-test/jillian-cutout.webp
    label:
      - Alumni
      - Class of 2021
    info:
      - Morgantown, WV
      - CEO, Big Company
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/article-collection
    heading: Article Collection Heading
    tags:
      - featured
    limit: 5
    config:
      edit_mode_only: false
      hide_collection_pages: true
  - _bookshop_name: design-system/section/big-search
    label: Label
    heading: Big Search Heading
    subheading: Subheading.
    postscript:
      copy:
      postscript_links:
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/button-group
    heading: Heading
    body: Body.
    buttons:
      - text: Call to Action
        url: https://www.wvu.edu
        icon: hammer
      - text: Call to Action
        url:
        icon: ship
    postscript:
      copy: Here is my postscript.
      postscript_links:
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/calendar-events
    heading: Heading
    subheading: Test subheading.
    event_feed:
    postscript:
      copy:
      postscript_links:
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/hero-list
    heading: Hero List Heading
    body: Hero list body
    ctas:
      - text: My Text
        icon: cat
        url:
    postscript_links:
    config:
      edit_mode_only: false
      is_main: true
  - _bookshop_name: design-system/section/icon-bar
    text: Hello World!
    items:
      - icon: book
        text: Text
        url:
      - icon: sandwich
        text: Sandwich
        url:
      - icon: pizza
        text: Pizza
        url:
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/link-lists
    background_image:
    alt_text:
    heading: Heading
    subheading: Subheading
    lists:
      - topic: My Topic
        description: My description.
        items:
          - site_page:
            text: Link 1
            url:
    config:
      edit_mode_only: false
      is_main: true
      id:
      aria_labelledby:
  - _bookshop_name: design-system/section/object-list
    heading: Hello World!
    subheading: Here is my subheading.
    text: Here is my text.
    items:
      - image: >-
          https://cloudcannondam.volutus.wvu.edu/admissions-test/hero__social-swag.jpg
        image_alt: Social media stuff.
        heading: Item Heading
        text:
        links:
          - text: Call to Action
            url:
    config:
      edit_mode_only: false
---
