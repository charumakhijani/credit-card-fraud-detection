# Credit-Card-Fraud-Detection
Every year, millions of people fall victim to fraud that costs the global economy billions of dollars. If you're a victim, it can wreak havoc on your personal finances. Luckily, due to some modern fraud detection techniques many financial institutions have measures in place to help protect you from credit fraud.

Dataset is from below URL <br>
https://www.kaggle.com/mlg-ulb/creditcardfraud

## Fraud Detection
Fraud Detection is a technique used to identify unusual patterns that are different from the rest of the population and not behaving as expected. These unusual patterns are also called as outliers.

The fraud detection involves in-depth data analysis/data-mining to recognize the unusual patterns. In this dataset, most of the data analysis part is already done and most of the features are scaled. The names of the features are not shown due to privacy reasons.

Hence our main focus will be to balance the data and perform predective analysis.

## Problem Statement
The Credit Card Fraud Detection dataset contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## Goals
Goal here is to identify as much fraudulent credit card transactions as possible. And as mentioned in the dataset insperation, I will calculate the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

## Table of Contents

1. [Import Libraries](#import-libraries)
2. [Read Data](#read-data)
3. [Understand the data](#understand-data)
    * [Check missing values](#check-missing-values)
4. [Exploratory Data Analysis](#eda)
    * [Observations from Data](#data-observations)
5. [Label Data](#label-data)
6. [Cluster data using Dimensionality reduction](#cluster-data)
7. [Split into train and test sets](#split-data)
8. [Scaling](#scaling)
9. [Predictive Analysis on unbalanced data](#unbalanced-predictive-analysis)
    * [Logistic regression](#unbalanced-lr)
    * [Decision Tree](#unbalanced-dt)
    * [Random Forest](#unbalanced-rf)
    * [Adaboost](#unbalanced-adaboost)
    * [XGBoost](#unbalanced-xgboost)
10. [Validate Unbalanced Data](#validate-unbalanced)
    * [ROC Curve](#unbalanced-roc)
    * [Precision-Recall Curve](#unbalanced-pr)
11. [Balance Data using oversampling method](#balance-data)
    * [Understand Balanced Data](#understand-balanced-data)
12. [Predictive Analysis on Balanced Data](#balanced-predictive-analysis)
    * [Logistic Regression](#balanced-lr)
    * [Decision Tree](#balanced-dt)
    * [Random Forest](#balanced-rf)
    * [Adaboost](#balanced-adaboost)
    * [XGBoost](#balanced-xgboost)
    * [Neural Networks](#balanced-nn)
13. [Validate Balanced Data](#validate-balanced)
    * [ROC Curve](#balanced-roc)
    * [Precision-Recall Curve](#balanced-pr)
14. [Feature Importance](#feature-importance)
15. [Conclusion](#conclusion)
