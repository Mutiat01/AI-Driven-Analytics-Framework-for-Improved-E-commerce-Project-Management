# AI-Driven-Analytics-Framework-for-Improved-E-commerce-Project-Management

## Overview

This project applies advanced machine learning and data analytics techniques to tackle key business challenges in e-commerce. It includes models for predicting order cancellations and delivery delays, forecasting product category sales, estimating repeat purchase propensity, and understanding drivers of customer satisfaction. Through thoughtful feature engineering, robust validation, and clear reporting, the project delivers reliable insights that support both operational excellence and strategic decision-making.

## Key Components

### **Order Cancellation Prediction**
Predicts which orders are likely to be cancelled. This enables proactive customer service, reduces revenue loss, and improves supply chain and fulfillment efficiency.

### **Product Category Sales Forecasting**
Forecasts sales at the category level to inform inventory planning, marketing strategies, and supply chain optimization—reducing stockouts and overstock situations.

### **Repeat Purchase Propensity Modelling**
Estimates the likelihood of a customer making another purchase. Results can be used to drive personalized marketing, loyalty initiatives, and customer lifecycle management.

### **Feature Engineering & Selection**
Transforms raw data into meaningful inputs and identifies the most predictive features to improve model accuracy, interpretability, and performance.

### **Model Validation & Hyperparameter Tuning**
Ensures model reliability through cross-validation, performance metrics, and algorithm tuning for optimal generalization to unseen data.

### **Delivery Delay Prediction**
Predicts expected delivery delays (in days) based on order attributes. Helps operational teams flag at-risk shipments and proactively manage delivery workflows.

### **Late Delivery Classification**
Classifies orders as “late” or “on-time” before shipment. This supports resource planning, customer communication, and last-mile logistics optimization.

### **Customer Satisfaction Prediction**
Predicts customer review scores using order-level data. Enables teams to identify drivers of satisfaction/dissatisfaction and intervene earlier to improve the customer experience.

## Tech Stack

- Python, Pandas, scikit-learn  
- Jupyter Notebooks  
- *Optional:* XGBoost, matplotlib, seaborn for advanced modelling and visualization  

### Download the dataset from Kaggle
👉 [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=olist_order_reviews_dataset.csv)

### Prepare the Data
Place the downloaded dataset(s) in the `/data` directory.

### Run the Project
- Execute the notebooks or scripts in sequence to perform:
  - Data exploration  
  - Preprocessing  
  - Modeling  
  - Evaluation  

- Refer to each notebook/script for detailed pipeline instructions.

---

## Results

- Models are evaluated using industry-standard metrics such as:  
  **Accuracy**, **F1**, **ROC AUC**, **MAE**, **RMSE**, and **R²**.

- Each modelling task includes:
  - Clear performance reports  
  - Actionable recommendations for improvements or next steps  

## Getting Started

1. **Clone the repository and install dependencies:**
   ```bash
   pip install -r requirements.txt
