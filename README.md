# Snowflake Healthcare Analytics Project on AWS

## 📌 Overview
This project leverages "healthcare analytics" to improve patient outcomes and reduce costs by focusing on the "Length of Stay (LOS)" metric in healthcare facilities.  
By integrating "Snowflake" for data handling and "AWS SageMake AI" for machine learning, the project enables real-time LOS prediction, automated scoring, and actionable insights.

---

## 🏥 Business Context
- Length of Stay (LOS) is a critical metric impacting patient outcomes, healthcare costs, and hospital capacity.  
- Accurate LOS analysis and prediction help:
  - Optimize hospital resources.
  - Reduce healthcare costs.
  - Improve patient care and discharge planning.

---

## 🎯 Objectives
- Analyze patient LOS data to identify areas for improvement.  
- Predict LOS using ML models (Linear Regression, Random Forest, XGBoost).  
- Store and process data in 'Snowflake'.  
- Deploy and automate ML models in 'AWS SageMaker'.  
- Perform live scoring and integrate predictions into Snowflake.  
- Send status notifications via email.

---

## ⚙️ Technical Workflow
-1.Introduction to Snowflake: Understanding the Snowflake platform and its application in data analytics.
-2.Exploratory Data Analysis (EDA) in Snowflake: Performing initial data exploration within Snowflake.
-3.Feature Engineering in Snowflake: Enhancing data for model building.
-4.AWS Sagemaker Setup: Configuring the AWS Sagemaker environment for model development.
-5.Data Fetching: Using snowflake-connector-python and snowflake-sqlalchemy for data extraction.
-6.Data Preprocessing: Preparing data for modeling.
-7.Feature Selection: Choosing relevant features for the model.
-8.Model Building: Developing models like Linear Regression, Random Forest Regression, and XGBoost Regression.
-9.Model Predictions: Generating and analyzing predictions.
-10.Inserting Predictions in Snowflake: Storing model outputs back into Snowflake.
-11.Scoring Function Deployment and Scheduling: Automating the model scoring process.
-12.Sending Status Emails: Setting up notifications regarding the process status.

---

## 🗂️ Project Structure
```
End-to-End-Snowflake-Healthcare-Analytics-Project-on-AWS/
├── README.md                     # Project README
└── Code/
    ├── Data/
    │   ├── health_data.csv       # Training data (~230k patients, 19 features)
    │   └── simulation_data.csv   # Simulation data (~71k patients)
    ├── Python Files/
    │   ├── LOS_Preprocessing.py
    │   ├── MODEL_FEATS.pkl
    │   ├── MODEL_XGB.model
    │   ├── MODEL_training_data_with_final_features.pkl
    │   ├── Preprocessing _ Model Building.ipynb
    │   ├── Scoring Script.ipynb
    │   ├── mail_creds.py
    │   └── snowflake_creds.py
    └── SQL Queries/
        ├── Snowflake-EDA.sql
        ├── Snowflake-Feature Engineering.sql
        └── Snowflake-Scoring Script.sql
```

---

## 📊 Data
- Training Data: 230k patient records, 19 features, across multiple hospitals/regions.  
- Simulation Data: 71k patient records for prediction.  

---

## 🛠️ Tech Stack
- Tools: Snowflake, AWS SageMaker  
- Language: Python  
- Libraries:  
  - Data Handling - `pandas`, `numpy`  
  - ML & Modeling -  `scikit-learn`, `xgboost`  
  - Integration -  `snowflake-connector-python`, `snowflake-sqlalchemy`  

---


## ✅ Key Takeaways
- Learn data analysis in Snowflake.  
- Perform feature engineering and preprocessing.  
- Build and evaluate multiple ML models for LOS prediction.  
- Automate ML pipelines in AWS SageMaker.  
- Integrate real-time predictions into Snowflake.  
- Implement email notifications for monitoring.  

---

## Author
Nandini Kosgi
Linkedin: https://www.linkedin.com/in/nandinikosgi/

