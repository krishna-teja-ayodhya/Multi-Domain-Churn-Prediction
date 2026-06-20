# Insurance Customer Churn Prediction

## 📖 Project Overview

This project focuses on predicting customer churn in the insurance sector using machine learning techniques. Customer churn refers to policyholders discontinuing, cancelling, or not renewing their insurance policies.

By analyzing customer demographics, policy information, insurance history, and behavioral attributes, the project identifies customers who are likely to churn.

### 🎯 Goal

The goal is to help insurance companies:

- Improve customer retention
- Reduce revenue loss
- Make proactive business decisions
- Generate data-driven insights

---

## 📂 Project Structure

```text
Insurance-Customer-Churn-Prediction/
│
├── insurance_customer_churn.csv
├── insurance_code.ipynb
├── images/
├── requirements.txt
└── README.md
```

| File | Description |
|--------|------------|
| insurance_customer_churn.csv | Raw dataset |
| insurance_code.ipynb | Data preprocessing, EDA, and model building |
| images/ | Visualizations and plots |
| requirements.txt | Python package dependencies |
| README.md | Project documentation |

---

## 🎯 Project Objectives

- Analyze customer demographics and insurance-related behavior
- Identify factors influencing customer churn
- Perform Exploratory Data Analysis (EDA)
- Build and evaluate machine learning models
- Recommend strategies to improve customer retention and policy renewal rates

---

## 📝 Dataset

The dataset contains customer demographic information, policy details, insurance history, and churn status.

### Features Included

#### Customer Information

- Gender
- Age
- Region Code

#### Insurance Information

- Driving License Status
- Previously Insured
- Vehicle Age
- Vehicle Damage History
- Annual Premium

#### Policy Information

- Policy Sales Channel
- Vintage (Customer Association Period)

#### Target Variable

| Response | Meaning |
|-----------|----------|
| 1 | Customer Churn |
| 0 | Customer Retained |

---

## 🔍 Key Analysis Performed

### Data Preprocessing

- Data cleaning and transformation
- Handling missing values
- Feature encoding
- Feature selection
- Dataset preparation for machine learning

### Exploratory Data Analysis (EDA)

- Customer demographic analysis
- Insurance history analysis
- Vehicle age analysis
- Vehicle damage analysis
- Premium amount analysis
- Regional customer analysis
- Customer tenure analysis
- Feature relationship analysis

---

## 📊 Key Factors Affecting Churn

- Previous Insurance Status
- Vehicle Age
- Vehicle Damage History
- Annual Premium
- Customer Tenure (Vintage)
- Regional Factors

---

## 🤖 Machine Learning Models Used

### Logistic Regression

Used as a baseline classification model for churn prediction.

### Random Forest Classifier

Used to improve predictive performance through ensemble learning.

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

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
git clone https://github.com/krishna-teja-ayodhya/insurance-customer-churn-prediction.git
cd insurance-customer-churn-prediction
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
jupyter notebook insurance_code.ipynb
```

---

## 📈 Key Insights

- Customer demographics significantly influence churn behavior.
- Previously insured customers exhibit different churn patterns compared to newly insured customers.
- Vehicle age plays an important role in customer retention.
- Customers with prior vehicle damage history show different policy renewal behavior.
- Annual premium amounts affect customer decisions regarding policy continuation.
- Customer tenure influences churn probability.
- Regional factors contribute to customer retention variations.

---

## 🏆 Results

Among all machine learning models evaluated, the **Random Forest Classifier** achieved the strongest performance.

### Performance Highlights

- Strong predictive accuracy
- Better balance between Precision, Recall, and F1-Score
- Effective classification through confusion matrix analysis

### Best Model

🏅 **Random Forest Classifier**

Recommended for insurance customer churn prediction.

---

## 💡 Business Recommendations

- Develop personalized retention strategies for high-risk customers
- Improve engagement with newly insured customers
- Design premium plans tailored to customer behavior
- Focus on customers with specific vehicle profiles and insurance histories
- Implement region-specific retention campaigns
- Encourage long-term policy renewals through loyalty benefits

---

## 🔮 Future Enhancements

- Hyperparameter tuning
- Real-time churn prediction system
- Streamlit dashboard deployment
- Advanced ensemble learning techniques
- Automated policy renewal recommendation system

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