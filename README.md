# Ecommerce-Churn-Prediction

In the long term, customer churn will have a huge loss impact on the company. Therefore, companies need to address this problem. it cost 5x more to get a new customer than it did to keep an existing

This project aim to reduce churn rate, with objective finding the importance factor affect churn customer. Knowing those factors help business can implement proper strategy. And our prediction model helps company to implement strategy appropriately. 

Using our model and recommendation can potentially **decrease up to 14.39%**

## Dataset Overview

1 Year historical data, contains of 5630 customer data and 19 independent features. Target feature explain wheter customer will churn or not. Data Source : [link](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction)

## Data Preprocessing

1. Handling Missing Values
2. Feature Engineering
3. Feature Encoding
4. Feature Transformation
5. Outlier Handling
6. Target Imbalaced Handling

## Modeling :

After doing some experiments, we tried 7 Algorithm to find the best model. We found Random Forest with score:
1. F2 Train Score: 1
2. F2 Test Score : 0.97

We consider F2 Score to minimize False Negative (predicted as customer who retain but actually churn)

## Recommendation :
1. Reallocate cashback targeting
2. Limit devices registered
3. Limit address refistered

Implementing this strategy can decrease churn rate up to 14.39%
