# FinTech Customer Churn & LTV Optimizer 

An end-to-end data analytics and machine learning engine designed to predict customer churn in a digital payments environment and optimize Customer Acquisition Cost (CAC) against Customer Lifetime Value (LTV). 

This project was built to demonstrate how predictive modeling can drive high-impact FinTech growth strategies by identifying high-risk users and maximizing marketing ROI.

## Project Highlights
* **High-Signal Feature Engineering:** Engineered complex "transaction velocity" and engagement drop-off features from a 10,000+ user dataset to expose hidden behavioral churn patterns.
* **Predictive Churn Engine:** Trained, tuned, and compared Random Forest and XGBoost classifiers. Successfully handled severe class imbalance to achieve an **0.81 ROC-AUC score** and a **73% Recall rate**—allowing for the early identification of roughly 3 out of 4 churning users before they leave.
* **Actionable Business Strategy:** Moved beyond pure accuracy by translating model probabilities into financial unit economics. Segmented users dynamically to uncover a "High Value" customer base yielding a massive **41x LTV-to-CAC ratio** ($1,936 LTV vs. $48 CAC), providing a data-backed blueprint for allocating marketing and retention budgets.

## Tech Stack
* **Language:** Python 
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Random Forest), XGBoost
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## How to Run the Model Locally

Follow these steps to replicate the environment, generate the synthetic dataset, and train the models on your own machine.

### 1. Install Dependecies
```bash
pip install -r requirements.txt
```
### 2. Clone the Repository
```bash
git clone [https://github.com/yourusername/fintech-churn-ltv-optimizer.git](https://github.com/yourusername/fintech-churn-ltv-optimizer.git)
cd fintech-churn-ltv-optimizer
```
