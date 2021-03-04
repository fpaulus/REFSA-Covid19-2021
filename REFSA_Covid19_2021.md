---
title: "REFSA COVID-19 Response—MCO 2.0"
author: "REFSA Research Team"
date: "2021-03-05"
output: 
  html_document: 
    keep_md: true
fig.width: 6
fig.asp: 0.618
---





This tracker brings together a number of oft-referred to statistics to monitor the evolution of the Covid-19 pandemic in Malaysia, and highlight some interesting data points. As of now, the following data is included: 

 1. Daily count of tests, cases and test positivity rate
 2. Mobility data, based on Google's Covid-19 location data
 
## Tests, cases and positivity rate

Source: Our World In Data. 



### Evolution of testing 

![](REFSA_Covid19_2021_files/figure-html/covid-daily-tests-1.png)<!-- -->

### Evolution of daily cases

![](REFSA_Covid19_2021_files/figure-html/covid-daily-cases-1.png)<!-- -->

### Evolution of test positivity rate

This rate shows the short-term positivity rate of tests. 

![](REFSA_Covid19_2021_files/figure-html/covid-posrate-1.png)<!-- -->

## Mobility

Analysis of mobility is based on Google's data for Malaysia. 
The charts below show the percent change compared to a baseline. The baseline is the median number of daily routing requests between early January to early February 2020. 



### Change from baseline across categories

This chart shows the change in destinations relative to a pre-pandemic baseline, smoothed using a 7-day rolling average. Each time movement restrictions are announced, there is a noticeable drop in retail and recreation destinations as well as transit stations. 

![](REFSA_Covid19_2021_files/figure-html/mobi-plot-all-1.png)<!-- -->

The effect of the resumption of interstate travel on 2020-12-07 is well visible in the "Transit Stations" category. From that day there is a clear uptick in the number of requests for transit stations. Looking at that chart in isolation: 

![](REFSA_Covid19_2021_files/figure-html/mobility-transit-1.png)<!-- -->

For further analysis, we could look to include economic data (high frequency indicators would be best), and relate that to the evolution of the pandemic and the mobility data. 

