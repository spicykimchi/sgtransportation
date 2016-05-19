---
title       : Developing Data Products Course Project
subtitle    : SpicyKimchi
author      : May 15 2016
job         : May 15 2016
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github:
  user:spicykimchi
  repo:sgtransportationslidify 
---

## Introduction

Assignment for Developing Data Products Course Project: Shiny Application and Reproducible Pitch.
The application should use shiny and allow user to enter data. The chart or data should show the filtered data according to user's inpput.


---

## Project

Analyse the transportation system in singapore for the past 10 years.

1. Data Source
+ https://data.gov.sg/dataset/public-transport-utilisation-average-public-transport-ridership

2. Filtering Criteria
+ Transport Type - Dropdown
+ Year - Slider

3. Application URL
+ https://spicykimchi.shinyapps.io/DSMod9Wk1PJ/


---

## Code

1. Plot Chart  
+ Use renderPlot, plot and lines() to plot a line chart for each transport type 
  
2. Show Data in table
+ Use sqldf to select data according to the relevant input passed to the shiny server
+ Use renderTable
  
---

##Screenshot

![200px](Output1.png) 

---
