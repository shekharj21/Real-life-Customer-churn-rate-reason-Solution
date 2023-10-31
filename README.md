# Real-life-Customer-churn-rate-reason-Solution
We have been hired by Lu's Communication to find the reasons of customers churn rate and the potential solutions to overcome it. Making a report for non technical people for thier better understanding.


You’ve been hired by Lu’s Communications which is a UK based telecom company that offers the following to its customers:
• Internet
• Landline
• TV

Lu’s Communications has a huge problem with churn (loss of customers to competition). It is expensive to acquire new customers and therefore retaining existing customers is much more appealing.
Lu’s communications would like to use a targeted approach to identify in advance customers who are likely to churn, which can be then targeted with special programs or incentives. This approach can bring in a huge loss if churn predictions are inaccurate, as money would be wasted to incentivise customers who would have stayed anyway.
Lu’s communications have hired you to help them with this problem.
You are expected to write a report to management at Lu’s communications; these are “non-technical” people.

You should also cover the following steps:
1. Data collection
• Lu’s communication has already provided the data (data.csv). However, this data is not perfect: it may contain outliers, missing values and irrelevant (not related to churn) information

3. Data preparation
• Review the structure of the dataset
• Peek into the data, summarise your data and get a snapshot of all the features
• Transform the data into a format ready to apply with the algorithms and modelling

5. Perform EDA (exploratory data analysis)
• Understand the data and its applicability to the problem
• Understand how the data and its features are related
• Evaluate the presence of outliers and their effects

7. Develop an initial hypothesis
• Based on the EDA, develop an initial hypothesis.

9. Data pre-processing
• Pre-process that data in an appropriate way. This can include (but not limited to):
i. Dealing with outliers
ii. Dealing with missing values


DATASET INFORMATION :

The dataset consist of 7350 observations.
The features of the dataset are:
customer_id: Every customer is given a unique ID
gender: Whether the customer is a male or a female
location: Location of the customer
partner: Whether the customer has a partner or not (1=Yes, 0=No)
dependents: Whether the customer has dependents or not (1=Yes, 0=No)
senior: Whether the customer is a senior citizen or not (1=Yes, 0=No)
Tenure: Number of years the customer has stayed with the company. Lu’s communication offers a loyalty scheme; this scheme gives 2% discount on the monthly cost for each year (up to 25 years) the customer remains with the company
monthly_cost: The amount charged to the customer monthly
package: Packages Lu’s communication offers. See table below for more information
survey: Score given by customers on the customer service (0=``Poor”, 10=``Excellent”)
Class: Whether the customer churned or not


