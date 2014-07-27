---
title       : BMI calculator
subtitle    : coursera project
author      : vackerp
job         : data
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The app

This very basic shiny app is intended for the Coursera Course 'Developing Data Products'. It's a very basis BMI-calculator. [The app is hosted on shinyapps.io](http://vackerp.shinyapps.io/Documents). 

It need 2 parameters: The height (in meters en centimeters (example: 1.78) and the weight (in kg (example: 75))

Output: the MBI-index.
Calculation:

```r
height = 1.78
weight = 75
weight / height^2
```
```r
## [1] 23.67
```
 

--- 
## The Body Mass Index

### What's a BMI?

The body mass index (BMI), or Quetelet index, is a measure of relative weight based on an individual's mass and height.
Devised between 1830 and 1850 by the Belgian polymath Adolphe Quetelet during the course of developing 'social physics', it is defined as the individual's body mass divided by the square of their height - with the value universally being given in units of kg/m2.

### What does the BMI tell me?

A frequent use of the BMI is to assess how much an individual's body weight departs from what is normal or desirable for a person of his or her height. The weight excess or deficiency may, in part, be accounted for by body fat (adipose tissue) although other factors such as muscularity also affect BMI significantly (see discussion below and overweight). The WHO regards a BMI of less than 18.5 as underweight and may indicate malnutrition, an eating disorder, or other health problems, while a BMI greater than 25 is considered overweight and above 30 is considered obese.  <small>[Body mass index on Wikipedia](https://en.wikipedia.org/wiki/Body_mass_index)</small>


--- .class #id 

## How to use the app
1. [The app is hosted on shinyapps.io](http://vackerp.shinyapps.io/Documents)
2. Input: your weight (in kg)
3. Input: your height (in meters and )
4. You will see the BMI-index with a little bit of interpretation


---
## Body mass index chart


[Body mass index chart (Wikipedia)](https://upload.wikimedia.org/wikipedia/commons/e/e9/Body_mass_index_chart.svg) 
