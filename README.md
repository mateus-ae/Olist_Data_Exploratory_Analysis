# Olist_Data_Exploratory_Analysis
This Project consists in an exploratory analysis on datasets from Olist Store using pandas and matplotlib libraries.

This dataset was downloaded from Kaggle and can be found at: <https://www.kaggle.com/olistbr/brazilian-ecommerce>

## About the dataset:
"This is a Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

This is real commercial data, it has been anonymised, and references to the companies and partners in the review text have been replaced with the names of Game of Thrones great houses.
This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. See more on our website: www.olist.com

After a customer purchases the product from Olist Store a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments."

## About the data:
The data consists in 8 csv files, with anonymised informations about customers, orders, payments, reviews, products, geolocation, and sellers.
There is one last dataset that contains translations of product categories from portuguese to english.

The 8 csv files have structured data and they relate with each other using a schema that can seen in the image below:
<p><img src="./DataSchema.png" width="700"></p>

## About this project:
This project is an analysis on the datasets to find out some interesting insights.

Analysis that were made:

* Number of Customers per State
* Number of Customers per City in SP - Top 30
* Cities with the highest number of customers in each State
* Top 50 customers
* Top 20 Selling Items
* Customer's Review Scores:
* Customer's Review Scores - Boxplot
* Customer's Review Scores - Density
* Customer's Review Scores - Description
* Sails per Category
* Best Selling Categories - Top 20
* Revenue x Month (From 2016 to 2018)
