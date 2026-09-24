---
layout: liquid-table
title: "Ryan vs. Ryan"
subtitle: "A Liquid table built from YAML data."
permalink: /table-demo
reynolds:
  strengths:
  - good father
  - funny
  - dated alanis morissette
  weaknesses: 
  - singing
  - green lantern movie
  - tennis backhand 
gosling:
  strengths: 
  - builds houses
  - is a real boy
  - never dated alanis morissette
  weaknesses: 
  - micky mouse club
  - cries a lot
  - not ryan reynolds
---

![Side-by-side portraits of Ryan Reynolds and Ryan Gosling from the lab example]({{ '/img/ryan-v-ryan.jpg' | relative_url }})

### A playful example of structured content

This comparison retains the sample data supplied in the lab. The entries are deliberately humorous and should be read as demonstration content, not verified claims about either actor.

The table below is generated from four lists in this page's YAML front matter. The custom layout uses a Liquid loop for each list, producing one table entry for each item. Editing a list updates the rendered table without changing the layout itself.

### What the example demonstrates

Separating data from presentation reduces repeated markup and makes updates easier to review. That is useful when several pages need a consistent comparison format. The structure alone, however, does not make a comparison rigorous: a substantive evaluation would also need defensible criteria, reliable sources, and an explanation of how each judgment was made.

*Source: [DS4PS Barebones Jekyll table example](https://github.com/DS4PS/barebones-jekyll/blob/master/page2.md) and [Liquid layout](https://github.com/DS4PS/barebones-jekyll/blob/master/_layouts/liquid-table.html). Image reproduced from the same teaching example.*
