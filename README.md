Fraud Detection & Transaction Risk Analysis
Tools: PostgreSQL | Power BI
Project Type: Fraud Analytics | Transaction Risk
Focus: Fraud Detection | Risk Concentration | Transaction Analysis
________________________________________
Project Overview
Fraudulent transactions can create financial losses and increase risk for businesses, making it important to understand where fraudulent activity is concentrated and which transaction characteristics are associated with higher fraud risk.
In this project, I used PostgreSQL and Power BI to analyze 594,643 transactions and investigate the patterns associated with fraudulent activity.
Rather than looking at fraud as one overall percentage, I broke the analysis down into transaction categories, merchants, customers, and transaction-value ranges to understand where fraud is concentrated and which areas may require closer monitoring.
________________________________________
Goal
To understand the main patterns in fraudulent transaction activity, identify areas of higher fraud risk, and provide actionable recommendations that can help the business prioritize fraud monitoring and investigation.
________________________________________
Business Questions
The analysis focused on five main questions:
1. How serious is the fraud problem?
•	How many transactions are fraudulent?
•	What percentage of all transactions are fraudulent?
•	What transaction value is associated with fraudulent transactions?
2. Which transaction categories have the highest fraud risk?
•	How does fraudulent activity vary across transaction categories?
•	Which categories have the highest fraud volume?
•	Which categories have the highest fraud rates?
•	Which categories are associated with the highest fraudulent transaction value?
3. Which merchants show the highest fraud risk?
•	Which merchants have the highest number of fraudulent transactions?
•	Which merchants have the highest fraud rates?
•	Which merchants are associated with the highest fraudulent transaction value?
4. Which customers show repeated fraudulent activity?
•	Which customers are associated with repeated transactions labeled as fraudulent?
•	Which customers are associated with higher fraudulent transaction value?
•	Do repeated fraudulent activities appear concentrated in particular categories?
5. How does fraud risk change with transaction amount?
•	How does fraud rate change across transaction-value ranges?
•	Which transaction-value ranges contain the highest fraud rates?
•	How does fraudulent transaction value change across the different ranges?
________________________________________
Key Findings
Fraud Represents 1.21% of All Transactions
The dataset contains 594,643 transactions, of which 7,200 were labeled fraudulent.
This represents a 1.21% fraud rate, with approximately $3.82M in fraudulent transaction value.
The overall rate provides a measure of the scale of the problem, but the analysis also shows that fraudulent activity is not evenly distributed across the dataset.
________________________________________
Fraud Risk Differs Across Transaction Categories
Fraud activity varies considerably across transaction categories.
Leisure recorded the highest fraud rate, while Travel was associated with the highest fraudulent transaction value. Sports & Toys recorded the highest number of fraudulent transactions.
This shows why fraud monitoring should consider more than one measure. A category can have a high fraud rate without having the largest fraud volume or financial value.
The analysis also identified merchants associated with high fraudulent activity within categories such as Leisure, Travel, and Sports & Toys.
________________________________________
Fraud Risk Is Concentrated Across Certain Merchants
Different merchants show different patterns of fraud activity.
•	M1294758098 recorded the highest fraud rate at approximately 96.34%.
•	M732195782 was associated with the highest fraudulent transaction value at approximately $1.35M.
•	M480139044 recorded the highest number of fraudulent transactions with 1,634 cases.
These results show that merchant risk should be examined using fraud rate, fraud volume, and fraudulent transaction value rather than relying on one metric alone.
________________________________________
Some Customers Are Associated With Repeated Fraudulent Activity
The analysis identified customers associated with repeated transactions labeled as fraudulent.
Some repeated activity was concentrated in categories such as Sports & Toys and Travel, while several customers were also associated with relatively high fraudulent transaction values.
This suggests that customer-level behavioral patterns can provide another useful signal for fraud monitoring and investigation.
The analysis does not establish that these customers committed fraud; it identifies customers associated with transactions labeled as fraudulent in the dataset.
________________________________________
Fraud Rate Rises Sharply With Transaction Amount
One of the strongest patterns identified in the analysis is the relationship between transaction value and fraud rate.
Transactions below $100 had a much lower fraud rate, while transactions above $300 showed substantially higher fraud rates.
The higher-value ranges recorded extremely high fraud rates, with several ranges above 90%.
This makes transaction value an important risk indicator in this dataset. However, the analysis shows an association between transaction amount and fraud; it does not establish that a higher transaction amount causes fraud.
________________________________________
Recommendations
Based on the analysis, I recommend:
•	Use predictive analytics and real-time fraud monitoring to identify high-risk transactions early and prioritize suspicious activity for investigation.
•	Apply additional screening or monitoring to higher-value transactions, particularly transactions above approximately $300, because of the substantially higher fraud rates observed in the dataset.
•	Prioritize merchants with unusually high fraud rates, fraud volumes, or fraudulent transaction values for further investigation.
•	Strengthen monitoring within categories such as Leisure, Travel, and Sports & Toys, where significant fraudulent activity was observed.
•	Use behavioral analytics to identify customers associated with repeated suspicious transaction patterns and prioritize them for review.
•	Combine transaction amount, merchant activity, category, customer behavior, and other available risk signals rather than relying on a single indicator.
•	Monitor fraud outcomes regularly to determine whether fraud-prevention measures are reducing financial losses and fraudulent activity.
________________________________________
How Success Could Be Measured
The business could monitor:
•	Fraud rate
•	Fraudulent transaction value
•	Financial losses associated with confirmed fraud
•	Number of high-risk transactions identified
•	Fraud detection precision / false-positive rate after a production fraud-detection system is implemented
A reduction in fraudulent transaction value and overall fraud rate, while maintaining effective detection, would indicate whether fraud-prevention measures are having the intended effect.
________________________________________
Dashboard
The dashboard focus on:
•	Overall fraud severity
•	Fraud concentration by category
•	Merchant-level fraud risk
•	Customer-level repeated fraudulent activity
•	The relationship between transaction amount and fraud risk
The dashboard is designed to answer one question quickly:
Where is fraud concentrated, which transaction patterns are associated with higher risk, and where should the business prioritize monitoring and investigation?
________________________________________
Process
•	I prepared and explored the fraud transaction dataset.
•	I used PostgreSQL to calculate overall fraud metrics.
•	I analyzed fraudulent activity across transaction categories.
•	I examined merchant-level fraud volume, rate, and transaction value.
•	I investigated customers associated with repeated fraudulent transactions.
•	I analyzed how fraud rates change across transaction-value ranges.
•	I identified the strongest patterns from the SQL analysis.
•	I translated the findings into business-focused recommendations.
•	I used the findings to build a Power BI dashboard focused on fraud risk and investigation priorities.
________________________________________
Technical Approach
PostgreSQL
The SQL analysis used:
•	Aggregate Functions
•	CASE Statements
•	Filtering
•	GROUP BY
•	Conditional Calculations
•	Fraud Rate Calculations
•	Transaction-Value Segmentation
•	Category Analysis
•	Merchant Analysis
•	Customer Analysis
The SQL analysis was used to move from the overall fraud problem into more specific questions about where fraudulent activity is concentrated and which transaction characteristics are associated with higher fraud risk.
Power BI
The dashboard will use:
•	KPI Cards
•	Fraud Category Analysis
•	Merchant Risk Analysis
•	Customer Risk Analysis
•	Transaction-Value Analysis
•	Interactive Filtering
•	Data Visualization
•	Business-Focused Data Storytelling
________________________________________
Dataset
The dataset contains 594,643 transaction records with information including:
•	Transaction step
•	Customer
•	Age category
•	Gender
•	Merchant
•	Transaction category
•	Transaction amount
•	Fraud label
________________________________________
Connect With Me
Winner Donald
📧 winnerdonald158@gmail.com
💻 GitHub
🔗 LinkedIn: www.linkedin.com/in/winner-donald
📍 Abuja, Nigeria
