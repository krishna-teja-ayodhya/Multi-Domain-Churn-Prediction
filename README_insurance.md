Insurance Customer Churn Prediction
📖 Project Overview

This project focuses on predicting customer churn in the insurance sector using machine learning techniques. Customer churn refers to policyholders discontinuing, cancelling, or not renewing their insurance policies. By analyzing customer demographics, policy information, insurance history, and behavioral attributes, the project identifies customers who are likely to churn.

The goal is to help insurance companies improve customer retention, reduce revenue loss, and make proactive business decisions through data-driven insights.

📂 Project 
├── insurance_customer_churn.csv    # Raw dataset
├── insurance_code.ipynb            # Data preprocessing, EDA, and model building
├── images/                         # Visualizations and plots
├── requirements.txt                # Python package dependencies
└── README.md                       # Project documentation
🎯 Project Objectives
Analyze customer demographics and insurance-related behavior.
Identify factors influencing customer churn.
Perform exploratory data analysis (EDA) to uncover meaningful insights.
Build and evaluate machine learning models for churn prediction.
Recommend strategies to improve customer retention and policy renewal rates.
📝 Dataset

The dataset contains customer demographic information, policy details, insurance history, and churn status.

Features Included
Customer Information
Gender
Age
Region Code
Insurance Information
Driving License Status
Previously Insured
Vehicle Age
Vehicle Damage History
Annual Premium
Policy Information
Policy Sales Channel
Vintage (Customer Association Period)
Target Variable
Response
1 → Customer Churn
0 → Customer Retained

🔍 Key Analysis Performed
Data Preprocessing
Data cleaning and transformation
Handling missing values
Feature encoding
Feature selection
Dataset preparation for machine learning
Exploratory Data Analysis (EDA)
Customer demographic analysis
Insurance history analysis
Vehicle age analysis
Vehicle damage analysis
Premium amount analysis
Regional customer analysis
Customer tenure analysis
Feature Analysis

Key factors affecting churn:

Previous Insurance Status
Vehicle Age
Vehicle Damage History
Annual Premium
Customer Tenure (Vintage)
Regional Factors

🤖 Machine Learning Models Used
Logistic Regression
Random Forest Classifier
Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
Confusion Matrix

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
git clone https://github.com/krishna-teja-ayodhya/insurance-customer-churn-prediction.git
cd insurance-customer-churn-prediction
2. Create & activate a virtual environment
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
3. Install dependencies
pip install -r requirements.txt
4. Launch the notebook
jupyter notebook insurance_code.ipynb
📊 Key Insights
Customer demographics significantly influence churn behavior.
Previously insured customers exhibit different churn patterns compared to newly insured customers.
Vehicle age plays an important role in customer retention.
Customers with prior vehicle damage history show different policy renewal behavior.
Annual premium amounts affect customer decisions regarding policy continuation.
Customer tenure with the company influences churn probability.
Regional factors contribute to variations in customer retention behavior.

🏆 Results

Among all machine learning models evaluated:

Random Forest Classifier
Achieved strong predictive performance
Provided better balance between Precision, Recall, and F1-Score
Demonstrated effective classification through confusion matrix analysis

The Random Forest Classifier showed the best overall performance and is recommended for predicting insurance customer churn.

💡 Business Recommendations
Develop personalized retention strategies for high-risk customers.
Improve engagement with newly insured customers.
Design premium plans tailored to customer behavior.
Focus on customers with specific vehicle profiles and insurance histories.
Implement region-specific customer retention campaigns.
Encourage long-term policy renewals through loyalty benefits.
🔮 Future Enhancements
Hyperparameter tuning
Real-time churn prediction system
Streamlit dashboard deployment
Advanced ensemble learning techniques
Automated policy renewal recommendation system
🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit pull requests.