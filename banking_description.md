# Banking Customer Churn Prediction

## Project Overview:

The aim of this data science project is to analyze customer demographics, banking behavior, account information, and financial characteristics to predict whether a customer is likely to leave the bank. Customer churn refers to customers closing their accounts or discontinuing banking services. By identifying customers at risk of churn, banks can implement targeted retention strategies, improve customer satisfaction, and reduce revenue loss.

## Data Dictionary:

Here is a data dictionary describing the variables used in this project:

| Variable | Description |
|-----------|------------|
| CreditScore | Customer's credit score |
| Geography | Customer's country/location (France, Germany, Spain) |
| Gender | Customer's gender |
| Age | Customer's age |
| Tenure | Number of years the customer has been with the bank |
| Balance | Customer's account balance |
| NumOfProducts | Number of banking products used by the customer |
| HasCrCard | Whether the customer has a credit card (1 = Yes, 0 = No) |
| IsActiveMember | Whether the customer is an active member (1 = Yes, 0 = No) |
| EstimatedSalary | Customer's estimated annual salary |
| Exited | Whether the customer left the bank or not (1 = Yes, 0 = No) |

## Conclusion:

From the exploratory data analysis, several insights have been derived:

- Customers belonging to certain geographical regions exhibit higher churn rates compared to others.
- Older customers tend to leave the bank more frequently than younger customers.
- Inactive members show a significantly higher churn rate than active members.
- Customers with higher account balances are more likely to churn compared to those with lower balances.
- The number of banking products used by a customer has a strong influence on churn behavior.
- Credit score plays an important role, with customers having lower credit scores showing a greater tendency to leave.
- Customers who maintain longer relationships with the bank generally exhibit lower churn rates.
- Feature importance analysis identified Age, Balance, Credit Score, Number of Products, and Active Membership status as key factors influencing customer churn.

Machine learning models including Decision Tree Classifier, Random Forest Classifier, and K-Nearest Neighbors (KNN) Classifier were employed in this project. The Random Forest Classifier achieved the highest predictive performance with superior accuracy, F1-score, and lower error metrics compared to the other models.

Therefore, the Random Forest Classifier is recommended as a suitable model for predicting customer churn in the banking sector. The model can assist banks in proactively identifying at-risk customers and implementing effective retention strategies.