---
title:
uuid:
description:
topper:
content_blocks:
---

## Page Blocks

fields:
  - name: blocks
    label: Page Blocks
    type: array
    schema:
      labelKey: type
      typeKey: type
      oneOf:
        - label: Button Block
          type: object
          fields:
            - name: type
              type: hidden
              default: button

            - name: label
              label: Button Label
              type: text

            - name: url
              label: Button URL
              type: text

            - name: style
              label: Button Style
              type: select
              options:
                - default
                - glitch
                - ghost
                - danger