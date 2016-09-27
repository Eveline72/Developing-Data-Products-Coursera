---
title       : Choose a car with the least mpg
subtitle    : 
author      : Eveline
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Choose a car with the least mpg

For this assignment, I created a shiny-app. 
In the app, you can build a lineair model of two variables that predicts the mpg. You can choose each of the variables yourself, from a given dataset. You can also choose the color of the line in the chart.

The result of the app is a summary of the two variables and a chart of the lineair model for one of them.

--- .class #id 

## The data

The data I used is available in the standard R package. It is the "mtcars"-dataset.

These are the available variables:


```r
data(mtcars)
names(mtcars)
```

```
##  [1] "mpg"  "cyl"  "disp" "hp"   "drat" "wt"   "qsec" "vs"   "am"   "gear"
## [11] "carb"
```

And the number of observations is:

```r
dim(mtcars)[1]
```

```
## [1] 32
```

--- .class #id 

## An example plot

This is an example output of my app, if you would use disp and cyl as independent variables.

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png)

--- .class #id 
      
## The app

You can find my app on shinyapps.io [here](https://eveline.shinyapps.io/Carstop/)

I hope you like it!

Kind regards,
Eveline
