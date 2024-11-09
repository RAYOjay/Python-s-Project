**DATA SYNOPSIS**

You have been provided with a dataset containing key demographic and financial details of bank customers. This dataset includes fields such as customer information (e.g., Name, Customer ID), financial performance indicators (e.g., Credit Score, Balance), and customer engagement metrics (e.g., Tenure, Number of Products, IsActiveMember). Additionally, it includes whether the customer has exited the bank or remains active. Your goal is to analyze the dataset to gain insights into customer behavior, financial standing, and engagement patterns

**PROBLEM STATEMENT**
 
* The financial insistute is looking forward to:
- Determine  customers status in the bank with active accounts or not
- provide demographic, financial, and engagement data of bank customers

#
## Approach/Solution
- Analyze Customer Demographics
- Understand Financial Performance
- Evaluate Engagement Metrics
- identify Exited vs Active Customers:
- Gain Insights for Predictive Analysis
- identify trends and patterns in customer engagement
- highlighting potential areas for business improvement
- 

## Objective
- Demographic Analysis
- Customer Engagement Patterns
- Financial Performance
- Exited Customers Analysis
- Customer Segmentation

**Data Dictionary**
- Field	       Description
CustomerId	   A unique identifier for each customer
Surname	       The customer's last name
CreditScore	   A numerical value representing the customer's credit score
Geography	   The country where the customer resides (France, Spain or Germany)
Gender	       The customer's gender (Male or Female)
Age	           The customer's age
Tenure	       The number of years the customer has been with the bank
Balance	       The customer's account balance
NumOfProducts	The number of bank products the customer uses (e.g., savings account, credit card)
HasCrCard	    Whether the customer has a credit card (1 = yes, 0 = no)
IsActiveMember	Whether the customer is an active member (1 = yes, 0 = no)
EstimatedSalary	The estimated salary of the customer
Exited	Whether the customer has churned (1 = yes, 0 = no)


### Observations
* Customer Tenure is  related to customer engagement. Longer-tenured customers may more products, be more active, and have higher balances and credit scores.
Customer Segmentation based on tenure helped identify groups with different behaviors targeted at  long-term customers for loyalty programs or tailor offerings for newer customers.
By performing these analyses, it helps understands customer financial patterns in greater detail and uncover trends related to demographics, balances, credit scores, and salaries. These insights are valuable for targeting different customer groups with customized financial products or services.
By analyzing customer segments and their churn rates, you can derive insights on which segments are more likely to exit and take actions accordingly, such as:

High churn rate: Implement retention strategies for high-churn segments.
Low churn rate: Focus on maintaining relationships and rewarding loyalty.
This code will help you identify distinct customer segments, analyze their characteristics, and take data-driven actions for improving retention and customer engagement.