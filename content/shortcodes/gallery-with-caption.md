---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

# Section title
title: Gallery with Caption

# Section subtitle
subtitle:

# Section design
design:
  # Use a 1-column layout
  columns: "1"

gallery_item:
    - album: code
      image: cpp.png
      caption: "**C++**"
    - album: code
      image: css.png
      caption: "**CSS**"
    - album: code
      image: html.png
      caption: "**HTML**"
    - album: code
      image: java.png
      caption: "**Java**"
    - album: code
      image: js.png
      caption: "**Javascript**"
    - album: code
      image: python.png
      caption: "**Python**"
---

{{< gallery-with-caption album="code" process="fit" fig_style="padding: 0px 20px 0px 20px" img_style="max-height:200px">}}