# Amazon_Vine_Analysis

### Programs and Data used for this analysis

Programs : AWS RDS database with tables in pgAdmin, Google Colab with Pyspark

Data : [Video Games Amazon](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)

## Overview of the analysis: 

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. I chose the video game datasets to analyze and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. I also used Google Colab with PySpark to determine if there is any bias toward favorable reviews from Vine members in my dataset. 

## Results: 

![This is an image](fivestar.png)

* Out of the total of 50,565 reviews, 94 of them were paid and 40,471 of them were unpaid.

* Out of those paid and unpaid reviews, 48 of them were five-star paid reviews and 15,663 were five-star unpaid reviews.

-----------------------------------------------------------------------------------------------------

![This is an image](percent.png)


* So calculating the results show that 51% of paid vine reviews were five-star and 38% were unpaid five star reviews. 

---------------------------------------------------------------------------------------------------

## Summary: 

According to the findings, vine users were rather biased as half of them had five-star ratings. Even though there were more non-vine users, 38% still had five-star reviews. It only goes to show that the majority of customers who are happy with their product will give it five stars. With this information, we may examine another data set to determine whether it is comparable to the video game set.
