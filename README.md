** **Exploratory Data Analysis for Telco Customer Churn Rate** **
**Objective**
The primary objective of this analysis is to explore and understand the factors influencing customer churn in the telecommunications sector. By analyzing customer demographics, service usage, and payment methods, the goal is to identify patterns and insights that can help the company reduce churn rates and improve customer retention strategies
**Summary Report**
**Data Overview:**
The dataset consists of 7043 customer records with 21 attributes, including demographic information (e.g., gender, senior citizen status), service details (e.g., tenure, internet service type), and churn status.
Link to dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
**Data Cleaning:**
Missing values in the TotalCharges column were addressed by replacing blanks with zero and converting the data type to float.
The SeniorCitizen column was transformed from binary (0/1) to categorical (‘No’/‘Yes’) for better interpretability.
**Descriptive Statistics:**
Churn Rate: Approximately 26% of customers have churned.
**Customer Demographics:**
Gender distribution and churn rates were analyzed, revealing potential trends in customer retention based on gender.
Tenure Analysis: Customers with longer tenure tend to have lower churn rates.
**Visualizations:**
Count Plots: Visualizations were created to show the distribution of churn across different demographics, such as gender and senior citizen status.
Pie Charts: Represented the percentage of customers who have churned versus those who have not, providing a clear visual of customer retention.
**Key Findings:**
Contract Type: Month-to-month contracts exhibited the highest churn rates compared to one-year and two-year contracts.
Payment Methods: Customers using electronic checks had a higher likelihood of churning, indicating a potential area for intervention.
Service Usage:
Customers with multiple lines tend to have lower churn rates compared to those with a single line or no lines. This suggests that offering bundled services may enhance customer retention.
Internet Service Type:
Customers using fiber optic internet service show a significantly lower churn rate compared to those using DSL or no internet service. This indicates a preference for higher-quality service among customers.
Monthly Charges:
There is a correlation between monthly charges and churn. Customers with higher monthly charges are more likely to churn, suggesting that pricing strategies may need to be reevaluated to retain these customers.
Contract Length:
The analysis shows that customers on one-year contracts have a much lower churn rate compared to those on month-to-month contracts. This highlights the importance of contract length in customer retention strategies.
Payment Method:
Customers who pay via credit card or bank transfer tend to have lower churn rates compared to those using checks. This could indicate that simplifying payment methods may improve retention.
Customer Support:
Customers who utilize tech support services show varied churn rates, with those receiving support being less likely to churn. This suggests that effective customer support can play a crucial role in retention.
