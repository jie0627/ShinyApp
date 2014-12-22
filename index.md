---
title       : Shiny Application
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

## Introduction

This shiny application is based on 673 businesses in downtown New Orleans
(in 'Katrina.csv'). It allows the user explore the following features present in the dataset: log medinc, and flood depth.

1. The user has the option to choose between log medinc and flood depth.
2. Plot a histogram of the feature chosen by the user.
3. The user has the ability to configure the number of bins in the histogram.

--- .class #id 

## User's Option

The user has two options to choose:
1. log medinc 
2. flood depth

--- .class #id 

## Histogram

This App shows histogram of log medinc and flood depth, which is the feature chosen by the user.

--- .class #id 


## Configuring number

The user could configure the number of bins in the histogram by changing the mumber on the radio button.





