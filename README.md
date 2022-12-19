# Amazon_Vine_Analysis

## Overview of the analysis
Extract one of the 50 datasets, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Furthermore using PySpark determine if there is any bias toward favorable reviews from Vine members in your dataset and present a summary to the SellBy stakeholders.

## Results
1) There were 613 paid vine reviews, and 64968 unpaid vine reviews.
2) There were 222 "5 stars" from paid Vine reviews, and 30543 "5 stars" for non-Vine reviews.
3) 36.21% of Vine reviews were 5 stars. 47.01% of non-Vine reviews were 5 stars.

![vine reviews](https://user-images.githubusercontent.com/111706055/208351761-66aee671-5e14-4378-8941-868d83e2f23f.png)

## Summary 
There no positivity bias for reviews in the Vine program since only 36.21% of vine reviews were 5 stars. This applies for non vine review as well with only 47.01% with a review of 5 stars.
We can analyse all the star reviews and find an average rating for vine and non vine users to dive further into the analysis.
