---
_schema: detail_page
title: Test Detail Blocks
uuid: 156356fd-49c4-4639-b93a-190839062bde
type: detail
description:
topper:
  _bookshop_name: design-system/topper/default
  topper_type: default
  heading: []
  subheading: Subheading.
  styles:
    vibe: down_to_business
    color_palette: wvu_blue
    enable_blend: false
    enable_pattern: false
    tint_opacity: 0.5
  vibe: down-to-business
  background_c: bg-light text-wvu-blue
  heading_c:
  background_layers:
    img_blend_mode:
    img_opacity: 0.4
    pattern:
    pattern_c: bg-white
    pattern_opacity: 0.2
    tint_opacity:
    texture: false
detail_blocks:
  - _bookshop_name: design-system/column/rich-text
    text: >-
      Text. How fast can I type? How fast can I type? Test type. How fast? Is
      this faster now?


      ## Here is a heading.


      Here is some more text.
  - _bookshop_name: design-system/column/accordion
    panels:
      - title: Panel 1 Title
        panel_text: Panel 1 text. Here is some text. Let's see how fast.
      - title: Panel 2 Title
        panel_text: Panel 2 text.
  - _bookshop_name: design-system/column/youtube-video
    title: Video Title
    description: Video description. Test speed.
    video_id: EMhV-NvxrAo
  - _bookshop_name: design-system/column/alert
    text: Text. Here is some text. How fast.
  - _bookshop_name: design-system/column/tabs
    tabs:
      - label: Tab 1
        text: Tab 1 text. More text.
  - _bookshop_name: design-system/column/link-list-panels
    heading: Here are files
    list_description: Reference the following files.
    items:
      - text: First Thing
        description: Description of first thing.
        url: /
        icon: Link
  - _bookshop_name: design-system/column/photo-block
    photos:
      - image: >-
          https://cloudcannondam.volutus.wvu.edu/admissions-test/hero-info-ftf-student-computer.jpg
        alt_text:
        caption:
      - image: /uploads/woodburn.webp
        alt_text:
        caption:
detail_sidebar_blocks:
  - _bookshop_name: design-system/column_sm/jump-links
    items:
      - text: Here is a heading.
        anchor: here-is-a-heading
---
