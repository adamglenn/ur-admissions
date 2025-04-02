---
_schema: detail_page
title: New Detail Page
description:
topper:
  _bookshop_name: design-system/topper/default
  subheading: My subheading.
detail_blocks:
  - _bookshop_name: design-system/column/rich-text
    text: |-
      Text. **Here is some markdown bold text.**

      ## Heading \{ class="text-wvu-gold" \}

      New Paragraph

      * List Item
      * Another List Item

      [Here is a button](https://www.wvu.edu) \{ class="btn btn-primary" \}
  - _bookshop_name: design-system/column/link-list-panels
    heading: Link List Panels
    list_description: Link list panels description.
    items:
      - text: My List Item
        description: Description for list item.
        url: https://wvu.edu
        icon: Download
  - _bookshop_name: design-system/column/accordion
    panels:
      - title: Panel 1 Title
        panel_text: Panel 1 text.
      - title: Panel 2 Title
        panel_text: Panel 2 text.
      - title: Panel 3 Title
        panel_text: Panel 3 text.
detail_sidebar_blocks:
uuid: a2793e2b-2e99-46bd-a324-e0892c4fa0ce
type: detail
---
