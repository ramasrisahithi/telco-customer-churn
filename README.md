# Customer Churn Analysis (Telco Dataset)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ramasrisahithi/telco-customer-churn/blob/main/customer_Chrun_Analysis.ipynb)

This project analyzes customer churn using the Telco Customer dataset. It includes data cleaning, EDA, feature engineering, model training, and deployment-ready prediction pipeline using saved encoders and a trained model.

## 📁 Project Structure



# telco-customer-churn
Customer Churn Analysis – Machine Learning Project
**Overview**

This project analyzes customer churn using the Telco Customer Churn dataset. It includes data preprocessing, exploratory analysis, feature engineering, model training, evaluation, and churn prediction. The goal is to build an end-to-end churn prediction pipeline and identify customer behaviors that influence churn.

**Dataset**

The project uses the WA_Fn-UseC_-Telco-Customer-Churn.csv dataset, containing customer demographics, service subscriptions, account information, and churn labels.
Important features include tenure, monthly charges, contract type, payment method, and internet services.

**Tools & Technologies**

Google Colab

Python (pandas, numpy, matplotlib, seaborn, scikit-learn)

Machine Learning Models (Logistic Regression / Random Forest)

Pickle (.pkl) for saving encoders and trained model

GitHub for version control

**Project Workflow**

**Data Loading & Inspection**

Loaded the dataset, identified column types, missing values, and data inconsistencies.

**Exploratory Data Analysis (EDA)**

Visualized churn trends, service-level patterns, payment behaviors, demographic insights.

Identified factors strongly influencing churn.

**Data Preprocessing**
Cleaned and converted data types

Encoded categorical variables with LabelEncoders

Scaled numerical features

Saved preprocessing objects as encoders.pkl

**Model Building**

Trained ML model using structured data

Evaluated accuracy, precision, recall, confusion matrix

Exported the trained model as churn_model.pkl

**Prediction Pipeline**

Built a prediction script to load encoders + model

Generates churn prediction and probability for new customer records.

**Project Structure**
customer_churn_analysis/

    customer_Chrun_Analysis.ipynb   # Full analysis notebook
    encoders.pkl                    # Encoders for categorical variables
    churn_model.pkl                 # Trained ML model
    README.md                       # Project documentation
    WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset

**Results**

Identified key churn drivers across customer segments

Built and evaluated a predictive churn model with strong performance

Created a reusable prediction pipeline ready for integration or deployment

Helps organizations proactively reduce churn by targeting high-risk customers
