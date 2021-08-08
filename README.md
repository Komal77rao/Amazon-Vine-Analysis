# Amazon_Vine_Analysis

## Overview of the analysis:
In this analysis, I used the amazon reviews dataset from the S3 bucket regarding women's apparel. The analysis was performed using Pyspark and the Relational Database (RDS) from Amazon web Services (AWS). The goal of this analysis was to determine if there is favorable review bias from the Vine members of our data set.


## Results:
#### How many Vine reviews and non-Vine reviews were there?
- There were a total of 33 vine reviews in our dataset and 45388 non-vine reviews in the complete dataset.


#### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- In this data, there were 15 5-star vine reviews and 23733 non-vine 5 star reviews.


#### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- percentage of 5 star Vine reviews - 52.9%
- percentage of 5 star non-vine reviews - 49%

![Picture1](https://user-images.githubusercontent.com/79213116/128646967-04b2e025-6459-4155-b4d0-8c4f49f097d8.png)

## Summary:
There is no positivity bias for reviews in the Vine program as the total vine reviews for 5 star ratings were 15 compared to 23733 non-vine 5 star reviews.
