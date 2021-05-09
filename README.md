

# E_Commerce_Spark_Data-Analysis
---
This data analysis project aims to preprocess the data using pyspark to find critical insights and derive meaning from them.

## Table of contents
---
* [Introduction ](#Introduction)
* [Setup](#setup)
* [Reference](#Reference)


### Introduction 
---
This project is divided into 2 notebooks:
- 1-RFM Analysis and Kmens 
- 2-Visual business analysis

#### RFM Analysis
- Used to segregate the customers based on behaviors
 
__RFM helps in segregating:__
- the more recent the purchase, the more responsive the customer is to promotions
- the more frequently the customer buys, the more engaged and satisfied they are
- monetary value differentiates heavy spenders from low-value purchasers

__first step__
- preprocess the data using pyspark and calculate RFM scores

__second step__
- try to segregate customers based on RFM analysis. First, we'll create clusters and see characterstics of each cluster

__Third step__
- Train a k-means model 

##### Visual business analysis
__We will look for trends in data such as:__
- Revenue trends
- Quantity Sold Trends
- New Customers Trends
- Transactions Count Trends
- Revenue by Months
- Quantity Sold by Months
- Growth Month wise
- Growth Month wise
- Revenue and Quantity by Sale Week Day , Hourwise ,Daywise ,Sale Quarterly
- Regionwise Analysis


#### output 
---
![Regionwise_Analysis](https://user-images.githubusercontent.com/34807427/117584028-21882e80-b113-11eb-8fe3-85cfe7740100.png)

![revnue_by_month](https://user-images.githubusercontent.com/34807427/117584029-2351f200-b113-11eb-9781-2e181d7e4421.png)

![Trends](https://user-images.githubusercontent.com/34807427/117584030-23ea8880-b113-11eb-90d5-43387bf632c7.png)


## Setup  
---
- Subscribe to Databricks
- Create a cluster in pyspark
- Install the following packages in the DataBricks cluster: plotly ,pandas ,seaborn 
- Run the notebook


## Reference
---
- k-means-clustering-using-pyspark (https://medium.com/swlh/k-means-clustering-using-pyspark-on-data-bricks-fd65e207154a)
- RFM-analysis  (https://clevertap.com/blog/rfm-analysis/)
- E-Commerce Dataset (https://www.kaggle.com/carrie1/ecommerce-data)


