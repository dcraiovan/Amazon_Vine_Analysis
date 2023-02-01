# Amazon_Vine_Analysis
## Overview 

The purpose of this analysis is to analyse the Vine program while performing ETL (Extract, Transform, Load) on a dataset from Amazon. I used US Apparel product reviews from Amazon. 

The analisis evaluates if it would be worth it to subscribe to a Vine program if we were to sell similar products through their platform. 

## Ressources
Datasets:
- US Apparel dataset
- Technologies used:

- Google Colab (to run PySpark)
- Jupyter Notebook
- AWS S3 and RDS
- PostgreSQL

## Results

### Perform ETL on Amazon Product Reviews
The first step was to extract the dataset from an AWS S3 using PySpark in order to transform it and load it to AWS again. I downloaded it as a jupyter notebook file, but it was originally created in Google Colab for PySpark to run. I divided the whole dataframe into 4 smaller dataframes for better analysis. These dataframes were then loaded to AWS RDS using a a connection from PySpark to PostgreSQL.

### Determine Bias of Vine Reviews
I worked with the last table called vine_table to perform the Vine program analysis to filter the best reviews, and see if there was biased for those with more 5-star reviews in the paid and incentivized (vine) program. The best reviews were those that were highly voted as helpful. 

## Summary
In my opinion there is no positivity bias for reviews in the Vine program. At first glance, it appeared that there would be bias; however after further analysis, it indicates that there are more non-members entering the reviews than Vine members. 

As a marketing strategy, we may want to reach out to Non-members to provide a membership on a trial period. We might want to more analysis that could analyze the number of years a member has been a Vine member. It is possible that they are satisfied with the service but feel that they do not need to offer a review. I would like to analyze the number of purchases a member has made or the amount of the purchase in a given year. We may need to reach out to the loyal customers for process improvement or incentive for a loyalty program.
