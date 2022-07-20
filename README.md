# Automatic Ticket Classification
> For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers. 

- We need to build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.With the help of non-negative matrix factorization (NMF), an approach under topic modelling, you will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories. By segregating the clusters, you will be able to identify the topics of the customer complaints. 


## Table of Contents
* [Business Overview](#Business-Objective)
* [Technologies Used](#Technologies-Used)
* [Exploratory Data Analysis & Model Steps](#Steps)
* [Conclusions](#Conclusions)

## Business-Objective

For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers.

- The company wants to analyse patterns and classify tickets into the following five clusters based on their products/services:

- -Credit card / Prepaid card

- - Bank account services

- - Theft/Dispute reporting

- - Mortgages/loans

- - Others 

> dataset : complaints.json

## Technologies-Used
- pandas      - Version : 1.2.4
- numpy       - Version : 1.20.1
- seaborn     - Version : 0.11.1
- matplotlib  - Version : 3.3.4
- statsmodels - Version : 0.12.2
- pandasql    - Version : 0.7.3
- sklearn     - Version :0.24.2

# Exploratory Data Analysis & Model Steps

## Steps

- Data Reading/Data Understanding
- Data Cleaning
- Data Preprocessing
- Data Visualisation
- Feature Extraction
- Topic Modelling
- Model Building
- Model Inference


## Conclusions

- Out of all the models that we have created so far Logistic regression is performing good 

> - Training Accuracy : 96.06 % 

> - Test Accuract : 94.7 %

- We will use Logistic regression for Ticket evaluation

## Contact
Created by [@shashank1989] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
