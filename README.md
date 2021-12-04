# Amazon_Vine_Analysis

## Overview of the analysis

#### Purpose
- Analyze Amazon reviews written by members of the paid Amazon Vine program
- Using product review dataset, perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin
- Determine if there is any bias toward favorable reviews from Vine members in your dataset

#### Background
Big market is a startup that helps businesses optimize their marketing efforts. $ellby a retail company and Big market's client is is about to release a large catalog of products on a leading retail website. They want to know how the reviews of their products compare to the reviews of similar products sold by their competitors. They are also interested in enrolling in a program that gives out free products to select reviewers but they want to know if its worth the cost.
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Resources
- Pyspark
- AWS-RDS, AWS-S3
- Postgres

## Results
Using bulleted lists and images of DataFrames as support, address the following questions:

- How many Vine reviews and non-Vine reviews were there?

 Vine program reviews: **47** 
  
  ![Vine program reviews](https://github.com/Sheetaltkr/Amazon_Vine_Analysis/blob/main/Resources/total_paid_reviews.png)
  
  Non-Vine program reviews: **8362**
 
 - How many Vine reviews were 5 stars?

 ![Non_Vine program reviews](https://github.com/Sheetaltkr/Amazon_Vine_Analysis/blob/main/Resources/total_unpaid_reviews.png)
 
  Vine program 5 star reviews: **15**
  
- How many non-Vine reviews were 5 stars?

 ![Vine program 5_star_reviews](https://github.com/Sheetaltkr/Amazon_Vine_Analysis/blob/main/Resources/total_paid_reviews_5_star.png)
 
  Non-Vine program 5 star reviews: **4332**
  
 ![Non_Vine program 5_star_reviews](https://github.com/Sheetaltkr/Amazon_Vine_Analysis/blob/main/Resources/total_unpaid_reviews_5_star.png)
  
- What percentage of Vine reviews were 5 stars?

  Vine program 5 star reviews %: **32%**
  
 ![Vine program 5_star_reviews%](https://github.com/Sheetaltkr/Amazon_Vine_Analysis/blob/main/Resources/paid_reviews_5_star_prcnt.png)

- What percentage of non-Vine reviews were 5 stars?

  Non-Vine program 5 star reviews %: **52%**

![Non_Vine program 5_star_reviews%](https://github.com/Sheetaltkr/Amazon_Vine_Analysis/blob/main/Resources/unpaid_reviews_5_star_prcnt.png)
  
## Summary
 
-  There is no bias observed for reviews for product "watches"
-  As per the results, 
   - The total paid reviews are very less compared to unpaid reviews
   - The total paid 5 star reviews are very less compared to unpaid  5 star reviews
   - The percentage of paid 5 star reviews of total paid reviews is 32% and the percentage of unpaid 5 star reviews of total unpaid reviews is 52%
 
 - The above results prove that the possibility of paid reviews to influence the positive outcome of the reviews is very low.

#### Additional Analysis
 - TF-IDF measure can be used for all the words part of the Vine and Non-Vine reviews.
   Term frequency (TF) measures the frequency of a word occurring in a document, and inverse document frequency (IDF)
 - We can compare the TF-IDF values of positive review words for paid and unpaid reviews. If the values are close, it proves that the Vine reviews are unbiased.




