![amazon vine.png](https://github.com/smj452/Amazon_Vine_Analysis/blob/main/Resources/amazon%20vine.png)

# Amazon Vine Program Analysis

## Project Overview

The Amazon Vine Program is a service that allows manufacturers and publishers to receive reviews for their products. The purpose of this analysis is to study one of Amazon's order category dataset from the Amazon Vine Program and use PySpark to perform the ETL process to an AWS RDS instance, and then load the transformed data into pgAdmin. The data is then used to determine if there is any bias toward favourable reviews from Vine members when compared to Non-Vine member reviews. Here I have picked up the Home Entertainment category dataset for my analysis.

## Results

**Vine Summary Results**
- There were 261 Vine reviews and 24,040 non-Vine reviews.
- 106 Vine reviews were 5 stars and 10,899 non-Vine reviews were 5 stars.
- 41% of Vine reviews were 5 stars and 45% of non-Vine reviews were 5 stars.

![Vine_Summary.png](https://github.com/smj452/Amazon_Vine_Analysis/blob/main/Resources/Vine_Summary.png)

## Summary 

There was no major bias for reviews in the Vine program. The percentage of Non-Vine 5 stars reviews was 4% more than Vine 5 stars reviews.

**Additional analysis that could be done with the dataset to support the statement**

- Calculate the average customer reviews categorized by  1, 2, 3, and 4 star reviews for each Vine and Non-Vine reviews.
- Conduct further analysis by analysing other vine program datasets so that the conclusion made is more accurate and precise.
