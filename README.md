# Capstone Project PART 3 (Machine Learning Classification) - Telco Customer Churn Dataset

<p align="center">
  <img src="./docs/header.png" alt="Header" width="800" height="400">
</p>

## Problem Statement
**"Optimizing Customer Retention Strategies in Telecommunications: Predictive Analysis of Customer Churn"**

In the competitive telecommunications sector, retaining customers is often more cost-effective than acquiring new ones. However, the industry is plagued with high customer churn rates due to competitive offerings, price sensitivity, and service dissatisfaction. This project aims to employ predictive analytics to identify customers at high risk of churn. By analyzing patterns in customer data such as tenure, services used, security features, and billing methods, we will develop a model to predict churn likelihood. This model will enable targeted interventions to improve customer satisfaction and retention strategies, thus reducing churn rates and enhancing profitability.

## Goals

Throughout the entire process of this analysis, by the end of it, we expect to suffice in answering and give solutions for these points below :

- The characteristics of customers who left the service (`yes` Churn / class:1 )
- Predictions of the customers' chances churning (Stopped using service) 
- Strategies in how to prevent customers' from churning
- Most significant factors that influenced customers to churn


## Context

The dataset represents customer profiles who have left the telco company. A churn in telco and other subscription-based services means a situation when the customer leaves the service provider. 


## Data

Using dataset `data_telco_customer_churn.csv`. [Download Link](https://drive.google.com/drive/folders/1_fR7R0srpZgnFnanbrmELgnK-xmzMAHp)


**Column Descriptions**:

| Features         | Description                                       |
|-------------------|---------------------------------------------------|
| Dependents        | Whether the customer has dependents or not        |
| Tenure            | Number of months the customer has stayed with the company |
| OnlineSecurity    | Whether the customer has online security or not   |
| OnlineBackup      | Whether the customer has online backup or not     |
| InternetService   | Whether the client is subscribed to Internet service |
| DeviceProtection  | Whether the client has device protection or not   |
| TechSupport       | Whether the client has tech support or not        |
| Contract          | Type of contract according to duration            |
| PaperlessBilling  | Bills issued in paperless form                    |
| MonthlyCharges    | Amount of charge for service on monthly basis     |
| Churn             | Whether the customer churns or not                |



## Analysis, Experiments, Conclusions, and Recommendations

Refer to file Capstone3Final.ipynb

## Deployment

Refer to file best_model_lgbmada_thres_rfe.pkl
