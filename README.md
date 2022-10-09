# Amazon_Vine_Analysis

## Overview

This analysis focuses on analyzing the Amazon Vine program to see whether there are any bias of reviews based on paid/unpaid members. Focusing on a specific product's dataset, we use:

- Google Colab Notebook
- Python
- PySpark 
- AWS / S3
- ETL using PySpark
- SQL + PgAdmin

## Results

#### Vine vs Non-Vine Reviews

22 paid and 26924 unpaid reviews were present, to a total of 26946 total reviews.

#### 5 - Stars?

13 paid 5-star reviews and 12485 unpaid 5-star reviews were present, to a total of 14452 5-star reviews.

#### Percentages

##### Vine (Paid) Review Percentage

- less than 0.1% of total reviews were made by paid reviewers.
- less than 0.01% o 5-star reviews were made by paid reviewers.
- 59% of paid reviews were 5-star reviews.

##### Non-Vine (Unpaid) Review Percentages

- 99.9% of total reviews were made by unpaid reviewers.
- 86% of 5-star reviews were made by unpaid reviewers.
- 46% of unpaid reviews were 5-star reviews. 

## Summary
