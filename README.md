# Customer Churn Prediction ML Pipeline

## Business Problem
Customer churn is a major challenge for telecom companies. When customers leave a service provider, it leads to revenue loss and increased acquisition costs for new customers.

This project builds a machine learning pipeline to predict which customers are likely to churn so that companies can proactively take retention actions.

---

## Dataset

Dataset: **Telco Customer Churn Dataset**

Source:  
https://www.kaggle.com/blastchar/telco-customer-churn

The dataset contains information on **7,043 telecom customers** with **21 variables**, including:

- Customer demographics
- Account information
- Services subscribed
- Billing details
- Churn status (target variable)

Key variables include:

- tenure
- MonthlyCharges
- TotalCharges
- Contract type
- Internet service
- Online security
- Payment method

Target variable: Churn (Yes/No)


---

## Project Pipeline

The project follows a typical machine learning workflow:

1. **Data Loading**
2. **Data Cleaning**
3. **Feature Engineering**
4. **Train-Test Split**
5. **Classification Models**
6. **Model Evaluation**

Models used:

- Logistic Regression
- Decision Tree
- Random Forest

---

## Project Structure
customer-churn-ml-pipeline
│
├── data
│ └── telco_churn.csv
│
├── notebooks
│ └── churn_analysis.Rmd
│
└── README.md


---

## Tools Used

- R
- tidyverse
- ggplot2
- dplyr
- caret
- randomForest

---

## How to Run the Project

1. Clone the repository
git clone https://github.com/YOUR_USERNAME/customer-churn-ml-pipeline.git


2. Open the notebook


notebooks/churn_analysis.Rmd


3. Run the code to reproduce the full churn prediction analysis.

Dataset is loaded using:


read_csv("../data/telco_churn.csv")


---

## Key Insight

Customer churn is strongly associated with:

- contract type
- monthly charges
- tenure
- additional service subscriptions

Machine learning models can help telecom companies identify high-risk customers and target retention strategies.

---

## Author

Karthik Radhakrishnan  
MS Business Analytics  
University of Kansas
