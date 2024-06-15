**Customer Churn Analysis**
This project analyzes customer churn rate to identify factors that influence churn. The final product is a dashboard that provides insights into customer churn.

**Data**
The data used for this project is a customer dataset originally provided in a Microsoft Excel workbook containing two worksheets:

**1. Databel - Aggregate**

This worksheet contains aggregated customer data at a group level. Here's a breakdown of the columns:

Subscription Features:
Unlimited Data Plan (Yes/No)
Customer Demographics:
Account Length (in months)
Intl Active (Yes/No) - Indicates if international calling is active
Intl Plan (Plan type for international calls)
State (Customer location)
Gender
Age
Under 30 (Derived from Age - Yes/No)
Senior (Derived from Age - Yes/No)
Group (Customer group affiliation)
Customer Service:
Avg Customer Service Calls (Average number of calls per month)
Financial Information:
Demographics (Textual description of demographics - might be redundant)
Contract Type
Payment Method
Churn Category
Churn Reason
Total Customers (Total customers in the group)
Churned Customers (Number of churned customers in the group)
Avg Monthly Charges (Average monthly charges per customer)
Avg Extra International Charges (Average extra charges for international calls)
Avg Extra Data Charges (Average extra charges for data usage)
Avg Monthly GB Download (Average monthly data downloaded in GB)

**2. Databel - Customer**

This worksheet contains detailed data for individual customers. Here's a breakdown of the columns:

Customer Identification:
Customer ID (Unique identifier for each customer)
Churn Label (Yes/No - indicates if the customer churned)
Account Details:
Account Length (in months)
Call Activity:
Local Calls (Number of local calls made)
Local Mins (Total minutes spent on local calls)
Intl Calls (Number of international calls made)
Intl Mins (Total minutes spent on international calls)
Intl Active (Yes/No) - Indicates if international calling is active (matches aggregate data)
Intl Plan (Plan type for international calls - matches aggregate data)
Data Usage:
Extra International Charges
Avg Monthly GB Download
Unlimited Data Plan (Yes/No - matches aggregate data)
Extra Data Charges
Customer Demographics:
State (Customer location - matches aggregate data)
Phone Number
Gender
Age
Under 30 (Derived from Age - Yes/No - matches aggregate data)
Senior (Derived from Age - Yes/No - matches aggregate data)
Group (Customer group affiliation - matches aggregate data)
Number of Customers in Group (Number of customers in the group the customer belongs to)
Service and Billing:
Device Protection & Online Backup (Yes/No)
Contract Type
Payment Method
Monthly Charge
Total Charges
Churn Information:
Churn Category
Churn Reason

**Data Source:** 
Dataset is fictional and provided by **Datacamp**

**Dashboard**
The dashboard  shows the following:

Total Customers : The total number of customers.
Churned Customers: The number of customers who churned.
Churn Rate: The churn rate as a percentage.
Churn by Demographics: A breakdown of churn rate by demographics, including age group, international plan, and state.
Churn Reasons: The most common reasons for churn, including reasons related to competitor offers, service dissatisfaction, and price.
Age Group Analysis: A chart showing the churn rate for different age groups.
Competitor Churn Analysis: A chart showing the churn rate for customers who switched to a competitor.
Consumption Churn: A chart showing the churn rate for customers with different levels of data consumption.

**Future Work**
The following are some suggestions for future work:

Analyze the reasons for churn in more detail. For example, you could look at the reasons for churn by customer segment or by churn time.
Develop a churn prediction model. This model could be used to identify customers who are at risk of churning and to target them with retention campaigns.
Implement the findings from this analysis to create targeted retention campaigns.
