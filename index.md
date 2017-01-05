---
title       : DDP - Assignment Week 3
subtitle    : Car Clustering
author      : FP
job         : wicht
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github:
  user: fpaster
  repo: CDD
---

## Introduction

Sometimes picking the right car is not as easy as it seems. There is always a tradeoff between horsepower (hp) and miles per gallon (mpg)

This app separates available cars into groups from economical to wasteful. The number of groups can automaticall be specified by the user.

---

## There are just so many different cars available



```r
print(p)
```

<img src="figure/unnamed-chunk-2-1.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />

---
    
## Cars Clustering is easy

Just specify the amount of clusters you want to divide all available cars and the plot will automatically colour the dots into their respective group.

For example put the slider to three to select three clusters:

![](slider_example.png)

---

## Voila

The cars are clustered into three clusters:

Thank you for your attention & have fun!
(somehow the image on this slide cannot be displayed on gh pages -.-)

![](selection_example.png)


