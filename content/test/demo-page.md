---
_schema: guide_page
title: Demo Page
uuid: 8c4065b3-8133-4271-b3a0-ce2a62bb14b6
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
      _bookshop_name: design-system/column_sm/student-profile
      heading: Student Profile
      student: a2c13034-c9a5-4acc-8a16-0519d915389f
      config:
        edit_mode_only: false
        show_content: false
    config:
      edit_mode_only: false
      show_content: false
    layout:
    styles:
  - _bookshop_name: design-system/section/columns-2-1-1
    column_a:
    column_b:
      _bookshop_name: design-system/column_sm/profile-generic
      label: Profile
      thumbnail:
      superheading:
        - Superheading Line 1
      heading: Firstname Lastname
      subheading:
        - Subheading Line 1
      lists: []
      cta:
        - text: View Profile
          url: https://wvu.edu
      config:
        edit_mode_only: false
    column_c:
      _bookshop_name: design-system/column_sm/calendar-events
      heading: Events
      subheading:
      event_feed: >-
        <div id="localist-widget-19280350" class="localist-widget"></div><script
        defer type="text/javascript"
        src="https://cal.wvu.edu/widget/view?schools=wvu&days=31&num=5&experience=inperson&container=localist-widget-19280350&template=dsv2-vertical-mini"></script>
      link_text: All Events
      url: https://cal.wvu.edu
      config:
        edit_mode_only: false
    config:
      edit_mode_only: false
    layout:
    styles:
  - _bookshop_name: design-system/section/columns-2-1-1
    column_a:
    column_b:
      _bookshop_name: design-system/column_sm/contacts
      heading: Contacts
      people:
        - contact:
      config:
        edit_mode_only: false
    column_c:
    config:
      edit_mode_only: false
    layout:
    styles:
---
