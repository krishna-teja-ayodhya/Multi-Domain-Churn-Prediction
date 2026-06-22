**Multi-Domain Customer Churn Prediction System Using Machine Learning
📖 Project Overview**

Multi-Domain Customer Churn Prediction System is a machine learning-based solution designed to predict customer churn across multiple industries, including Telecommunications, Banking, and Insurance.

Traditional churn prediction systems are typically developed for a single industry, limiting their applicability. This project introduces a unified framework that analyzes customer behavior, service usage patterns, financial attributes, and domain-specific characteristics to identify customers who are likely to discontinue services.

By leveraging machine learning algorithms, the system helps organizations proactively identify at-risk customers, improve retention strategies, reduce revenue loss, and enhance customer satisfaction.

**🎯 Project Objectives**
Develop a unified churn prediction framework for multiple business domains.
Analyze customer behavior and engagement patterns across industries.
Identify key factors contributing to customer churn.
Perform Exploratory Data Analysis (EDA) to uncover actionable insights.
Build and evaluate machine learning models for churn prediction.
Compare churn drivers across Telecom, Banking, and Insurance sectors.
Support data-driven customer retention strategies.

**🏢 Supported Domains**
**📡 Telecom Customer Churn Prediction**
Predicts customer attrition based on:

Customer demographics
Service subscriptions
Internet services
Contract type
Billing information
Customer tenure

**🏦 Banking Customer Churn Prediction**
Predicts customer attrition based on:

Credit score
Account balance
Active membership status
Banking product usage
Customer tenure
Financial attributes

**🛡️ Insurance Customer Churn Prediction**
Predicts policyholder churn based on:

Insurance history
Vehicle information
Annual premium
Policy sales channels
Customer demographics
Policy tenure

**📂 Project Structure**
Multi-Domain-Customer-Churn-Prediction/
│
├── telecom_code.ipynb
├── banking_churn_code.ipynb
├── insurance_code.ipynb
│
├── telecom_description.md
├── banking_description.md
├── insurance_description.md
│
├── README.md
│
└── datasets/
    ├── telecom_customer_churn.csv
    ├── banking_customer_churn.csv
    └── insurance_customer_churn.csv
    
**🔍 Project Workflow
1. Data Collection**
Telecom Customer Dataset
Banking Customer Dataset
Insurance Customer Dataset
**2. Data Preprocessing**
Data Cleaning
Missing Value Handling
Feature Encoding
Feature Scaling
Feature Selection
**3. Exploratory Data Analysis (EDA)**
Customer Demographics Analysis
Churn Distribution Analysis
Service Usage Analysis
Financial Behavior Analysis
Customer Retention Analysis
**4. Machine Learning Model Development**
The following models were implemented and evaluated:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
**5. Model Evaluation**
Performance measured using:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
**🛠️ Technologies Used**
**Programming Language**
Python
**Data Analysis**
Pandas
NumPy
**Data Visualization**
Matplotlib
Seaborn
Machine Learning
Scikit-learn
**Development Environment**
Jupyter Notebook
Google Colab

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/krishna-teja-ayodhya/multi-domain-customer-churn-prediction.git
cd multi-domain-customer-churn-prediction
```

### 2. Create & activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch the notebooks

#### Telecom Churn Prediction

```bash
jupyter notebook telecom_code.ipynb
```

#### Banking Churn Prediction

```bash
jupyter notebook banking_churn_code.ipynb
```

#### Insurance Churn Prediction

```bash
jupyter notebook insurance_code.ipynb
```
