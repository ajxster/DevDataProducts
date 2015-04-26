---
title       : Body Mass Index
subtitle    : Developing Data Products
author      : AJ
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Background

The body mass index (BMI), or Quetelet index, is a value derived from the mass (weight) and height of an individual. The BMI is defined as the body mass divided by the square of the body height and is universally expressed in units of in units of kg/m2, resulting from weight in kilograms and height in metres.

Categories

BMI <18.5 : Underweight

BMI [18.5-25) : Optimal weight

BMI [25-30) : Overweight

BMI >=30 : Obese

--- .class #id 

## Shiny Web

<div style='text-align: center;'>
    <img height='420' src='shiny.png' />
</div>

https://ajxster.shinyapps.io/bmip/

--- .class #id 

## The Calculation

The BMI is an attempt to quantify the amount of soft tissue mass (muscle plus fat) in an individual, and then categorize that person as underweight, normal weight, overweight, or obese based on that value.

<div style='text-align: center;'>
    <img height='160' src='calc.png' />
</div>

Gender <- Female

Height <- 165

Weight <- 60

BMI (result) optimal weight

--- .class #id 


## The Code

The details for server.R

<div style='text-align: center;'>
    <img height='240' src='code.png' />
</div>




