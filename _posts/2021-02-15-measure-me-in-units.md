---
layout: post
title: Measure me in Units
date: 2021-02-15T17:25:29.858Z
header_feature_image: ../uploads/patricia-serna-zpz9vqqdnba-unsplash.jpg
title_color: "#ffffff"
caption: Photo by patricia serna on Unsplash
comments: false
tags:
  - web
  - CSS
  - HTML
---
What units of measure can we use in our CSS to provide such things as font size, margins, padding and widths. There are many, including px, em, rem, vh, vw and even %. What does it all mean and how should we use these units?

## The structure of an \`HTML\` page; the hierarchy of the elements.

We should just remind ourselves about this, because some of these important units are relative – relative to the settings on their parent element.

![Here we see the structure of the web page](../uploads/html-dom.png "Web page structure")

We have `<html>` as the root element with `<body>`as the main content. Within this we will have a number of block level elements such as headings, paragraphs, sections, navs and articles.