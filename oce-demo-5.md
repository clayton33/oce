---
permalink: oce-demo-5.html
title: oce demo 5
layout: default
---

```r
library(oce)
library(oce)
par(mar=rep(0.5, 4))
data(endeavour, package="ocedata")
data(coastlineWorld, package="oce")
mapPlot(coastlineWorld, type='l', fill='gray')
mapPoints(endeavour$longitude, endeavour$latitude, pch=20, col='red')
```
