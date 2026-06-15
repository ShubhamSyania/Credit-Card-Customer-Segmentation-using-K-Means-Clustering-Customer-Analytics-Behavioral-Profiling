GitHub Repository Description
📊 Credit Card Customer Segmentation using K-Means Clustering – An unsupervised machine learning project that segments 9,000+ credit card customers into distinct behavioral groups using K-Means Clustering, enabling personalized marketing, risk management, customer retention, and data-driven business strategies.
________________________________________
README.md
📊 Credit Card Customer Segmentation using K-Means Clustering
Overview
Understanding customer behavior is essential for financial institutions seeking to improve customer engagement, manage credit risk, and increase profitability.
This project applies K-Means Clustering to segment approximately 9,000 credit card customers based on their spending habits, payment behavior, cash advance usage, and credit utilization patterns. The resulting customer segments provide actionable insights for marketing, customer retention, cross-selling, and risk management strategies.
________________________________________
Business Problem
Traditional customer segmentation often relies on demographic information, which may fail to capture actual customer behavior.
The objective of this project is to identify meaningful customer segments using behavioral data and machine learning techniques to answer questions such as:
•	Which customers are most profitable?
•	Which customers present elevated credit risk?
•	Who should receive loyalty rewards?
•	Which customers need proactive financial assistance?
•	How can marketing campaigns be personalized?
By leveraging clustering techniques, organizations can move toward behavior-driven customer management.
________________________________________
Objectives
•	Perform customer segmentation using K-Means Clustering.
•	Identify behavioral patterns among credit card users.
•	Analyze spending, repayment, and cash advance habits.
•	Develop business recommendations for each customer segment.
•	Support risk management and personalized marketing initiatives.
________________________________________
Dataset Overview
The dataset contains behavioral information for approximately 9,000 active credit card users over a six-month period.
Key Variables
•	BALANCE
•	PURCHASES
•	ONEOFF_PURCHASES
•	INSTALLMENTS_PURCHASES
•	CASH_ADVANCE
•	PURCHASES_FREQUENCY
•	CASH_ADVANCE_FREQUENCY
•	CREDIT_LIMIT
•	PAYMENTS
•	MINIMUM_PAYMENTS
•	PRC_FULL_PAYMENT
•	TENURE
The analysis focuses on customer behavior rather than demographic attributes.
________________________________________
Tech Stack
Programming Language
•	Python
Data Analysis
•	Pandas
•	NumPy
Visualization
•	Matplotlib
•	Seaborn
Machine Learning
•	Scikit-Learn
Clustering Algorithm
•	K-Means Clustering
Data Preprocessing
•	StandardScaler
•	Missing Value Imputation
________________________________________
Data Preprocessing
Several preprocessing steps were performed before clustering:
Missing Value Handling
Missing values in:
•	CREDIT_LIMIT
•	MINIMUM_PAYMENTS
were replaced using median imputation.
Feature Selection
•	Customer ID column removed
•	Behavioral variables retained
Data Normalization
All numerical variables were standardized using:
StandardScaler()
This ensured equal feature contribution during clustering.
________________________________________
Exploratory Data Analysis
Key Correlations Identified
Strong Positive Correlations
Variables	Correlation
PURCHASES & ONEOFF_PURCHASES	0.92
CASH_ADVANCE & CASH_ADVANCE_TRX	0.80
PURCHASES_FREQUENCY & INSTALLMENTS_FREQUENCY	0.86
PURCHASES & PURCHASES_TRX	0.66
Business Insights
•	High spenders tend to make larger one-time purchases.
•	Frequent purchasers are more likely to use installment plans.
•	Customers taking large cash advances often do so repeatedly.
•	Purchase frequency strongly relates to customer engagement levels.
________________________________________
K-Means Clustering Model
The dataset was segmented into 6 customer clusters based on spending behavior, repayment patterns, cash advance usage, and account management habits.
________________________________________
Customer Segments
Cluster 1 – Credit Hoarders
Characteristics:
•	High balances
•	Low spending activity
•	Low full-payment behavior
•	Moderate credit limits
Business Interpretation:
Customers maintain high balances but transact infrequently.
Recommended Action
•	Monitor credit exposure
•	Encourage repayment plans
•	Improve financial engagement
________________________________________
Cluster 2 – Loyal & Responsible Customers
Characteristics:
•	Long tenure
•	Moderate spending
•	Consistent repayment behavior
•	High payment discipline
Business Interpretation:
Reliable and financially disciplined customers.
Recommended Action
•	Loyalty programs
•	Premium offers
•	Relationship-building campaigns
________________________________________
Cluster 3 – High-Value Customers
Characteristics:
•	High purchase volume
•	High transaction frequency
•	Low cash advance usage
•	Strong repayment habits
Business Interpretation:
Most profitable customer segment.
Recommended Action
•	Cashback rewards
•	Premium credit cards
•	Cross-selling opportunities
•	VIP loyalty programs
________________________________________
Cluster 4 – Financially Stressed Users
Characteristics:
•	High cash advance usage
•	Low payment behavior
•	Low full repayment rates
•	Long customer tenure
Business Interpretation:
Potentially risky customers showing signs of financial stress.
Recommended Action
•	Risk monitoring
•	Financial counseling
•	Credit limit controls
________________________________________
Cluster 5 – Dormant & Low Engagement Customers
Characteristics:
•	Low balances
•	Minimal purchases
•	Low card usage
•	Weak repayment patterns
Business Interpretation:
Low-value customers with limited engagement.
Recommended Action
•	Reactivation campaigns
•	Credit education programs
•	Product restructuring
________________________________________
Cluster 6 – Premium Low-Risk Customers
Characteristics:
•	Frequent purchases
•	Strong repayment habits
•	Low cash advance dependency
•	Stable account management
Business Interpretation:
Highly valuable and low-risk segment.
Recommended Action
•	Credit limit enhancements
•	Premium products
•	Retention incentives
________________________________________
Cross-Cluster Business Insights
Repayment Behavior Drives Creditworthiness
Customers with higher full-payment percentages consistently demonstrate lower risk profiles.
Cash Advance Usage Signals Financial Stress
Frequent cash advances often correlate with poor repayment behavior and elevated risk.
Tenure Alone Is Not Sufficient
Long-standing customers can still represent either high-value or high-risk segments.
Purchase Frequency Indicates Relationship Strength
Frequent purchasers with strong repayment habits represent the most valuable customers.
________________________________________
Strategic Business Recommendations
Dynamic Limit Management System
Adjust credit limits dynamically based on:
•	Repayment behavior
•	Spending habits
•	Cash advance dependency
Value-Based Cross-Selling
Target premium customer segments with:
•	Premium credit cards
•	Buy Now Pay Later (BNPL)
•	Investment products
•	Savings accounts
AI-Based Credit Wellness Coach
Provide personalized financial guidance for at-risk customers showing:
•	Repayment irregularities
•	Excessive cash advances
•	Signs of financial stress
Gamified Rewards Program
Increase engagement through:
•	Transaction milestones
•	Cashback rewards
•	Fee waivers
•	Loyalty tiers
Cluster-Driven CRM Strategy
Integrate customer segments directly into CRM systems for personalized campaigns and real-time segmentation updates.
________________________________________
Project Structure
Credit-Card-Customer-Segmentation/
│
├── data/
├── notebooks/
├── reports/
├── visualizations/
├── models/
├── README.md
├── requirements.txt
└── Customer_Segmentation_KMeans.ipynb
________________________________________
Key Outcomes
✅ Segmented 9,000+ customers into 6 meaningful behavioral groups
✅ Identified high-value and high-risk customer profiles
✅ Developed actionable business strategies for each segment
✅ Demonstrated the practical application of unsupervised learning in financial services
✅ Enabled data-driven decision-making for marketing, retention, and risk management
________________________________________
Business Impact
The project demonstrates how machine learning-based customer segmentation can help financial institutions:
•	Improve customer retention
•	Reduce credit risk
•	Increase cross-sell opportunities
•	Personalize marketing campaigns
•	Enhance customer lifetime value
•	Optimize credit portfolio management
________________________________________
Author
Shubham Rakesh Syania
PGDM – Research & Business Analytics
Welingkar Institute of Management Development and Research
⭐ If you found this project useful, consider giving it a star on GitHub! 🚀
