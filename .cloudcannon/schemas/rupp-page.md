name: Custom Page
label: Custom Page
icon: code

fields:
  - name: title
    label: Page Title
    type: text

  - name: content
    label: Content
    type: markdown

  - name: detail_blocks
    label: Custom Blocks
    type: array
    schema:
      labelKey: type
      typeKey: type
      oneOf:
        - label: Glitch Block
          type: glitch_block
          fields:
            - name: type
              type: hidden
              default: glitch_block
            - name: text
              label: Glitched Text
              type: textarea

        - label: Redacted Note
          type: redacted_note
          fields:
            - name: type
              type: hidden
              default: redacted_note
            - name: note
              label: Note
              type: textarea