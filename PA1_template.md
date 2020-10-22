---
title: "Reproducible Research: Peer Assessment 1"
output: 
  html_document:
    keep_md: true
---

<p>&nbsp;</p> 

This assignment is part of the Coursera-Johns Hopkins University course **Reproducible Research.** You can find more information about it in the `README.md` document.

<p>&nbsp;</p>

## Loading and preprocessing the data

<p>&nbsp;</p>

First we need to prepare the package we will use:

```r
library(dplyr)
library(ggplot2)
```

<p>&nbsp;</p>

The GitHub repository contains the dataset, so we do not have to download the data.
We just need to unzip it:


```r
if(!file.exists("activity.csv")) {
      unzip("activity.zip")
}

activity <- read.csv("activity.csv")
```

<p>&nbsp;</p>

Explore the data


```r
head(activity, n = 10)
```

```
##    steps       date interval
## 1     NA 2012-10-01        0
## 2     NA 2012-10-01        5
## 3     NA 2012-10-01       10
## 4     NA 2012-10-01       15
## 5     NA 2012-10-01       20
## 6     NA 2012-10-01       25
## 7     NA 2012-10-01       30
## 8     NA 2012-10-01       35
## 9     NA 2012-10-01       40
## 10    NA 2012-10-01       45
```

<p>&nbsp;</p>

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
