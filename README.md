# Amazon_Vine_Analysis

## Overview of the analysis

#### Pupose
- Analyze Amazon reviews written by members of the paid Amazon Vine program
- Using product review dataset, perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin
- Determine if there is any bias toward favorable reviews from Vine members in your dataset

#### Background
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Results
Using bulleted lists and images of DataFrames as support, address the following questions:

- How many Vine reviews and non-Vine reviews were there?

  Vine program reviews: **47** 
  
  Non-Vine program reviews: **8362**
- How many Vine reviews were 5 stars?

  Vine program 5 star reviews: **15** 
- How many non-Vine reviews were 5 stars?

  Non-Vine program 5 star reviews: **4332**
- What percentage of Vine reviews were 5 stars?

  Vine program 5 star reviews %: **32%**
- What percentage of non-Vine reviews were 5 stars?

  Non-Vine program 5 star reviews %: **52%**
  
## Summary
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
