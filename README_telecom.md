Telecom Customer Churn Prediction
📖 Project Overview

This project focuses on predicting customer churn in the telecommunications industry using machine learning techniques. Customer churn refers to customers discontinuing a company's services. By analyzing customer demographics, service subscriptions, tenure, contract information, and billing details, the project identifies customers who are likely to leave the company.

The objective is to help telecom companies improve customer retention, reduce revenue loss, and make data-driven business decisions.

📂 Project Structure
├── telecom_customer_churn.csv      # Raw dataset
├── telecom_code.ipynb              # Data preprocessing, EDA, and model building
├── images/                         # Visualizations and plots
├── requirements.txt                # Python package dependencies
└── README.md                       # Project documentation
🎯 Project Objectives
Analyze customer behavior and service usage patterns.
Identify factors influencing customer churn.
Perform exploratory data analysis (EDA) to discover meaningful insights.
Build and evaluate machine learning models for churn prediction.
Recommend strategies to improve customer retention.
📝 Dataset

The dataset contains customer demographic information, service details, contract information, billing data, and churn status.

Features Included
Customer Demographics
Gender
Senior Citizen
Partner
Dependents
Service Information
Phone Service
Multiple Lines
Internet Service
Online Security
Online Backup
Device Protection
Tech Support
Streaming TV
Streaming Movies
Contract Information
Contract Type
Paperless Billing
Payment Method
Billing Information
Monthly Charges
Total Charges
Target Variable
Churn (Yes/No)
🔍 Key Analysis Performed
Data Preprocessing
Handled missing values
Data cleaning and transformation
Feature encoding
Feature selection
Data preparation for machine learning
Exploratory Data Analysis (EDA)
Churn distribution analysis
Demographic analysis
Service-wise churn analysis
Contract type analysis
Billing analysis
Tenure analysis
Feature Importance Analysis

Key features influencing churn:

Tenure
Contract Type
Monthly Charges
Total Charges
🤖 Machine Learning Models Used
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
Evaluation Metrics
Accuracy Score
F1 Score
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
🛠️ Technologies & Libraries
Programming Language
Python
Data Analysis
Pandas
NumPy
Data Visualization
Matplotlib
Seaborn
Machine Learning
Scikit-learn
🚀 Getting Started
1. Clone the repository
git clone https://github.com/krishna-teja-ayodhya/telecom-customer-churn-prediction.git
cd telecom-customer-churn-prediction
2. Create & activate a virtual environment
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
3. Install dependencies
pip install -r requirements.txt
4. Launch the notebook
jupyter notebook telecom_code.ipynb
📊 Key Insights
Customers with shorter tenure are more likely to churn.
Month-to-month contracts show higher churn rates than long-term contracts.
Customers with higher monthly charges tend to churn more frequently.
Customers without partners or dependents have higher churn rates.
Streaming service users generally show better retention.
🏆 Results

Among all machine learning models evaluated:

Random Forest Classifier
Accuracy: 82%
Highest F1 Score
Lowest MSE and MAE

The Random Forest model demonstrated the best overall performance for predicting telecom customer churn.

💡 Business Recommendations
Encourage long-term contracts through incentives.
Develop retention programs for new customers.
Offer personalized plans for high-risk customers.
Improve customer engagement for month-to-month subscribers.
Monitor customers with high monthly charges and low tenure.
🔮 Future Enhancements
Hyperparameter tuning
Deployment using Streamlit
Real-time churn prediction dashboard
Advanced ensemble models
Customer retention recommendation system
🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit pull requests.