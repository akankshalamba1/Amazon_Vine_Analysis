# Amazon_Vine_Analysis
Analysis using AWS database

## Overview of the analysis:

In this analysis is based on the Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. For this analysis we had access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. 

#### Tools used for the analysis:
Following are the tools used for the analysis:
- Google colab 
- AWS: Relational Database Service
- PGAdmin4
- Pyspark
- Postgres

#### Analysis process:
For this analysis we will be using Personal care dataset
- Using PySpark to perform the ETL process to extract the dataset, transform the data, connect to AWS RDS instance, and load the transformed data into pgAdmin. 
- Using PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.



## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

### How many Vine reviews and non-Vine reviews were there?

**Total Vine review:** There are 3 vine reviews where vine = 'Y'

![vine_Y](https://user-images.githubusercontent.com/111251560/208995301-c5d196f2-90c4-4374-b564-f40b4dd6fda9.png)

**Total non-vine review:** There are 3094 non-vine reviews where vine = 'N'

![vine_N](https://user-images.githubusercontent.com/111251560/208997094-3f43d5eb-7fe2-42c1-b1a6-2229b1a3aa78.png)


### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?


## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
