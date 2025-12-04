# Olist Brazilian E-commerce Prediction

This repository contains an interactive Jupyter Notebook for predictive analytics and KPI monitoring on the [Olist Brazilian E-commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). The notebook demonstrates how to transform raw business data into actionable insights for IT project management, customer experience improvement, and e-commerce process optimization.

## Project Overview

The notebook approaches each order as a distinct project, analyzing constraints of time (delivery schedules), cost (order/freight value), and quality (customer satisfaction scores). The main objectives are:

- To monitor and benchmark Key Performance Indicators (KPIs): schedule delay variance, quality measures, and financial performance using descriptive analytics.
- To predict project failures (e.g., late/cancelled deliveries, low satisfaction) using machine learning models.
- To prepare clean, reliable features for downstream data visualization (such as in Tableau dashboards).

## Data and Preprocessing

The analysis uses 8 tables from the Kaggle dataset; customers, orders, order payments, order reviews, sellers, products, geolocation, and category translations:

- *Data Cleaning* includes normalization of categorical fields, de-duplication, handling missing values and outliers, and standardizing time/date formats.
- *Feature Engineering* includes imputation for missing values, encoding categories, and deriving new variables (e.g., delivery delay, payment method indicators).

## EDA and KPI Analysis

- Trends in revenue, monthly sales, payment preferences, and delivery performance are visualized.
- KPI benchmarks are established for delivery delays, late/early rate, and satisfaction distributions, supporting deeper root-cause analysis and prioritization of operational improvements.

## Predictive Modeling

Several machine learning models are implemented, including:
- *Classification*: Predicting risk of order cancellation, late delivery, and low review scores using gradient boosting (XGBoost), random forest, and logistic regression.
- *Regression/Forecasting*: Time series analysis or regression tasks (with Prophet, where applicable).

Models are evaluated using metrics such as AUC, accuracy, and cross-validation scores. Feature selection methods like RFE and SelectKBest are applied for optimal input selection.

## How to Run

1. Download the Olist dataset from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) and place CSV files in your notebook directory.
2. Install requirements:
