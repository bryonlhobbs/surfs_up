# surfs_up

## Overview
In this challenge, I was asked to pull only June & December temperature data to determine if the surf and ice cream shop was sustainable year round.  Once I had the data, I needed to convert it to a list, then a DataFrame and get summary statistics to show viability.

## Results
  - The first difference between the two months is the lowest temperature.  In December, the lowest temperature was 56 degrees, whereas in June the lowest temperature was 64.  

  - Another difference is that the standard deviation for December is higher, suggesting more variance in the data.

  - The final difference is that the mean for June is almost 4 degrees higher.  Rounding to the nearest whole number, June has a mean of 75 degrees and December has a mean of 71 degrees.  Similariliy, the median for each month matches the mean.

Below are the summary statistics from both June and December.

<img width="155" alt="June_temperature_summary" src="https://user-images.githubusercontent.com/99457275/166123446-4f1c4523-7644-4062-b2e4-49e4740f90be.png">

<img width="173" alt="December_temperature_summary" src="https://user-images.githubusercontent.com/99457275/166123448-4137ca59-9f79-4f9d-9a1c-7b1a58050e9b.png">


## Summary
Upon analyzing the temperature data, it looks like opening the shop is a safe bet on the basis of temperature.  Other queries that may assist our planning include a query on precipitation for both months, as no one likes eating ice cream in the rain, and querying only the tempurature data from the station closest to the planned location of the shop in order to fine tune our analysis.
