# Amazon_Vine_Analysis

## Overview

The team has been tasked with another larger project to analyze Amazon video game reviews written by the members of the paid Amazon Vine program.  The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. The project deliverables are listed below.
- Perform ETL on Amazon Product Reviews
- Determine Bias of Vine Reviews
- A Written Report on the Analysis

## Resources
- [ETL Code](https://github.com/sbretag/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb)
- [Analysis Code](https://github.com/sbretag/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb)
- [Amazon Video Game Review Data Set](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)
- Software: Spark 3.1.2, AWS RDS Database, Pg Admin 4


## Results 

 - After applying relevancy filters for amazon video game reviews w/20+ votes and with a 50% or higher ratio of helpful votes, the following counts were calculated from the data frames
   - 40,565 reviews (filtered for relevancy) of which 40,471 (99.8%) were non vine reviews and 94 (0.2%) were vine reviews
   - Of the 40,565 reviews, 15,711 (38.7%) were 5 star reviews
   - Of the 15,711 5 star reviews, 15,663 (99.7%) were from non vine reviews and 94 (0.3%) were from vine reviews
   - Vine reviews were found to have a 5 star rating 51% of the time and non vine reviews were found to have a 5 star rating 39% of the time
 
## Summary


