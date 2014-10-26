---
title       : Pitching Metrics Calculator
subtitle    : 
author      : Brian Chan
job         : 
logo        : baseball.jpg
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## America's Love of Baseball and Statistics


Baseball is America's great pastime and at its heart, a very simple game.

Baseball's structured nature makes it a perfect application of statistics and associated metrics.

Stadiums, television broadcasts, and even fans in the stands are keeping track of every ball and strike; however, the more advanced metrics are always calculated by statisticians after the fact.

<b>What if you could track your pitcher's advance metrics, as you watch the game?</b>

--- 

## Features

Calculate:
- Innings Pitched
- Earned Run Average
- WHIP
- Power Finesse Ratio
- Quality Starts

<h3>WHIP Example:</h3>

```r
bb=4; hits=3; outs=27
whip <- function(bb,hits,outs) {(bb+hits)/(outs/3)}
whip(bb,hits,outs)
```

```
## [1] 0.7778
```

---

## The App

<img src="AppScreenshot.png" alt="Application Screenshot" align="middle">

---

## Thank you!

Give it a try!

https://brianychan.shinyapps.io/shiny/

---

