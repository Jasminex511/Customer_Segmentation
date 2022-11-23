
# RFM Analysis for Customer Segmentation

This notebook shows the process of an RFM(Recency, Frequency, MonetaryValue) analysis, which is a popular analysis for customer segmentation. It considers how recently, how frequently a customer make a purchse and how much in total did the customer spend to determine the most valuable group of customers. 

## Description

Customer segmentation is the practice of separating customers into different groups based on their similarity in ways that are related to marketing, such as transactional behaviours like interests. The use case of dividing customers is to market distinct groups of customer differently in order to maximize marketing efficiency and effectiveness.

The key thing is identifying the features that relate the customer together for the specific business that we are targeting. There are several popular customer segmentation models:
* Demographics: age, gender, family size, education level, etc.
* Geographics: country, city, town, etc.
* Psychographic: lifestyle, personality, social class, etc.
* Behavioral: spending habits, consumption, product interests, etc.

## Data
data.csv contains transactions of an e-commerce from UCI Machine Learning Repository. 

### Features
This dataframe contains 7 variables that correspond to:

1. **InvoiceNo**: Invoice number, uniquely assigned to each transaction. 
2. **StockCode**: Product code,  uniquely assigned to each distinct product.
3. **Description**: Product name.
4. **Quantity**: The quantities of each product purchased per transaction.
5. **InvoiceDate**: Day and time when each transaction was generated.
6. **UnitPrice**: Product price per unit.
7. **CustomerID**: Customer number, uniquely assigned to each customer.

Since the dataset we are using here is the customer historic transactions, so my code is using the behavioral segmentation model.

## Getting Started

* Python 3.7 is needed to run this project
* Main Python libraries needed:
** Pandas
** Datetime
** Seaborn
** Matplotlib
** Numpy
** Scikit-learn
* Software installed to run and execute a Jupyter Notebook

### Code
My code is included in the `RFM Analysis.ipynb` file and `data.csv` need to be installed in order to run this file successfully.
