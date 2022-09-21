# Amazon Vine Analysis
## Overview

Working for the startup BigMarket, we are the first data expert on the team that focuses on helping businesses optimize their market efforts. Our next big project for our current client, SellBy, in sight is to analyze reviews written by members of the paid Amazon Vine program. This program is a service that allows its manufacturers and sellers to receive reviews of their products. For example, firms like SellBy will pay a fee to Amazon and send Amazon Vine members their own products, in which these individuals are then required to produce and publish a review. 

While Amazon Reviews has an abundant amount of review categories to choose from, for our analysis, we will be focusing on the billion dollar industry of Beauty products and its dataset. Utilizing tools such as PySpark, we will perform the ETL process to extract the dataset, transform the data, and connect the data to an AWS RDS instance, and then load the transformed dataset into pgAdmin. 

Afterwards, we will investigate if any bias exists toward favorable reviews from Vine members on the basis of whether they were paid or unpaid. This will aid in determining if having a paid Vine review will make a difference in the percentage of 5-star reviews. 

## Objectives: 
- Explain how MapReduce processes data.
- Define Spark and explain how it processes data.
- Describe how NLP collects and analyzes text data.
- Explain how to use AWS Simple Storage Service (S3) and relational databases for basic cloud storage.
- Complete an analysis of an Amazon customer review.

## Tools Used:
- AWS
- pgAdmin
- PySpark
- Google Colaboratory
- SQL
- Pandas
- Jupyter Notebook

## Dataset:
Amazon Beauty Review dataset: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Beauty_v1_00.tsv.gz


