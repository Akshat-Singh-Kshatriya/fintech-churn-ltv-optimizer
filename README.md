# Customer Segmentation & Lifetime Value Prediction 

## Project Overview
This project analyzes a 2-year UK retail dataset (805,000+ transactions) to bridge the gap between raw data and actionable Go-To-Market strategies. By answering two critical business questions—*Who are our most valuable customers?* and *How much will they spend in the future?*—this project enables the growth team to optimize Customer Acquisition Cost (CAC) and improve Customer Lifetime Value (CLV).

## Business Impact & Outcomes
1. **Customer Obsession (Churn Analysis):** Identified a **36.10% Year-over-Year Customer Churn Rate**, highlighting the critical need for retention-focused marketing in parallel with new market expansion.
2. **Target Audience Definition:** Utilized **K-Means Clustering** on RFM (Recency, Frequency, Monetary) metrics to discover 4 distinct customer personas. This allows the GTM team to build highly targeted lookalike audiences for new market entry.
3. **Balancing CAC vs. LTV:** Trained a **Random Forest Regressor (R² = 0.61)** to predict a customer's 12-month future spend based purely on their early behavior. This empowers the growth team to dynamically adjust acquisition spend based on predicted profitability.

## Tech Stack
* **Data Engineering:** Cleaned and merged multi-year transactional data, handling returns, cancellations, and missing values.
* **Feature Engineering:** Calculated RFM (Recency, Frequency, Monetary) scores at the user level.
* **Unsupervised Learning:** Applied **K-Means Clustering** (validated via Silhouette Score) to segment the customer base without pre-existing labels.
* **Supervised Learning:** Built a **Random Forest Regressor** to accurately forecast Year 2 spend using Year 1 transaction features.

## 📊 Visual Dashboard
![GTM Dashboard](images/dashboard_results.png)
*(The dashboard visualizes our customer personas, the accuracy of our LTV predictions, and our overall retention/churn rate).*

## 🛠️ How to Run This Project
### 1. Clone the repository
```bash
   git clone [https://github.com/Akshat-Singh-Kshatriya/fintech-churn-ltv-optimizer.git](https://github.com/Akshat-Singh-Kshatriya/fintech-churn-ltv-optimizer.git)
   cd FareFocus-Boston
  
```
### 2. Install dependencies 
```bash
   pip install -r requirements.txt
```
### 3. Run the Jupyter Notebook
   
