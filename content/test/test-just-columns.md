---
_schema: guide_page
title: Test Just Columns
uuid: 24cbb5f1-4d84-4f5e-91f4-c0fd22ed6a29
type: guide
description:
topper:
  _bookshop_name: design-system/topper/hero
  label:
  background_image:
  alt_text:
  heading:
    - text: Heading
      highlight:
  subheading: Subheading goes here.
  body_text: ''
  styles:
    vibe: down-to-business
    background_c:
    heading_c:
    enable_blend: false
    enable_pattern: false
    tint_opacity: 0.5
    container_margin:
content_blocks:
  - _bookshop_name: design-system/section/columns-2-1-1
    column_a:
      _bookshop_name: design-system/column/factoids
      heading: By the Numbers
      items:
        - pre: Pre text
          stat: 97%
          post: post text.
          source: Source
      config:
        edit_mode_only: false
      styles:
    column_b:
    column_c:
    config:
      edit_mode_only: false
    layout:
    styles:
  - _bookshop_name: design-system/section/video-feature
    title: Video Title
    description: Video description.
    id: EMhV-NvxrAo
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/columns-2
    column_a:
      _bookshop_name: design-system/column/youtube-video
      title: Video Title
      description: Video description.
      video_id: EMhV-NvxrAo
    column_aa:
      _bookshop_name: design-system/column_sm/calendar-events
      heading: Events
      subheading:
      event_feed: >-
        <div id="localist-widget-88670364" class="localist-widget"></div><script
        defer type="text/javascript"

        src="https://cal.wvu.edu/widget/view?schools=wvu&days=31&num=3&experience=inperson&container=localist-widget-88670364&template=dsv2-vertical-mini"></script>
      link_text: More Events
      url: https://www.wvu.edu
      config:
        edit_mode_only: false
    config:
      edit_mode_only: false
    layout:
    styles:
---
