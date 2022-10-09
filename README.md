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

#### 1. Vine vs Non-Vine Reviews

22 paid and 26924 unpaid reviews were present, to a total of 26946 total reviews.

#### 2. 5 - Stars?

13 paid 5-star reviews and 12485 unpaid 5-star reviews were present, to a total of 14452 5-star reviews.

#### 3. Percentages

##### Vine (Paid) Review Percentage

- less than 0.1% of total reviews were made by paid reviewers.
- less than 0.01% o 5-star reviews were made by paid reviewers.
- 59% of paid reviews were 5-star reviews.

##### Non-Vine (Unpaid) Review Percentages

- 99.9% of total reviews were made by unpaid reviewers.
- 86% of 5-star reviews were made by unpaid reviewers.
- 46% of unpaid reviews were 5-star reviews. 

## Summary

There seems to be a positive bias of the paid reviews for the Amazon program, given the fact that despite the very small population size of the paid reviews, 59% of them gave 5-star ratings whereas only 46% of a much bigger unpaid review pool gave 5-star ratings. It would be beneficial to conduct this analysis across different items and compare the trends of positive reviews to see whether paid reviews always have higher percentage 5-star reviews than unpaid. Furthermore, statistical analysis using st.dev, average, and margins of error would assist in proving the validity of this data pool.
