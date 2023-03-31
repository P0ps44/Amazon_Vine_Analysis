# Amazon_Vine_Analysis

### Programs and Data used for this analysis

Programs : AWS RDS database with tables in pgAdmin, Google Colab with Pyspark

Data : [Video Games Amazon](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)

## Overview of the analysis: 

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. I chose the video game datasets to analize and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. I also used Google Colab with PySpark to determine if there is any bias toward favorable reviews from Vine members in my dataset. 

## Results: 

![This is an image](fivestar.png)

How many Vine reviews and non-Vine reviews were there?

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?


![This is an image](percent.png)

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?



## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
