---
title       : Coursera Data Products
subtitle    : Parameters of Black Cherry Trees
author      : Meir Adest
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Application Concept

* R contains a dataset of some of the parameters of black cherry trees
* These parameters include:
  + Trunk Girth
  + Tree Height
  + Tree Volume
* The Shiny application allows to plot each of the above variables in comparison to any other

--- .class #id 

## Usage Instructions

* select the wanted variable for the X axis
* select the wanted variable for the Y axis
* Voila! Observe the graph as requested

--- .class #id 

## Example 1

An example plot of Girth as function of Volume.


```r
plot(trees$Volume, trees$Girth, xlab = "Volume", ylab = "Girth", main = "Black Cherry Trees")
```

<img src="assets/fig/unnamed-chunk-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />

--- .class #id 

## Example 2

An example plot of Height as function of Girth.


```r
plot(trees$Girth, trees$Height, xlab = "Girth", ylab = "Height", main = "Black Cherry Trees")
```

<img src="assets/fig/unnamed-chunk-2.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />

