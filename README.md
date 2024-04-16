# Customer Analytics



# 1. Data

The train dataset used for model building contained 10999 observations of 12 variables, and the test dataset used for predicting the target variable contained 3993 observations of 12 variables.
Data description: 
ID :ID number of the customer.
Warehouse block: The company has a big warehouse which is divided in various blocks such as A,B,C,D adn F
Mode of shipment : The company ships the products by different modes of transport such as ship, flight and road.
Customer care calls: The number of calls made for enquiry of the shipment.
Customer rating : The company has rated every customer on various parameters, 1 being the lowest (Worst), 5 being highest (Best).
Cost of the product :Cost of the product in US Dollars
Prior purchases : The number of prior purchases.
Product importance :The company has categorised the products in the range of high, medium and low based on various parameters.
Gender: Customer gender
Discount offered: Discount offered on that specific product.
Weight in gms : Product's weight in grams
Reached on time: target variable, where 1 Indicates that the product has NOT reached on time and 0 indicates it has reached on time.

# 2. Objective

The objective of the project outlined in the R script is to analyze customer data to uncover trends and patterns that may contribute to a higher rate of delayed deliveries. Additionally, the project aims to utilize machine learning algorithms to develop the most effective model for predicting whether shipments reach customers on time. 

# 3. Classification Model

The model used in the project are: 
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Support Vector Machine (SVM)

# 4. Result

The best model is 
