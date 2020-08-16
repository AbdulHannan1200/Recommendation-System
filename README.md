# Recommendation-System
### You can download dataset from kaggle.
#### Brazilian E-Commerce Public Dataset by Olist
Here is the link of the dataset:
`https://www.kaggle.com/olistbr/brazilian-ecommerce?select=olist_order_items_dataset.csv`


### Project Details:
This is basically recommender system for e-commerce website, dataset consist of many parameters, some of them are inputs, 3 of them are output and rest are useless declared on the basis of statical and data analytics.

We used machine learning and deep learning models for the prediction, and the most important point which should be noted that we achieve 100% accuracy on testing data which is quite incredible.
The most important key which leads to achieve that much accuracy is data pre-processing and and analytics.
The input parameters are :

  1. order_id 
  2. product_id
  3. freight_value
  4. seller_lat
  5. sellet_lng
  6. customer_lat 
  7. customer_lng


And the output paramters are:

  1. review_score
  2. product_category
  3. product_price


### Model Used:
We used Decision tree for predicting  `review_score` and `product_category`, these both belongs to classification problem.
We used Neural Network for predicting `product_price` and this belong to regression problem.
