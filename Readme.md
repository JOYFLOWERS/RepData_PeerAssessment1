## Introduction

This is Course Project 1 from the Reproducible Research Course in the Data Science Specialization from Coursera/Johns Hopkins University.

In this assignment, activity (specifically number of steps) from a personal monitoring device such as Fitbit or Jawbone, is analyzed.. This device recorded the number of one individual's steps in 5-minute increments for two months over October and November, 2012.

## Input
The file contains three variables and a total of 17,568 observations. These variables are:<ol>
<li><b>steps</b>: Number of steps taken in a 5-minute interval (missing values are coded as NA)
<li><b>date</b>: The date on which the measurement was taken in YYYY-MM-DD format
<li><b>interval</b>: Identifier for the 5-minute interval in which measurement was taken </ol>

## Output
There are three documents created: <ol>
<li><b>PA1_template.Rmd</b> This is the RMarkdown script
<li><b>PA1_template.html</b> This is the output produced by the RMarkdown code
<li><b>PA1_template.md</b> This is the intermediary markdown file. This file does not maintain the exact formatting of the html version but is close. For example, it treat R code comments as headers. </ol>

## Results and Calculations

The PA1_template.html document shows total steps taken over the two month period and breaks them down total steps taken per date. It creates a histogram of the total steps (which also counts missing values). It calculates the mean and median (with and without missing values). It sums the number of missing values. It then plots the average steps per interval and calculates at which interval the maximum average steps were taken. It takes these averages and imputes the missing values with the average (mean) per interval. A new histogram with imputed values is then plotted. Lastly, it compares and plots weekday versus weekend steps per interval. Results are detailed in the html document. Some observations are that the histogram with imputed values reflects a greatly diminished number of days where steps taken are under 1000. Also, while weekend and weekday steps are similar in number, it is clear that the weekday steps are mostly completed from 5 to 10 AM whereas the weekend steps are accomplished more consistently throughout the day.

