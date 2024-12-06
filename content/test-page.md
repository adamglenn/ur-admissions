---
title: Test Page
topper:
  _bookshop_name: topper/default
content_blocks:
  - _bookshop_name: section/hero
    heading: My Hero
    body:
    ctas:
    postscript_links:
    config:
      is_main: true
  - _bookshop_name: section/backpage
    main:
      - detail_blocks:
          - _bookshop_name: detail/rich-text
            text: Here is my text.
          - _bookshop_name: detail/accordion
            panels:
              - title: Panel 1 Title
                text: Panel 1 text.
              - title: Panel 2 Title
                text: Panel 2 text.
          - _bookshop_name: detail/tabs
            tabs:
              - link: Tab 1
                text: Tab 1 text.
              - link: Tab 2
                text: Tab 1 text.
          - _bookshop_name: detail/youtube-video
            title: Video Title
            description: Video description.
            video_id: EMhV-NvxrAo
    sidebar: []
---
