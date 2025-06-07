# CINEMA-BUSINESS-ANALYSIS-PROJECT
This project involved end-to-end data analysis for a cinema business, using real transaction data from May 2019 to uncover customer insights, operational inefficiencies, and propose actionable business strategies. The team applied techniques from data preprocessing to machine learning and dashboard creation to support data-driven decision-making in cinema operations.

# Objectives:  
  - Analyze customer behavior through demographic and transactional data.
  - Identify customer segments using clustering algorithms.
  - Build business intelligence dashboards to visualize key performance indicators (KPIs).
  - Provide actionable recommendations to optimize cinema operations and marketing strategies.

# Key Features:
  - Segmented customers using RFM metrics with K-Means and DBSCAN.
  - Identified trends in ticket sales, genres, time slots, and seat preferences.
  - Built interactive Power BI dashboards for business KPIs, customer profiles, and scheduling.
  - Proposed data-driven strategies for marketing and F&B upselling.
  - Tools: Python, Power BI, Excel

# Data Preprocessing & Modeling Approach
  - Removed irrelevant columns, handled missing values, converted birthdate to age, and treated outliers.
  - Engineered RFM features:
    - Recency: days since last purchase
    - Frequency: number of tickets purchased
    - Monetary: total amount spent
  - Encoded categorical variables:
    - Used One-Hot Encoding for Job and Industry
    - Used Label Encoding for Gender
    - Normalized numerical features using StandardScaler.
# K-Means Clustering Results & Customer Insights
The customer segmentation yielded 4 distinct clusters:

- **Cluster 1** – Inactive Customers (~2,230 customers):
Low visit frequency, minimal spending, and long time since last interaction. Mostly young (avg. age ~27), previously watched action, sci-fi, mystery, and adventure.  
**→ Suggested action**: Reactivation campaigns via email/app with genre-based recommendations and discount codes.  
![image](https://github.com/user-attachments/assets/ac9e1af4-63be-4fa2-b460-f8409025a4a8)

- **Cluster 2** – Outlier VIP (1 customer):
Extremely high frequency (~4,000 visits) and spending (~5 billion VND), recency = 0, but age = 6 (likely data error or shared account).  
**→ Suggested action**: Flag as VIP; offer loyalty rewards and personalized experiences. Verify data integrity.  
![image](https://github.com/user-attachments/assets/f9720044-0f86-4d3f-9b1f-c154b0f986b9)

- **Cluster 3** – Niche High-Spender (1 customer):
Nearly 2,900 visits, ~3.3 billion VND spent. Prefers horror, action, adventure, mystery.  
**→** **Suggested action**: Treat as VIP customer with tailored offerings.  
![image](https://github.com/user-attachments/assets/0ff78546-345c-42b5-9cd0-adefd4915497)

- **Cluster 4** – Active Regulars (~2,200 customers):
Moderate frequency (~2 visits), recent engagement (~6 days), stable spending (~200,000 VND). Age ~29, with preferences for comedy, horror, adventure, and mystery.  
**→** **Suggested action**: Upsell via combo offers, loyalty cards, and referral incentives.  
![image](https://github.com/user-attachments/assets/969084c2-d9f7-4c69-bc91-e8af0458a0bf)

# Dashboard
- 🎬**Movie Theatre Overview Dashboard**  
  ![image](https://github.com/user-attachments/assets/7e5c6ad7-e4f2-49da-9201-7d7cbdfa6454)
- 🧑‍🤝‍🧑 **Customer Segmentation Dashboard**  
    ![image](https://github.com/user-attachments/assets/58753829-8649-499c-88c4-e79a099db7e1)

- 📅 **Scheduling Dashboard**  
    ![image](https://github.com/user-attachments/assets/403aeaa0-fa08-49a7-aca8-a1ebd4359d00)
