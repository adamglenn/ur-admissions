---
_schema: guide_page
title: New Guide Page
description: What's a guide page?
topper:
  _bookshop_name: design-system/topper/hero
  heading: []
  subheading: Subheading.
  styles:
    vibe: down-to-business
    enable_blend: false
    enable_pattern: false
    tint_opacity: '0.5'
content_blocks:
  - _bookshop_name: design-system/section/cards-list
    heading: Hello World!
    subheading: Bunch cards here!
    label: Label for the cards list
    items:
      - image: /uploads/fern-mq-1.jpg
        image_alt: Ernest goes to horticulture class
        heading: Moral Responsibility
        text: >-
          A significant consequence often drawn from this argument is that if
          determinism is true and libertarian free will is impossible, then
          traditional notions of moral responsibility (based on praise and blame
          for actions one could not have avoided doing) are undermined. This
          leads to further debates about whether responsibility can be redefined
          (perhaps compatibilistically) or if our practices of punishment and
          reward need radical revision.
        links:
          - text: The link goes nowhere
            url: '#'
      - image: /uploads/desert-mq.jpg
        image_alt: whole big buncha text
        heading: Compatibilism
        text: >-
          This argument specifically targets the libertarian concept of free
          will. Compatibilists (or Soft Determinists) disagree, arguing that
          free will is compatible with determinism. They do this by redefining
          free will, often removing the requirement for alternative
          possibilities or ultimate sourcehood in the strong sense. For a
          compatibilist, freedom might mean acting voluntarily according to
          one's desires and values, without coercion, even if those desires and
          values are themselves determined. This argument presented above
          rejects that compatibilist redefinition as insufficient for the kind
          of free will often thought necessary for deep moral responsibility.
        links: []
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/calendar-events
    heading: Upcoming Events maybe?
    subheading: 'Did i get the event feed right? '
    event_feed: https://cal.wvu.edu/department/college_of_applied_human_sciences
    postscript:
      copy: ''
      postscript_links:
        - text:
          icon:
          url:
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/columns-2-1-1
    column_a:
      _bookshop_name: design-system/column/contacts
      heading: Contacts
      people:
        - label: For Inquiries, Contact
          contact: 58497c86-ba80-4789-8f62-e823130a7669
        - label: For Inquiries, Contact
          contact: caca3806-54ce-4be2-940f-950138ac1a03
      config:
        edit_mode_only: false
        show_content: false
    column_b:
      _bookshop_name: design-system/column_sm/factoids
      heading: By the Numbers
      items:
        - pre: You miss
          stat: 95%
          post: of the shots you don't take.
          source: Wayne Gurtzkie
        - pre: You make
          stat: 5%
          post: of the shots you don't miss.
          source: Steve
      config:
        edit_mode_only: false
        source:
          disable: false
      styles:
        container:
          margin_bottom: mb-4
        factoid:
          font: wvu-shout
          size: display-1
          color: text-wvu-gold
        divider:
    column_c:
      _bookshop_name: design-system/column_sm/poster
      heading: Free Will
      subheading: Cannot Exist in a Deterministic Universe
      body: >-
        Since both **core requirements** for *meaningful* (libertarian) free
        will – the ability to do otherwise and being the ultimate source of
        one's actions – are incompatible with the nature of a deterministic
        universe, it follows that if the universe is deterministic, this kind of
        free will does not exist.
      ctas:
        - text:
          url:
    config:
      edit_mode_only: false
    layout:
    styles:
      - typography_palettes
  - _bookshop_name: design-system/section/testimonials
    heading: Testimonials?
    subheading: yes, really, testimonials!
    testimonials:
      - label: Know what i mean fern?
        name: Ernest
        title: 'Horticulture Extraordinaire '
        image: /uploads/fern-mq-1.jpg
        quote: >-
          A significant consequence often drawn from this argument is that if
          determinism is true and libertarian free will is impossible, then
          traditional notions of moral responsibility (based on praise and blame
          for actions one could not have avoided doing) are undermined. This
          leads to further debates about whether responsibility can be redefined
          (perhaps compatibilistically) or if our practices of punishment and
          reward need radical revision.
    config:
      edit_mode_only: false
  - _bookshop_name: design-system/section/place
    heading: The Quad
    subheading: Where's the quad?
    text: 'It''s in the square. '
    ctas:
      - text: Details on the quad
        url: /test/new-detail-page/
    config:
      edit_mode_only: false
uuid: 47693e90-72d2-4f8b-a4bc-9782d9f22c0d
type: guide
---
