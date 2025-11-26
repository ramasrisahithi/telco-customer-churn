# Customer Churn Analysis (Telco Dataset)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ramasrisahithi/telco-customer-churn/blob/main/customer_Chrun_Analysis.ipynb)

**Project Overview**

This project focuses on developing a complete machine learning pipeline to predict customer churn in the telecom industry. The goal is to understand why customers leave and build a model that can accurately classify high-risk customers. The project follows an end-to-end workflow, including data preprocessing, exploratory analysis, feature engineering, model development, and generating final predictions.

**Dataset Description**

The dataset contains information about customer demographics, subscription details, internet and phone services, billing patterns, and churn status. Each record represents an individual customer along with attributes such as gender, tenure, monthly charges, contract type, payment method, and service usage. These features help in identifying behavioral patterns that influence churn decisions.

**Data Preprocessing**

The preprocessing phase involved cleaning the dataset by handling missing values, correcting inconsistent entries, and converting data into appropriate formats. Categorical features were encoded using label encoding techniques to make them compatible with machine learning models. Additional derived features were created to strengthen the predictive capability of the dataset and highlight customer behavior more effectively.

**Exploratory Data Analysis (EDA)**
A detailed exploratory analysis was performed to understand how various factors correlate with churn. The analysis revealed that customers with month-to-month contracts, high monthly charges, and specific service combinations were more likely to churn. Visualizations and summary statistics helped identify patterns in tenure distribution, service adoption, and billing behavior. These insights guided feature selection and model development.

**Model Development and Evaluation**

Several machine learning algorithms were trained and compared, including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting classifiers. Each model was evaluated using accuracy, precision, recall, F1-score, and ROC-AUC to assess overall performance and its ability to classify churn correctly. The best-performing model was optimized and saved as a .pkl file to enable future predictions without retraining.

**Prediction and Output**

Once the model was finalized, it was used to generate churn predictions for unseen customer data. The saved encoders and model file allow users to load the model directly and classify new customers into churn or non-churn categories. This demonstrates how the machine learning pipeline can be integrated into real-world decision-making workflows.

**Conclusion**

This project demonstrates practical experience in data cleaning, statistical exploration, machine learning engineering, and predictive analytics. It showcases the complete lifecycle of developing a churn prediction system using Python and Scikit-learn. The final model provides valuable insights into customer behavior and can assist telecom companies in improving their retention strategies.
