# Causal_Analysis
Causal Analysis of Customer Churn using DeepLearning

In this experiment a framework proposed for Causal Analysis of Customer Churn by using DeepLearning algorithm and DoWhy packages, using the Deep Feed Forward Neural Network DFF NN algorithm accompanied by a sequential pattern mining method on a massive financial dataset with high-dimensional sparse data for the classification task. We also propose a causality analysis system for predicting the probability of causes that lead to customer churn.

Experiments were conducted on 12 datasets were for members holding accounts provided by a local finance company. The datasets cover customers account, demographics, customer engagement and financial data. Each dataset is including 88 features (71 numerical and 17 nominal data), around 250k examples. Final data cleansing is done based on criteria previously mentioned in the data mining section to improve prediction accuracy.
Based on our empirical results on the datasets shown in figure 4. around 90 per cent of customers fall into customer and account tenure value between 5 and 12 months, and average account tenure in different datasets is around 7.6 months which means most customers close their account in less than one year. Therefore, after a trade-off between having more historical data and observing more sample data, a rational approach is that we consider the customers’ account that was open only more than six months which means we eliminate all accounts that are recently opened.

Churn Propensity Modelling Workflow

The neural network algorithm, and seven of the most popularly used classifiers were applied on datasets with the mentioned method of 12-
month observation window and 6-month outcome window. 

