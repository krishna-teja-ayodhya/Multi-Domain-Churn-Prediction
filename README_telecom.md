# Telecom Customer Churn Prediction

## 📖 Project Overview

This project focuses on predicting customer churn in the telecommunications industry using machine learning techniques. Customer churn refers to customers discontinuing a company's services.

By analyzing customer demographics, service subscriptions, tenure, contract information, and billing details, the project identifies customers who are likely to leave the company.

### 🎯 Goal

The goal is to help telecom companies:

- Improve customer retention
- Reduce revenue loss
- Make data-driven business decisions
- Identify at-risk customers early

---

## 📂 Project Structure

```text
Telecom-Customer-Churn-Prediction/
│
├── telecom_customer_churn.csv
├── telecom_code.ipynb
├── images/
├── requirements.txt
└── README.md
```

| File | Description |
|--------|------------|
| telecom_customer_churn.csv | Raw dataset |
| telecom_code.ipynb | Data preprocessing, EDA, and model building |
| images/ | Visualizations and plots |
| requirements.txt | Python package dependencies |
| README.md | Project documentation |

---

## 🎯 Project Objectives

- Analyze customer behavior and service usage patterns
- Identify factors influencing customer churn
- Perform Exploratory Data Analysis (EDA)
- Build and evaluate machine learning models
- Recommend strategies to improve customer retention

---

## 📝 Dataset

The dataset contains customer demographic information, service details, contract information, billing data, and churn status.

### Features Included

#### Customer Demographics

- Gender
- Senior Citizen
- Partner
- Dependents

#### Service Information

- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies

#### Contract Information

- Contract Type
- Paperless Billing
- Payment Method

#### Billing Information

- Monthly Charges
- Total Charges

#### Target Variable

| Churn | Meaning |
|--------|----------|
| Yes | Customer Left the Service |
| No | Customer Retained the Service |

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
- Customer demographic analysis
- Service-wise churn analysis
- Contract type analysis
- Billing analysis
- Tenure analysis
- Feature importance analysis

---

## 📊 Key Factors Affecting Churn

- Tenure
- Contract Type
- Monthly Charges
- Total Charges

---

## 🤖 Machine Learning Models Used

### Decision Tree Classifier

Used for interpretable customer churn prediction.

### Random Forest Classifier

Used to improve prediction performance through ensemble learning.

### K-Nearest Neighbors (KNN)

Used for similarity-based customer classification.

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
git clone https://github.com/krishna-teja-ayodhya/telecom-customer-churn-prediction.git
cd telecom-customer-churn-prediction
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
jupyter notebook telecom_code.ipynb
```

---

## 📈 Key Insights

- Customers with shorter tenure are more likely to churn.
- Month-to-month contracts show higher churn rates than long-term contracts.
- Customers with higher monthly charges tend to churn more frequently.
- Customers without partners or dependents exhibit higher churn behavior.
- Streaming service users generally demonstrate better retention.

---

## 🏆 Results

Among all machine learning models evaluated, the **Random Forest Classifier** achieved the best overall performance.

### Performance Highlights

- Accuracy: **82%**
- Highest F1 Score
- Lowest MSE and MAE

### Best Model

🏅 **Random Forest Classifier**

Recommended for telecom customer churn prediction.

---

## 💡 Business Recommendations

- Encourage long-term contracts through incentives
- Develop retention programs for new customers
- Offer personalized plans for high-risk customers
- Improve engagement for month-to-month subscribers
- Monitor customers with high monthly charges and low tenure

---

## 🔮 Future Enhancements

- Hyperparameter tuning
- Streamlit deployment
- Real-time churn prediction dashboard
- Advanced ensemble learning models
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