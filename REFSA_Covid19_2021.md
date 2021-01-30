---
title: "REFSA COVID-19 Response—MCO 2.0"
author: "REFSA Research Team"
date: "2021-01-30"
output: 
  html_document: 
    keep_md: true
---




## Objective

Malaysia is currently struggling to deal with the third wave of the Covid-19 pandemic. This analysis aims to highlight a few data points that illuminate the response so far of the government, and where additional investment may be required. 

 1. Test positivity rate, and the need to perform more testing
 2. Changes in mobility, related to the positivity rate
 
## Test positivity rate

The test positivity rate is still quite elevated in Malaysia, above the minimum threshold recommended by the WHO (5%), and especially high compared to a successful country in managing Covid-19, South Korea. The following charts depict the evolution of number of new cases, number of tests, and positivity rate. All data is 7-day smoothed (rolling average); people tested are per 1,000 population; new daily cases are per million population.

Source: Our World In Data. 



![](REFSA_Covid19_2021_files/figure-html/covid-plot-1.png)<!-- -->

## Mobility
Analysis of mobility is based on Google's data for Malaysia. 
The charts below show the percent change compared to a baseline. The baseline is the median number of daily routing requests between early January to early February 2020. 

![](REFSA_Covid19_2021_files/figure-html/mobility-1.png)<!-- -->

The effect of the resumption of interstate travel on 2020-12-07 is well visible in the "Transit Stations" category. From that day there is a clear uptick in the number of requests for transit stations. Looking at that chart in isolation: 

![](REFSA_Covid19_2021_files/figure-html/mobility-transit-1.png)<!-- -->

In order to see the trend better, we also compute a 7-day rolling average for the same data, across the whole data set. 

![](REFSA_Covid19_2021_files/figure-html/mobility-7da-1.png)<!-- -->

## Test positivity rate vs mobility
The chart below shows the evolution of the test positivity rate and the mobility data related to transit stations. 

![](REFSA_Covid19_2021_files/figure-html/posrate-mobility-1.png)<!-- -->
