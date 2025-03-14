---
_schema: guide_page
title: New Page
uuid: 0c23cee6-5171-4aab-a361-5da8583ea4d6
type: guide
description:
topper:
  _bookshop_name: design-system/topper/hero
  label:
  background_image:
  alt_text:
  heading:
    - text:
      highlight:
  subheading: Subheading.
  body_text:
  styles:
    vibe: down-to-business
    color_palette:
    background_c: bg-white text-dark
    gradient_1:
    gradient_2:
    gradient_3:
    heading_c: text-wvu-blue
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
    image: /uploads/jillian.png
    is_cutout: true
    label:
      - Alumni
      - Class of 2021
    info:
      - Morgantown, WV
      - CEO, Big Company
    ctas:
      - text: Call to Action
        url:
        icon:
      - text: Call to Action
        url:
        icon: pizza
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
  - _bookshop_name: design-system/section/cards-list
    heading: Hello World!
    subheading: Here is my subheading.
    label: My Label
    items:
      - image: >-
          https://cloudcannondam.volutus.wvu.edu/admissions-test/hero__social-swag.jpg
        image_alt: Social media stuff.
        heading: Item 2 Heading
        item_text:
        links:
          - text: Call to Action
            url:
      - image: >-
          https://cloudcannondam.volutus.wvu.edu/admissions-test/hero__social-swag.jpg
        image_alt: Social media stuff.
        heading: Item Heading
        item_text:
        links:
          - text: Call to Action
            url:
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/page-collection
    heading: Heading
    subheading: Subheading.
    items:
      - title: Item 1 Title
        text: Item 1 text.
        url:
      - title: Item 2 Title
        text: Item 1 text.
        url:
      - title: Item 3 Title
        text: Item 1 text.
        url:
    config:
      edit_mode_only: false
    styles:
      panels:
      item_headings:
      margin:
    lead: Lead text.
  - _bookshop_name: design-system/section/page-collection-vertical-sticky
    heading: Heading Test
    items:
      - title: Item 1 Title
        text: Item 1 text.
        url:
      - title: Item 1 Title
        text: Item 1 text.
        url:
    lead: Lead text.
    config:
      edit_mode_only: false
    layout:
      margin_y:
    styles:
      panels:
      item_headings:
  - _bookshop_name: design-system/section/place
    heading: Place Heading
    subheading: Subheading goes here.
    text: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua.
    ctas:
      - text: Call to Action
        url:
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/poster
    name: poster-split
    alt_text:
    heading:
      - Heading Line 1
      - Heading Line 2
    body:
      - Lede.
      - Body.
    ctas: []
    postscript_links: []
    config:
      edit_mode_only: false
      is_main:
      id:
      aria_labelledby:
    background_image:
  - _bookshop_name: design-system/section/poster-split
    name: poster-split
    poster_image:
    alt_text:
    heading:
      - Heading Line 1
      - Heading Line 2
    body:
      - Lede.
      - Body.
    ctas: []
    postscript_links: []
    config:
      edit_mode_only: false
      is_main: true
      id:
      aria_labelledby:
  - _bookshop_name: design-system/section/testimonials
    heading: Testimonials Heading
    subheading: Subheading Test.
    testimonials:
      - label:
        name: Firstname Lastname
        title: Title
        image: https://cloudcannondam.volutus.wvu.edu/admissions-test/jillian.png
        quote: Here is my quote.
    config:
      edit_mode_only: false
---
