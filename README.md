# Amazon_Vine_Analysis

## Overview of the analysis

#### Pupose
- Analyze Amazon reviews written by members of the paid Amazon Vine program
- Using product review dataset, perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin
- Determine if there is any bias toward favorable reviews from Vine members in your dataset

#### Background
Big market is a startup that helps businesses optimize their marketing efforts. $ellby a retail company and Big market's client is is about to release a large catalog of products on a leading retail website. They want to know how the reviews of their products compare to the reviews of similar products sold by their competitors. They are also interested in enrolling in a program that gives out free products to select reviewers but they want to know if its worth the cost.
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

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
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
