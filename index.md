---
title       : 
subtitle    : 
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Plot 1

title: "Habits"
output:
  slidy_presentation:
    fig_width: 7
    fig_height: 6
    fig_caption: true

--- .class #id 

## Here’s some code

```r
dim(iris)
```
---

## Here’s a plot

```r
[image] hist(iris[,2])
```
---


