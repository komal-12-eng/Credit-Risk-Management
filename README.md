# **Credit Risk Prediction Model for Loan Eligibility Assessment**

# **Project Overview**
This project aims to develop a robust model for predicting loan approval categories (P1-P4) based on customer data. The model will assist financial institutions in making informed decisions regarding loan approvals by assessing the credit risk associated with new customers.

## **Goals**
**Predict Loan Approval Category**: Develop a machine learning model to predict the loan approval category (P1-P4) for new customers, indicating different risk levels.

**Aid Loan Approval Decisions**: Use the model to support loan officers in making data-driven loan approval decisions.
## **Data**
**Dataset:**
The project utilizes a dataset containing over 50,000 customer records.
Features: The data includes various features related to demographics, financial information, and loan history.
Target Variable: The target variable is a categorical variable representing loan approval categories (P1-P4).
### **Methodology**
1. **Data Cleaning**
- Missing Values: Addressed missing values using appropriate imputation techniques.
- Data Inconsistencies: Identified and resolved data inconsistencies to ensure data integrity.
2. **Exploratory Data Analysis (EDA)**
- Data Distribution: Performed EDA to understand the distribution of data across different features.
- Feature Relationships: Analyzed relationships between features and the target variable.
3. **Feature Engineering**
- Chi-square Tests: Conducted Chi-square tests to identify significant relationships between categorical features and the target variable.
- VIF Analysis: Used Variance Inflation Factor (VIF) analysis to remove highly correlated numerical features.
- Domain Knowledge: Applied domain knowledge to create new features that could enhance model performance.
4. **Model Building and Evaluation**
- Model Selection: Chose XGBoost as the primary model for its effectiveness in handling tabular data.
- Hyperparameter Tuning: Tuned hyperparameters to optimize model performance.
- Model Evaluation: Evaluated the model on unseen data, achieving an accuracy of 85%.
## **Results**
- Model Accuracy: The final model achieved an accuracy of 85% on unseen data, demonstrating its effectiveness in predicting loan approval categories.
- Business Impact: The model provides a valuable tool for assessing credit risk and aiding loan approval decisions.
