Banking Customer Churn Prediction
📖 Project Overview

This project focuses on predicting customer churn in the banking sector using machine learning techniques. Customer churn refers to customers closing their accounts or discontinuing banking services. By analyzing customer demographics, banking behavior, account information, and financial characteristics, this project identifies customers who are likely to leave the bank.

The goal is to help banks improve customer retention, enhance customer satisfaction, reduce revenue loss, and support data-driven decision-making.

📂 Project Structure
├── banking_customer_churn.csv      # Raw dataset
├── banking_churn_code.ipynb        # Data preprocessing, EDA, and model building
├── images/                         # Visualizations and plots
├── requirements.txt                # Python package dependencies
└── README.md                       # Project documentation
🎯 Project Objectives
Analyze customer demographics and banking behavior.
Identify key factors influencing customer churn.
Perform exploratory data analysis (EDA) to discover meaningful insights.
Build and evaluate machine learning models for churn prediction.
Recommend strategies to improve customer retention and customer engagement.
📝 Dataset

The dataset contains customer demographic information, account details, banking product usage, and churn status.

Features Included
Customer Information
Credit Score
Geography
Gender
Age
Banking Information
Tenure
Balance
Number of Products
Credit Card Status
Active Membership Status
Financial Information
Estimated Salary
Target Variable
Exited
1 → Customer left the bank
0 → Customer retained the banking services

🔍 Key Analysis Performed
Data Preprocessing
Data cleaning and transformation
Handling missing values
Feature encoding
Feature selection
Dataset preparation for machine learning
Exploratory Data Analysis (EDA)
Churn distribution analysis
Age-wise churn analysis
Geography-wise churn analysis
Balance distribution analysis
Product usage analysis
Active membership analysis
Credit score analysis
Feature Importance Analysis

Key features influencing customer churn:

Age
Balance
Credit Score
Number of Products
Active Membership Status

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
git clone https://github.com/krishna-teja-ayodhya/banking-customer-churn-prediction.git
cd banking-customer-churn-prediction
2. Create & activate a virtual environment
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
3. Install dependencies
pip install -r requirements.txt
4. Launch the notebook
jupyter notebook banking_churn_code.ipynb
📊 Key Insights
Customers from certain geographical regions exhibit higher churn rates.
Older customers are more likely to leave the bank than younger customers.
Inactive members show significantly higher churn rates than active members.
Customers with higher account balances tend to churn more frequently.
The number of banking products used strongly influences churn behavior.
Customers with lower credit scores are more likely to leave the bank.
Long-term customers generally demonstrate higher loyalty and lower churn rates.

🏆 Results

Among all machine learning models evaluated:

Random Forest Classifier
Achieved the highest predictive performance
Produced superior accuracy and F1-score
Recorded lower error metrics compared to other models

The Random Forest Classifier demonstrated the best overall performance for predicting customer churn in the banking sector and is recommended for identifying at-risk customers.

💡 Business Recommendations
Develop targeted retention programs for high-risk customers.
Increase engagement initiatives for inactive members.
Offer personalized banking products based on customer behavior.
Monitor customers with high balances and declining activity.
Improve customer experience for older customer segments.
Strengthen loyalty programs for long-term customers.
🔮 Future Enhancements
Hyperparameter tuning
Deployment using Streamlit
Real-time churn prediction dashboard
Advanced ensemble learning techniques
Automated customer retention recommendation system
🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit pull requests.
