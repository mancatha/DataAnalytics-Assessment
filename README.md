# DataAnalytics-Assessment
## Introduction
This project presents a comphensive analysis of financial transcation data to uncover patterns is user behavior,identify risk indicators and gain insights into platform operation. The datasets includes was a merged table of plans and saving tables. 

🔍 Analytical Questions & Insights
1. 💰 What is the total amount transacted overall and by year?
    ![Total Transaction by Year](igraph\Traansaction.png)

Approach: Aggregated transaction values (amount) across all users.

Insights: Identified total sums transacted. Yearly analysis provided visibility into financial growth and platform usage over time.

2. 📅 Are there patterns or spikes in transaction dates (Time Series)?
Approach: Parsed transaction dates to extract years and months. Grouped by time and visualized transaction counts.

Insights: Spikes were observed in certain months/years, possibly due to promotional periods, user behavior patterns, or operational cycles.

3. 💳 What is the average transaction amount by transaction type?
Approach: Grouped transactions by transaction_type_id and computed the average amount.

Insights: Some transaction types (e.g., investment, savings) had higher average amounts, suggesting different user intents or product usage.

4. 📊 What are the most frequent transaction statuses and types?
Approach: Used value counts on transaction_status and transaction_type_id to determine popularity.

Insights: Most transactions were successful, but notable proportions were pending or failed, indicating areas for process improvement or error resolution.

5. 🛡️ What is the distribution of fraud scores? Are there high-risk users?
Approach: Visualized fraud_score using histograms and distribution plots.

Insights: Majority of users fell into low-to-medium risk ranges. A few outliers with high fraud scores were identified as high-risk users.