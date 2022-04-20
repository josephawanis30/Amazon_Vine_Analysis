# Amazon_Vine_Analysis


## Overview of the analysis: 

The purpose of the analysis is to analyze Amazon reviews written by members of paid Amazon Vine program. The goal is to
see if there is a favorable Review bias from Vine members.  We will be using PySpark to extract the dataset then transform
data, connect to an AWS RDS instance and load the transformed data into pgAdmin., also using PySpark to analyze our data
to determine if there is any bias toward favorable Vine member reviews. We will be using Google Colab this makes it easier
to read datasets that are from the cloud also. Our data will be pulled from Amazon's Simple Storage Service (S3).


## Results: 

![image](https://user-images.githubusercontent.com/94503395/163915435-8a0c5049-9bca-44f2-a10c-1e24de115452.png)

![image](https://user-images.githubusercontent.com/94503395/163915461-d0baf1cd-7714-437a-afd4-7fa554f4126a.png)


How many Vine reviews and non-Vine reviews were there? 
* 607 Vine reviews (paid).
* 50,522 non-Vine reviews (Unpaid).

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* 257 5-stars Vine (paid) reviews
* 25,220 5-stars Vine (unpaid) reviews

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* Approximately 42% 5-stars Vine reviews.
* Approximately 50% 5-stars non-Vine reviews.

## Summary: 

Reviewing the results comparing the Vine vs. non-Vine reviews, there is not a bias for reviews in the Vine program.
A recommendation would be perhaps also an analysis to check for certain words in the reviews, or a summary statistic
showing the mean, median, mode, minimum value, maximum value, and standard deviation would be beneficial for
comparison of reviews in the Vine program Vs. non-Vine program reviews.
