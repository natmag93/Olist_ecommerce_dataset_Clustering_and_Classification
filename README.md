# Olist E-commerce Dataset:  
Customer Clustering & Classification

This project focuses on leveraging data science techniques to analyze a brazilian e-commerce dataset. Primary objectives were: first, to cluster clients based on their purchasing behavior, and second, to classify customers likely to return.

## Dataset
This dataset was provided by Olist, which was made publicly accessible on kaggle.com. The dataset has information of 100,000 orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allow you to evaluate an order from a variety of perspectives, including order status, pricing, payment, and freight performance, as well as customer location, product qualities, and customer feedback.

Dataset Link: [https://www.kaggle.com/olistbr/brazilian-ecommerce](https://www.kaggle.com/olistbr/brazilian-ecommerce)

## Business understanding 

**Background/ Requirements Gathering**
 - The company is an e-commerce platform that sells to multiple
   marketplaces in Brazil.
 - From 2016 to 2018, all orders placed were    recorded and one major
   business problem was detected, namely that the    majority of
   customers who placed orders did not return.

**Business/Project Objectives and Scope**
 - Gain insight into what drives people to buy our product
 - *Clustering -* Segmentation of customers per group to customize future client service.
- *Classification -* In order to predict customer’s return. The project, which spanned over one month, followed the CRISP-DM methodology. 


## Project steps:

- Data understanding 
	- Data profiling and EDA.
-  Data Preparation
- Modeling
	- K-means, RF, DT and SVM algorithms
- Evaluation

tools used: Power Bi, Python (pandas), R (tidyverse, smotefamily, e1071, rpart, factoextra)

## Data understanding

## Data preparation

## Modeling

## Evaluation

https://github.com/natmag93/Olist_ecommerce_dataset_Clustering_and_Classification/blob/97027db4915dca2a64765a3f7d1f54f0d02b0477/evalution_kmeans.png

https://github.com/natmag93/Olist_ecommerce_dataset_Clustering_and_Classification/blob/97027db4915dca2a64765a3f7d1f54f0d02b0477/evalution_classification.png


## Conclusions 

Detailed customer segmentation using Recency, Frequency, and Monetary successfully classified them into 10 groups. Each group had characteristics which allow specific actions/impact. These insights can be used as a business leverage to customize future client service.
The model selected for classification of returned customers had an acceptable performance and was able to correctly predict 48.09 % of them. However, 40.93 % of customers who did not return were incorrectly predicted as returned. These insights can be used as a business leverage, but with caution.
It is also important to note that some limitations regarding data were found. This includes a low number of customers who returned (1.6%) vs not returned (98.4%), as well as having some variable with a high dispersion. Moreover, available variables might not be enough to understand (predict) what made customers return.

**Future Work**
Alternative outcomes could be explored for customer segmentation using different approaches, including: the creation of other features, application of other clustering algorithms (e.g., Hierarchical clustering or Gaussian Mixture Models), use of other clustering evaluation metrics (e.g., Dunn index or Fowlkes-Mallows index), and use different techniques for normalization, dimensionality reduction (i.e., PCA), detection and treatment of outliers and missing values.
The prediction of customers return could also be carried out using different classification models (e.g., xgboost). Other features could be created, including ones related to client’s reviews.
