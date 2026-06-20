# Banking Customer Churn Prediction

## 📖 Project Overview

This project focuses on predicting customer churn in the banking sector using machine learning techniques. Customer churn refers to customers closing their accounts or discontinuing banking services.

By analyzing customer demographics, banking behavior, account information, and financial characteristics, the project identifies customers who are likely to leave the bank.

### 🎯 Goal

The goal is to help banks:

- Improve customer retention
- Enhance customer satisfaction
- Reduce revenue loss
- Support data-driven decision-making

---

## 📂 Project Structure

```text
Banking-Customer-Churn-Prediction/
│
├── banking_customer_churn.csv
├── banking_churn_code.ipynb
├── images/
├── requirements.txt
└── README.md
```

| File | Description |
|--------|------------|
| banking_customer_churn.csv | Raw dataset |
| banking_churn_code.ipynb | Data preprocessing, EDA, and model building |
| images/ | Visualizations and plots |
| requirements.txt | Python package dependencies |
| README.md | Project documentation |

---

## 🎯 Project Objectives

- Analyze customer demographics and banking behavior
- Identify key factors influencing customer churn
- Perform Exploratory Data Analysis (EDA)
- Build and evaluate machine learning models
- Recommend strategies to improve customer retention and customer engagement

---

## 📝 Dataset

The dataset contains customer demographic information, account details, banking product usage, and churn status.

### Features Included

#### Customer Information

- Credit Score
- Geography
- Gender
- Age

#### Banking Information

- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Membership Status

#### Financial Information

- Estimated Salary

#### Target Variable

| Exited | Meaning |
|---------|----------|
| 1 | Customer Left the Bank |
| 0 | Customer Retained Banking Services |

---

## 🔍 Key Analysis Performed

### Data Preprocessing

- Data cleaning and transformation
- Handling missing values
- Feature encoding
- Feature selection
- Dataset preparation for machine learning

### Exploratory Data Analysis (EDA)

- Churn distribution analysis
- Age-wise churn analysis
- Geography-wise churn analysis
- Balance distribution analysis
- Product usage analysis
- Active membership analysis
- Credit score analysis
- Feature importance analysis

---

## 📊 Key Factors Affecting Churn

- Age
- Balance
- Credit Score
- Number of Products
- Active Membership Status

---

## 🤖 Machine Learning Models Used

### Decision Tree Classifier

Used for interpretable customer churn prediction.

### Random Forest Classifier

Used to improve prediction accuracy through ensemble learning.

### K-Nearest Neighbors (KNN)

Used for similarity-based classification of customer churn.

### Evaluation Metrics

- Accuracy Score
- F1 Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

---

## 🛠️ Technologies & Libraries

### Programming Language

- Python

### Data Analysis

- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-learn

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/krishna-teja-ayodhya/banking-customer-churn-prediction.git
cd banking-customer-churn-prediction
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
```

#### Windows

```bash
venv\Scripts\activate
```

#### macOS/Linux

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch the Notebook

```bash
jupyter notebook banking_churn_code.ipynb
```

---

## 📈 Key Insights

- Customers from certain geographical regions exhibit higher churn rates.
- Older customers are more likely to leave the bank than younger customers.
- Inactive members show significantly higher churn rates than active members.
- Customers with higher account balances tend to churn more frequently.
- The number of banking products used strongly influences churn behavior.
- Customers with lower credit scores are more likely to leave the bank.
- Long-term customers generally demonstrate higher loyalty and lower churn rates.

---

## 🏆 Results

Among all machine learning models evaluated, the **Random Forest Classifier** achieved the best overall performance.

### Performance Highlights

- Highest predictive performance
- Superior Accuracy and F1-Score
- Lower error metrics compared to other models

### Best Model

🏅 **Random Forest Classifier**

Recommended for banking customer churn prediction.

---

## 💡 Business Recommendations

- Develop targeted retention programs for high-risk customers
- Increase engagement initiatives for inactive members
- Offer personalized banking products based on customer behavior
- Monitor customers with high balances and declining activity
- Improve customer experience for older customer segments
- Strengthen loyalty programs for long-term customers

---

## 🔮 Future Enhancements

- Hyperparameter tuning
- Streamlit deployment
- Real-time churn prediction dashboard
- Advanced ensemble learning techniques
- Automated customer retention recommendation system

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to:

- Fork the repository
- Create a feature branch
- Submit a pull request

---

## ⭐ Support

If you find this project useful, consider giving it a star on GitHub.