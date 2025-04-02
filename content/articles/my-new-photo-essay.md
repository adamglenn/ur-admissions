---
_schema: photo_essay
title: >-
  Can we add CSS classes to specific sections? So if for example I want to
  control the line-length for a specific page  I might add right padding. 
subheading: >-
  Can we add CSS classes to specific sections? So if for example I want to
  control the line-length for a specific page  I might add right padding. 
authors:
  - author: 1431914c-f6cc-4749-b4db-06e585933d66
    article_role: Author
publishDate: 2025-03-18T22:44:24-04:00
description:
article_topper:
  _bookshop_name: design-system/topper/article-hero
  label:
  background_image: /uploads/wvu-core-planeria.jpg
  alt_text: Planeria
  heading:
  body_text: 'What is this body text? '
  show_byline: true
  styles:
    vibe: down-to-business
    enable_blend: false
    enable_pattern: false
    tint_opacity: '0.5'
    margin:
photo_essay_blocks:
  - _bookshop_name: design-system/section/rich-text
    text: >-


      # Markdown: Syntax{ class="text-wvu-accent--sunset"}
      
      *   [Overview](#overview)
          *   [Philosophy](#philosophy)
          *   [Inline HTML](#html)
          *   [Automatic Escaping for Special Characters](#autoescape)
      *   [Block Elements](#block)
          *   [Paragraphs and Line Breaks](#p)
          *   [Headers](#header)
          *   [Blockquotes](#blockquote)
          *   [Lists](#list)
          *   [Code Blocks](#precode)
          *   [Horizontal Rules](#hr)
      *   [Span Elements](#span)
          *   [Links](#link)
          *   [Emphasis](#em)
          *   [Code](#code)
          *   [Images](#img)
          {.bg-wvu-gold}
      *   [Miscellaneous](#misc)
          *   [Backslash Escapes](#backslash)
          *   [Automatic Links](#autolink)
      
      **Note:** This document is itself written using Markdown; you
      can [see the source for it by adding '.text' to the URL](/projects/markdown/syntax.text).
      
      ----
      
      ## Overview
      
      ### Philosophy
      
      Markdown is intended to be as easy-to-read and easy-to-write as is feasible.
      { class="bg-wvu-accent--blue-light" }
      
      Readability, however, is emphasized above all else. A Markdown-formatted
      document should be publishable as-is, as plain text, without looking
      like it's been marked up with tags or formatting instructions. While
      Markdown's syntax has been influenced by several existing text-to-HTML
      filters -- including [Setext](http://docutils.sourceforge.net/mirror/setext.html), [atx](http://www.aaronsw.com/2002/atx/), [Textile](http://textism.com/tools/textile/), [reStructuredText](http://docutils.sourceforge.net/rst.html),
      [Grutatext](http://www.triptico.com/software/grutatxt.html), and [EtText](http://ettext.taint.org/doc/) -- the single biggest source of
      inspiration for Markdown's syntax is the format of plain text email.
      
      ## Block Elements{ class="bg-wvu-accent--blue-light p-4" }
      
      ### Paragraphs and Line Breaks{.text-wvu-gold}
      
      A paragraph is simply one or more consecutive lines of text, separated
      by one or more blank lines. (A blank line is any line that looks like a
      blank line -- a line containing nothing but spaces or tabs is considered
      blank.) Normal paragraphs should not be indented with spaces or tabs.{.text-wvu-gold}
      
      The implication of the "one or more consecutive lines of text" rule is
      that Markdown supports "hard-wrapped" text paragraphs. This differs
      significantly from most other text-to-HTML formatters (including Movable
      Type's "Convert Line Breaks" option) which translate every line break
      character in a paragraph into a `<br />` tag.
      
      When you *do* want to insert a `<br />` break tag using Markdown, you
      end a line with two or more spaces, then type return.
      
      ### Headers
      
      Markdown supports two styles of headers, [Setext] [1] and [atx] [2].
      
      Optionally, you may "close" atx-style headers. This is purely
      cosmetic -- you can use this if you think it looks better. The
      closing hashes don't even need to match the number of hashes
      used to open the header. (The number of opening hashes
      determines the header level.)
      
      
      ### Blockquotes
      
      Markdown uses email-style `>` characters for blockquoting. If you're
      familiar with quoting passages of text in an email message, then you
      know how to create a blockquote in Markdown. It looks best if you hard
      wrap the text and put a `>` before every line:
      
      > This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
      > consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
      > Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
      > 
      > Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
      > id sem consectetuer libero luctus adipiscing.
      
      Markdown allows you to be lazy and only put the `>` before the first
      line of a hard-wrapped paragraph:
      
      > This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
      consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
      Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
      
      > Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
      id sem consectetuer libero luctus adipiscing.
      
      Blockquotes can be nested (i.e. a blockquote-in-a-blockquote) by
      adding additional levels of `>`:
      
      > This is the first level of quoting.
      >
      > > This is nested blockquote.
      >
      > Back to the first level.
      
      Blockquotes can contain other Markdown elements, including headers, lists,
      and code blocks:
      
      > ## This is a header.
      > 
      > 1.   This is the first list item.
      > 2.   This is the second list item.
      > 
      > Here's some example code:
      > 
      >     return shell_exec("echo $input | $markdown_script");
      
      Any decent text editor should make email-style quoting easy. For
      example, with BBEdit, you can make a selection and choose Increase
      Quote Level from the Text menu.
      
      
      ### Lists
      
      Markdown supports ordered (numbered) and unordered (bulleted) lists.
      
      Unordered lists use asterisks, pluses, and hyphens -- interchangably
      -- as list markers:
      
      *   Red
      *   Green
      *   Blue
      
      is equivalent to:
      
      +   Red
      +   Green
      +   Blue
      
      and:
      
      -   Red
      -   Green
      -   Blue
      
      Ordered lists use numbers followed by periods:
      
      1.  Bird
      2.  McHale
      3.  Parish
      
      It's important to note that the actual numbers you use to mark the
      list have no effect on the HTML output Markdown produces. The HTML
      Markdown produces from the above list is:
      
      If you instead wrote the list in Markdown like this:
      
      1.  Bird
      1.  McHale
      1.  Parish
      
      or even:
      
      3. Bird
      1. McHale
      8. Parish
      
      you'd get the exact same HTML output. The point is, if you want to,
      you can use ordinal numbers in your ordered Markdown lists, so that
      the numbers in your source match the numbers in your published HTML.
      But if you want to be lazy, you don't have to.
      
      To make lists look nice, you can wrap items with hanging indents:
      
      *   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
          Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
          viverra nec, fringilla in, laoreet vitae, risus.
      *   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
          Suspendisse id sem consectetuer libero luctus adipiscing.
      
      But if you want to be lazy, you don't have to:
      
      *   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
      Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
      viverra nec, fringilla in, laoreet vitae, risus.
      *   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
      Suspendisse id sem consectetuer libero luctus adipiscing.
      
      List items may consist of multiple paragraphs. Each subsequent
      paragraph in a list item must be indented by either 4 spaces
      or one tab:
      
      1.  This is a list item with two paragraphs. Lorem ipsum dolor
          sit amet, consectetuer adipiscing elit. Aliquam hendrerit
          mi posuere lectus.
      
          Vestibulum enim wisi, viverra nec, fringilla in, laoreet
          vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
          sit amet velit.
      
      2.  Suspendisse id sem consectetuer libero luctus adipiscing.
      
      It looks nice if you indent every line of the subsequent
      paragraphs, but here again, Markdown will allow you to be
      lazy:
      
      *   This is a list item with two paragraphs.
      
          This is the second paragraph in the list item. You're
      only required to indent the first line. Lorem ipsum dolor
      sit amet, consectetuer adipiscing elit.
      
      *   Another item in the same list.
      
      To put a blockquote within a list item, the blockquote's `>`
      delimiters need to be indented:
      
      *   A list item with a blockquote:
      
          > This is a blockquote
          > inside a list item.
      
      To put a code block within a list item, the code block needs
      to be indented *twice* -- 8 spaces or two tabs:
      
      *   A list item with a code block:
      
              <code goes here>
      
      ### Code Blocks
      
      Pre-formatted code blocks are used for writing about programming or
      markup source code. Rather than forming normal paragraphs, the lines
      of a code block are interpreted literally. Markdown wraps a code block
      in both `<pre>` and `<code>` tags.
      
      To produce a code block in Markdown, simply indent every line of the
      block by at least 4 spaces or 1 tab.
      
      This is a normal paragraph:
      
          This is a code block.
      
      Here is an example of AppleScript:
      
          tell application "Foo"
              beep
          end tell
      
      A code block continues until it reaches a line that is not indented
      (or the end of the article).
      
      Within a code block, ampersands (`&`) and angle brackets (`<` and `>`)
      are automatically converted into HTML entities. This makes it very
      easy to include example HTML source code using Markdown -- just paste
      it and indent it, and Markdown will handle the hassle of encoding the
      ampersands and angle brackets. For example, this:
      
          <div class="footer">
              &copy; 2004 Foo Corporation
          </div>
      
      Regular Markdown syntax is not processed within code blocks. E.g.,
      asterisks are just literal asterisks within a code block. This means
      it's also easy to use Markdown to write about Markdown's own syntax.
      
      ```
      tell application "Foo"
          beep
      end tell
      ```
      
      ## Span Elements
      
      ### Links
      
      Markdown supports two style of links: *inline* and *reference*.
      
      In both styles, the link text is delimited by [square brackets].
      
      To create an inline link, use a set of regular parentheses immediately
      after the link text's closing square bracket. Inside the parentheses,
      put the URL where you want the link to point, along with an *optional*
      title for the link, surrounded in quotes. For example:
      
      This is [an example](http://example.com/) inline link.
      
      [This link](http://example.net/) has no title attribute.
      
      ### Emphasis
      
      Markdown treats asterisks (`*`) and underscores (`_`) as indicators of
      emphasis. Text wrapped with one `*` or `_` will be wrapped with an
      HTML `<em>` tag; double `*`'s or `_`'s will be wrapped with an HTML
      `<strong>` tag. E.g., this input:
      
      *single asterisks*
      
      _single underscores_
      
      **double asterisks**
      
      __double underscores__
      
      ### Code
      
      To indicate a span of code, wrap it with backtick quotes (`` ` ``).
      Unlike a pre-formatted code block, a code span indicates code within a
      normal paragraph. For example:
      
      Use the `printf()` function.
      

      ## Adding Class to Header{.text-wvu-gold}
      
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non nunc
      rhoncus, vulputate nunc eget, molestie ligula. Donec interdum vestibulum
      pretium. Vivamus sit amet urna ac urna fringilla consequat. Nam nunc
      ligula, luctus eget eleifend ut, iaculis nec ante. 
      
      
      ## Adding Class to Header{.text-wvu-gold .text-wvu-center}
      
      Nullam ac est
      fermentum, sollicitudin leo eu, consectetur sapien. Vestibulum non tortor
      sed lorem feugiat commodo. Sed rutrum, mauris a accumsan sagittis, mi
      sapien ultrices libero, vel accumsan metus libero nec tellus. Integer at
      turpis a tellus pulvinar tempus.


      Cras nulla ante, interdum eget enim vitae, gravida dignissim justo.{class="text-wvu-gold"}


      
      ## What about a table?{class="text-wvu-gold"}


      \| foo   \| bar   \| baz  \| \| xyzzy \| plugh \| thud \|


      **Quisque id dictum arcu.** Etiam luctus diam a quam tempor, at sodales
      augue maximus. Fusce a turpis sit amet nisl elementum aliquam non non
      diam. Donec volutpat ligula quis odio eleifend, non pretium quam porta.
      Sed porta rhoncus urna, eu fringilla felis sollicitudin vel. Quisque erat
      purus, convallis non tellus sed, tincidunt ullamcorper neque. Aliquam
      lacinia sodales tellus, vel scelerisque nibh ornare non.


      ## Quisque tincidunt nulla sed neque pretium blandit sed et tortor.&nbsp;


      Aliquam molestie bibendum nibh, eu fermentum orci mollis a. In
      pellentesque accumsan lectus vitae eleifend. Maecenas euismod elit eget mi
      porttitor scelerisque. Sed libero velit, rutrum et condimentum a, molestie
      et nibh.


      > Proin lobortis viverra dapibus. In hac habitasse platea dictumst.


      * None

      * Right{class="text-wvu-gold"}

      * Space Right{class="text-wvu-gold"}
      
      * Below{class="bg-wvu-accent--sunset"}
      
      * Space Below


      Maecenas condimentum leo dapibus mauris placerat, ac congue nibh
      hendrerit. Fusce ut dui vel dui rutrum fringilla nec nec justo. Nullam
      dignissim rutrum nunc eget varius. Donec viverra posuere convallis.
      Aliquam nec pellentesque arcu. Fusce interdum felis eu ligula aliquam, vel
      posuere eros fermentum. \{: .red\} 1. Bulleted List 2. Testing 3. Test


      Cras ultrices interdum tortor, ac tincidunt metus suscipit eu. Sed ut
      convallis dui. Quisque molestie scelerisque eros ut efficitur. Phasellus
      vel nisl ac lorem faucibus ultricies ac nec eros. Suspendisse
      pellentesque, justo sed facilisis lacinia, magna mauris convallis lacus,
      id bibendum ante enim et nisi. Donec at nulla et nisi tristique hendrerit
      nec ullamcorper sapien. Curabitur consectetur elit ac lectus mollis
      suscipit. Nullam fringilla lorem nunc, ac elementum tortor luctus a.
      Aenean finibus nunc magna, id finibus lacus sodales non. Pellentesque
      ornare dolor ac sapien dignissim viverra. In consectetur convallis dui.
      Nunc dictum magna et sem euismod, nec molestie metus sodales. Aliquam
      varius pretium ex, et malesuada lacus. Aenean volutpat magna a ex iaculis,
      vitae luctus dolor luctus.


      Donec sed tempus ex, ut dictum nisi. Vestibulum efficitur consequat
      sollicitudin. Etiam eu erat justo. Aliquam sollicitudin molestie gravida.
      Aliquam metus purus, tempus a est id, dapibus pharetra mi. Cras ornare sem
      at felis viverra vehicula. Donec lobortis commodo augue, id condimentum
      odio gravida ac. Curabitur eleifend, nunc vel rutrum ullamcorper, erat est
      congue ex, ac iaculis quam ligula a ligula. In condimentum tortor in justo
      ornare, sit amet tristique purus imperdiet. Suspendisse potenti.


      ## What happens if i insert a table here?


      \| Syntax      \| Description \| \| ———– \| ———– \| \| Header      \|
      Title       \| \| Paragraph   \| Text        \|


      <table><tbody><tr><th>head 1</th><th>head
      2</th></tr><tr><td>hi</td><td>hello moto</td></tr></tbody></table>


      okay.


      <table><tbody><tr><td>`</td><td>foo</td><td>bar</td><td>baz</td><td>&nbsp;</td><td>xyzzy</td><td>plugh</td><td>thud</td><td>`</td></tr></tbody></table>


      ` | foo   | bar   | baz  | | xyzzy | plugh | thud | `
  - _bookshop_name: design-system/section/full-bleed-photo
    src: /uploads/wvu-biology-rachel-morris-lab-sample-v2.jpg
    alt:
    caption:
    config:
      edit_mode_only: false
show_author_bios: true
type: photo-essay
uuid: 3157561f-d066-4064-a84d-0b46db7f4a91
metadata:
  type: Photo Essay
---
