---
date: "2021-01-01"
excerpt: Not used.
subtitle: A critical look at the history of IR and of IR as a discipline
title: International Relations in Theory and History
weight: 2
---


intro blurb

## Pre-requisites

syllabus

```
install.packages("blogdoown")
```

Restart your R session. If you use RStudio, use the menu item *Session > Restart R* or the associated keyboard shortcut:

+ <kbd>Ctrl + Shift + F10</kbd> (Windows and Linux) or
+ <kbd>Command + Shift + F10<kbd> (Mac OS). 

```
packageVersion("blogdown")
[1] ‘1.0’
```

## Create GitHub repo

Online.

## Clone GitHub repo

```
usethis::create_from_github("https://github.com/apreshill/global-blogdown.git")
```

:sparkles: Commit & Push! :sparkles:

You should be committing these files:

+ `*.Rproj`

+ `.gitignore`

## Create a new blogdown site

We'll be using a new Hugo theme that I made for us! 

Inside your current blogdown project, use the R console:

```
library(blogdown)
```

Let's start with making the website with the theme: 

```
new_site(dir = ".", theme = "apreshill/blogophonic")
```

## Configure your site

The first stop on this tour of your site is the `config.yaml` file.


