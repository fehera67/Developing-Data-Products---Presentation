---
title: "Developing Data Products Presentation"
author: "Andras Feher"
highlighter: prettify
output:
  html_document:
    number_sections: yes
    toc: yes
job: Pitch Presentation
knit: slidify::knit2slides
mode: selfcontained
hitheme: tomorrow
subtitle: MPG - Manual vs. Automatic Transmission
framework: io2012
widgets: bootstrap
---

## Developing Data Products Project Descrition

- The application predicts the mpg of various cars using the mtcars data set.
- The application is available on shinyapps.io
- Application url:  http://fehera67.shinyapps.io/shapp
- github url: https://github.com/fehera67/Developing-Data-Products---Shiny-Application/tree/master


---

## The mtcars data set

### Motor Trend Car Magazine Road Tests Data

- Data is from the 1974 Motor Trend US magazine containing MPG and other characheristics for 32 automobiles (1973–74 models).

### Source

- Henderson and Velleman (1981), Building multiple regression models interactively. Biometrics, 37, 391–411.


```
##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
```

---

## mtcars dataset fields

### Fields in the data set:

- mpg  : Miles/(US) gallon
- cyl  : Number of cylinders
- disp : Displacement (cu.in.)
- hp   : Gross horsepower
- drat : Rear axle ratio
- wt   : Weight (lb/1000)
- qsec : 1/4 mile time
- vs   : V/S
- am   : Transmission (0 = automatic, 1 = manual)
- gear : Number of forward gears
- carb : Number of carburators

---

## Shiny application description

- The application fits a linear model with the selected predictor and displays the summary along with the plot including the abline.




