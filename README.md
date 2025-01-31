# **Telecom Customer Churn Data Analysis**
In this project, I analyzed a Telecom company’s churn dataset, which includes customer activity data and a churn label indicating whether a customer canceled their subscription. The goal was to identify key factors contributing to customer churn and provide recommendations to improve retention

**Objectives of Data Analysis:**
- Develop an understanding of the cause of customer churn.
- Find the factors that increase customer churn.
- Recommendations to retain the most valuable customer.

**Data Overview:**
- Total Rows: 3,333
- Total Columns: 21
- Target Variable: churn (boolean)

**Key Features:**
- Numerical: account length, number vmail messages, customer service calls.
- Categorical: state, international plan, voice mail plan.

**Steps for the Data Analysis:**
1. Importing Libraries
2. Importing Dataset
3. Exploring the Dataset
4. Checking Missing and Duplicates Values
5. Analyzing the Data
6. Interpretation and Insights
7. Recommendations

**Key Findings:**
1. Almost 15% of customers have churned whic indicates that churn is a relatively infrequent event.
2. California (CA), New Jersey (NJ), Texas (TX), Maryland (MD), and South Carolina (SC) have the highest percentage churn among all states.
3. There is no major difference in account length between churned and non-churned customers, meaning account length alone is not a strong predictor of customer churn.
4. Higher Churned Percentage for customers with international plan.
5. Churn is higher among customers who do not have a voicemail plan. This suggests that offering voicemail plans could help reduce churn.
6. Customers with more customer service calls tend to churn more, suggesting dissatisfaction with service. Frequent contact with customer service is a warning sign for potential churn, but also emphasizes that there are other underlying factors driving customers away even without service calls.

**Recommendations:**

**1. Priority Support in High-Churn States:**
- Provide customized discounts or special plans for customers in the high-churn states to reduce churn.
- Study competitors in the high-churn states and match or beat their offers.

**2. Revise International Plans:**
- Offer competitive pricing and packages for international plans to reduce dissatisfaction.
- Conduct surveys or outreach programs to understand why customers with international plans are leaving.

**3. Leverage Voicemail Plans:**
- Offer discounts or incentives to encourage customers to sign up for voicemail plans.
- Educate customers on the benefits of voicemail services.

**4. Improve Customer Support:**
- Identify customers making multiple calls (more than 3 calls) and proactively intervene with personalized support or offers.
- Investigate the reasons for churn among customers who don't contact support. This might involve surveys, feedback analysis, or examining other customer data. Focus on improving overall customer experience beyond just support interactions.
- Provide training for customer service representatives to enhance satisfaction.
