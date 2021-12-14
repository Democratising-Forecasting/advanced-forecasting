---
output: 
  md_document:
    preserve_yaml: true
    variant: gfm
layout: page
title: Lab 08
---

## Feature-based Time Series Forecasting

Please make sure to have the following packages installed:

```{r, comment=NA, messages=FALSE, warnings=FALSE}
library(tidyverse)
library(tsibble)
library(lubridate)
library(fable)
library(seer)
library(coronavirus)
library(M4comp)
```

## Question 1

This question is based on data available in the `coronavirus` package.

i) Extract confirmed cases corresponding to all countries.

ii) Convert all negative values to zero.

iii) Compute suitable features using the functionalities available in the `feast` package.

iv) Use an appropriate method to visualize feature-space corresponding to the time series of confirmed cases for all countries. (Help: Dimension reduction technique: PCA, t-SNE)


## Question 2

Train  a FFORMS meta-learner to forecast yearly series. Use yearly time series of M3 competition as your training set and yearly time series of M1 competition as your test set.




