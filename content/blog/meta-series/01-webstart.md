---
date: "2021-12-15"
draft: false
excerpt: Text is not used.
subtitle: ""
title: Building a new website
weight: 1
---

## First steps

I have long been a fan of static websites, which are portable, compact, and do not require a lot of server overhead. Since it was time to update my woefully inadequate website, I did some research into different static website options.

[Hugo](https://gohugo.io/) is a powerful and widely-used framework for building static websites and offers a number of attractive themes. 

[Blogdown](https://bookdown.org/yihui/blogdown/) makes it easy to edit a website's files within [RStudio](https://www.rstudio.com).

I settled on [Hugo Apéro](https://hugo-apero-docs.netlify.app/) an excellent theme developed by [Alison Hill](https://www.apreshill.com), a data scientist working at RStudio.

## Initial build

The initial build was straight-forward, following the [instructions](https://hugo-apero-docs.netlify.app/start/) at the Hugo Apéro site. 

---

## Configuration

The Apéro theme is endlessly customizeable. My first change was to change the default font to Baskerville, and to reduce the size of the standard header text, so that my name would not spill onto a second line on the landing page for normal screen widths. This change was made in the file `index.html` inside `hugo-apero/layouts`.

Additional changes will be described in additional posts in this series.