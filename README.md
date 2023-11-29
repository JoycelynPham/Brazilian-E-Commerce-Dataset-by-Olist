# Brazilian-E-Commerce-Dataset-by-Olist

![image](https://github.com/JoycelynPham/Brazilian-E-Commerce-Dataset-by-Olist/assets/148677481/add18cda-9e01-4e28-97f2-94bb3327a03b)
Olist is a Brazilian e-commerce startup marketplace integrator, founded in 2015, with the mission of connecting small businesses to larger product marketplaces to help entrepreneurs sell their products to a larger customer base

# About Dataset
Data source: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data

This is a Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. See more on our website: www.olist.com

After a customer purchases the product from Olist Store a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.

## Olist data schema
![image](https://github.com/JoycelynPham/Brazilian-E-Commerce-Dataset-by-Olist/assets/148677481/fd76f96d-32ef-4c0d-b69e-e5201eb7571e)


Project Intro/Objective

The purpose of this project is to provide nessesary and important informations for new seller who wish to enter this new online platform in Brazil
Clarify 3 main questions for new sellers:

What to sell ?
Where are the potential customers ?
When to sell ?

Provide solutions based on these 3 criterias

Methods Used

Machine Learning
Data Visualization

Technologies

Python
Pandas, Seaborn, Matplotlib
LDA model
Bag of Word
Google trans
Project Description

The data of this project came from kaggle (Brazilian E-Commerce Public Dataset by Olist). Our team firstly formed a big question about what are the product that were becoming popular as well as those that received fewer support by customers. Nevertheless, we then redirected our big questions into helping new sellers who try to join this online platflorm and used the original big question as a key point to help answer the new question. We firstly try to apply data cleaning and then do some visualizations on finding top trending products. Then we draw charts and defined specific time zone in which customers paid the most and lastly we analyzed comments left by customers in order to find out what are the problems customer usually criticised about.

Throughout the entire project, we used various of techniques in visualizing as well as cleaning / selecting relavants columns from the dataset such as seaborn countplot, pivot table, convert long from to wide form, etc. Furthermore, we also used scikit learn to apply machine learning for analyzing comments, grouping comments into top 10 topics and defined top mentioned term. For example: I still received product, I did not recieve the product, etc.

The big problems we had is to define the big question and find key ideas to support it. Not only did the big question need to be attractive and realistic, but also the key ideas to support it had to be indepth and clearness.
