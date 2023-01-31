# Amazon_Vine_Analysis
## Overview 

The purpose of this analysis is to analyse the Vine program while performing ETL (Extract, Transform, Load) on a dataset from Amazon.

## Results

Deliverables
Deliverable 1: Perform ETL on Amazon Product Reviews
Using your knowledge of the cloud ETL process, you’ll create an AWS RDS database with tables in pgAdmin, pick a dataset from the Amazon Review datasets (Links to an external site.), and extract the dataset into a DataFrame. You'll transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, you'll upload the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded.


Deliverable 2: Determine Bias of Vine Reviews
Using either PySpark, Pandas, or SQL, follow the instructions below to complete Deliverable 2.

Filter the data and create a new DataFrame or table to retrieve all the rows where the total_votes count is equal to or greater than 20 to pick reviews that are more likely to be helpful and to avoid having division by zero errors later o


There is a bulleted list that addresses the three questions for unpaid and paid program reviews (7 pt)

## Summary

The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)

In my opinion there is no positivity bias for reviews in the Vine program. At first glance, it appeared that there would be bias; however after further analysis, it indicates that there are more non-members entering the reviews than Vine members. As a marketing strategy, we may want to know why don't more Vine members provide a review and how to increase the 5-star rating. We may want to provide incentives for the Vine members to provide more reviews and increase ratings. Or reach out to Non-members to provide a membership on a trial period. Then, provide one additional analysis that you could do with the dataset to support your statement, I think I would like to analyze the number of years a member has been a Vine member. It is possible that they are satisfied with the service but feel that they do not need to offer a review. I would like to analyze the number of purchases a member has made or the amount of the purchase in a given year. We may need to reach out to the loyal customers for process improvement or incentive for a loyalty program.

For this assignment I ended up doing SQL and Pyspark due to the percentage calculation, so that is why there are SQL tables and screenshots.
