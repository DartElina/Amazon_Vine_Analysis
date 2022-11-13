# Amazon Vine Analysis

## Overview of the analysis: 
We analyzed 43,574 amazon reviews to identify if there is a benefit to pay for Vine reviews. We filtered these reviews for vine and non vine members. We filtered each for the number of 5-Star Reviews as well. We hope to identify if there is any bias in the Vine reviews. 

We used AWS, PgAdmin, Pyspark, and Google Console for this analysis. 
___ 
### Results: 
- How many Vine reviews and non-Vine reviews were there?
  - There a total of 107 Vine Reviews. 
  - There a total of 39,869 Non-Vine Reviews. 
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - Of the 107 Vine reviews, 56 were 5-Star reviews. 
  - Of the 39,869 Non-Vine Reviews, 21005 were 5-Star reviews. 
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - Percentage of Vine reviews with 5-Stars was 52.34%
  - Percentage of Non-Vine reviews with 5-Stars was 52.69%
___ 
### Summary: 

The proportion of Vine reviews with 5-Stars is very similar to the proportion if 5-Star review among Non-Vine reviews. This may indicate that there is no bias in the reviews of vine members. 

I recommend applying this analysis to other segments to find if these results are consistent. 40,000 plus reviewers is a large pool to start with, however the vine pool is very small, and hard to prove our results are consistent, or reliable. Comapring more vine reviews will make for a stronger test. 
___
### Images of code and results 
Customer Table in PgAdmin:

![customer table](https://github.com/DartElina/Amazon_Vine_Analysis/blob/f4d773a826994f3c0baf21f8b5f46896166cccba/images/customers_table.png)

Products Table in PgAdmin:

![product table](https://github.com/DartElina/Amazon_Vine_Analysis/blob/f4d773a826994f3c0baf21f8b5f46896166cccba/images/products_table.png)

Review ID Table in PgAdmin:

![review table](https://github.com/DartElina/Amazon_Vine_Analysis/blob/f4d773a826994f3c0baf21f8b5f46896166cccba/images/review_id_table.png)

Vine Table in PgAdmin:

![vine table](https://github.com/DartElina/Amazon_Vine_Analysis/blob/f4d773a826994f3c0baf21f8b5f46896166cccba/images/vine_table.png)

Pyspark Calculations for total, vine, non-vine, and percentage calculations:

![percentage calculations](https://github.com/DartElina/Amazon_Vine_Analysis/blob/f4d773a826994f3c0baf21f8b5f46896166cccba/images/vine_reviews_percentage.png)
