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


# Project Objective

Due to the limited information in this dataset, the project's goal is to conduct basic analyses on revenue and order trends, the popular product categories, customer and seller performance, as well as delivery time and review scores. Through these analyses, the aim is to provide recommendations for new sellers who wish to enter this online platform.
The questions to be answered in this project include: 

- What product categories should be sold? 
- Where is the potential market? 
- When should sales occur?

# Techniques:

Python
Pandas, Seaborn, Matplotlib

# Insights:

- 'bed_bath_table' and 'watches_gifts' are the top popular product categories with high order volumnes and relatively low seller competition. This indicates ongoing potential in these categories.

- The majority of customers are concentrated in SP state, and the ratio of sellers to customers in SP state is relatively low. Additionally, RJ and MG states are also emerging markets that attract attention. Consequently, SP, RJ, and MG are all potential markets for new sellers to explore.

- Customers tend to make purchases relatively steadily throughout the month but experience a sharp decline towards the end of the month. The purchasing time increase on weekdays and a decrease on weekends and the peak purchasing time is observed between 10 am and 10 pm.
Notably, customers tend to make more purchases on special days such as Black Friday or Cyber Monday

# Recommendations:

- Conducting a detailed analysis of each category is necessary to select specific products tailored for each state.
- Monitoring delivery times closely is crucial to prevent negative ratings and enhance competitiveness by reducing delivery times.
- Aligning marketing campaigns with periods when customers are inclined to make more purchases, especially during special occasions, is crucial. Additionally, implementing promotion programs for existing customers and attracting new ones is essential for customer retention.

# Challenge:
The challenge I faced is a lack of domain knowledge, and the dataset is too broad to analyze in order to define the main question and find key ideas to support it.
