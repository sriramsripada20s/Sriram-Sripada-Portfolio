# Sriram-Sripada-Portfolio
Analytics Portfolio

# [Project 1: Telstra - Predicting Service Faults On Australia's Largest Telecommunications Network Using Machine Learning](https://github.com/sriramsripada20s/Telstra_ML_endtoend_Project)

**Abstract**

In the modern era of technology, importantly in the Telecommunication space, the challenge to drive customer advocacy and build a loyal customer base has always been a major challenge for all the telecom providers. Over the years both the network volume and network conditions have changed, service disruptions or service faults have been the important cause for reduction in the number of active users. Identifying fault severity at a certain location and time, has always been a crucial business statistic because the major purpose of organizations is to create consumer advocacy, which helps them save money and retain and better service their customers. In this report we try to predict fault severity at a location using data mining techniques and help organizations detect Service faults. Various machine learning models have been used to predict faults and evaluated based on various classification metrics.

**Objective**

To predict Fault Severity at particular time and location based on log data available Fault severity has 3 categories: 0,1,2 (0 meaning no fault, 1 meaning only a few, and 2 meaning many)

## Overview of Simple End to End Architecture which I followed
![image](https://user-images.githubusercontent.com/49833524/220527312-afb87a95-33fa-42ba-b230-c7f1201839c0.png)

**Deployed Streamlit web app on Heroku Cloud created so that users could explore my LGBM Classification model predicting the Telstra network's Fault Severity at a time at a particular location based on the log data available.**

Steamlit App Deployed on Heroku: https://telstra-fault-prediction.herokuapp.com/
![image](https://user-images.githubusercontent.com/49833524/220527542-b910db0e-6faf-46c0-ae06-bbce513f94ee.png)


# [Project 2: Amazon Fine Food Reviews (Python, Text Classification, Natural Language Processing)]

**Obective**

To classify reviews as Positive and Negative based on the text/reviews provided by various users on Amazon

Amazon Fine Food Reviews Analysis Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

**The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.**

Number of reviews: 568,454 Number of users: 256,059 Number of products: 74,258 Timespan: Oct 1999 - Oct 2012 Number of Attributes/Columns in data: 10.

**Tasks Performed**

1.Used SQLite database and python to perform data loading and data extraction.

2.Transformed text using various featurization techniques like Bag of words, Bigrams, TF-IDF, TF-IDF, Avg W2Vec.

3.Found the best Machine learning Model by performing Hyper-parameter tuning (Grid Search) and compared them with train and test AUC scores, Accuracy and F1 Scores.

**How to determine if a review is positive or negative?**

We could use the Score/Rating. A rating of 4 or 5 could be cosnidered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is nuetral and ignored. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.
