# Instacart-Market-Basket-Analysis
Model based on instacart Market basket analysis using Tenserflow Framework

# Goal of Model
The goal is to predict which products will be in a user's next order. The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart user.

# File descriptions
Each entity (customer, product, order, aisle, etc.) has an associated unique id. 

## aisles.csv
Aisles:
    
    1,  prepared soups salads
    2,  specialty cheeses 
    3, energy granola bars
     ...


## departments.csv
Departments :
    
    1,frozen  
    2,other  
    3,bakery 
    ...

## order_products__*.csv
These files specify which products were purchased in each order. order_products__prior.csv contains previous order contents for all customers. 'reordered' indicates that the customer has a previous order that contains the product. Note that some orders will have no reordered items. You may predict an explicit 'None' value for orders with no reordered items

## orders.csv
This file tells to which set (prior, train, test) an order belongs. You are predicting reordered items only for the test set orders. 'order_dow' is the day of week.

# Dataset
 Please download the dataset from [https://www.kaggle.com/c/instacart-market-basket-analysis/data]
 
 # classifier
 Constructed using Tenserflow GBM
 
 # Requirements
 Python 3.8.1
  
 Python Packages :
    
    Tenserflow GBM 2.0
    Numpy 1.8
    Pandas 0.25.0
    Matplotlib 3.1.2
    Scikit-learn 0.22.1
 
