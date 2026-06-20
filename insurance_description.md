# Insurance Customer Churn Prediction

## Project Overview:

The aim of this data science project is to analyze customer demographics, policy-related information, insurance history, and behavioral attributes to predict whether a customer is likely to churn. Customer churn in the insurance sector refers to policyholders discontinuing, cancelling, or not renewing their insurance policies. By identifying customers who are at risk of churn, insurance companies can implement proactive retention strategies, improve customer satisfaction, and minimize revenue loss.

## Data Dictionary:

Here is a data dictionary describing the variables used in this project:

| Variable | Description |
|-----------|------------|
| id | Unique customer identifier |
| Gender | Customer's gender |
| Age | Customer's age |
| Driving_License | Whether the customer possesses a valid driving license (1 = Yes, 0 = No) |
| Region_Code | Customer's regional location code |
| Previously_Insured | Whether the customer was previously insured (1 = Yes, 0 = No) |
| Vehicle_Age | Age category of the customer's vehicle |
| Vehicle_Damage | Whether the vehicle has been damaged previously (Yes/No) |
| Annual_Premium | Annual premium amount paid by the customer |
| Policy_Sales_Channel | Channel through which the policy was sold |
| Vintage | Number of days the customer has been associated with the company |
| Response | Customer churn status (1 = Churn, 0 = Non-Churn) |

## Conclusion:

From the exploratory data analysis, several insights have been derived:

- Customer demographics and insurance-related attributes significantly influence churn behavior.
- Customers with previous insurance history exhibit different churn patterns compared to newly insured customers.
- Vehicle age and vehicle damage history play an important role in determining customer retention.
- Annual premium amount impacts customer decisions regarding policy continuation.
- Customer tenure with the company influences the likelihood of churn.
- Regional factors contribute to variations in customer retention behavior.
- Multiple factors collectively affect churn, making machine learning techniques effective for identifying at-risk customers.

Machine learning models including Logistic Regression and Random Forest Classifier were employed in this project. Model performance was evaluated using metrics such as Accuracy, Precision, Recall, and F1-Score.

The Random Forest Classifier demonstrated strong overall performance and provided better balance between precision, recall, and F1-score compared to Logistic Regression. The confusion matrix analysis indicated effective classification performance, making Random Forest a reliable model for churn prediction.

Therefore, the Random Forest Classifier is recommended as a suitable model for predicting customer churn in the insurance sector. The model can help insurance companies proactively identify at-risk customers, improve retention strategies, and enhance long-term customer relationships.