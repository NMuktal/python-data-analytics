# Customer Segmentation & Propensity to Buy Analysis (RFM + ML)

## Project Overview
This project demonstrates how customer behavioral data can be used to **segment customers and predict purchase propensity** using **RFM analysis** and **machine learning**.  
The goal is to help businesses identify high-value customers, improve targeted marketing, and support data-driven decision-making.

Synthetic data is used to simulate real-world customer behavior while maintaining data privacy.

---

## Business Objective
- Segment customers based on **Recency, Frequency, and Monetary (RFM)** values
- Assign **business-friendly customer segments**
- Build a **predictive model** to identify customers likely to make a purchase
- Translate analytics results into **actionable business insights**

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Data Description
The dataset represents customer behavior with the following features:

| Feature | Description |
|---------|------------|
| Recency (days) | Days since last purchase |
| Frequency | Number of purchases |
| Monetary Value | Total amount spent |
| Email Clicks | Email engagement metric |
| Website Visits | Website activity metric |
| Purchase | Target variable (Yes / No) |

---

## RFM Analysis
Customers are scored on:
- **Recency:** More recent activity → higher score
- **Frequency:** More purchases → higher score
- **Monetary:** Higher spend → higher score

Scores range from **1 (low)** to **5 (high)**, and are combined into a **total RFM score (3–15)**.

---

## Customer Segmentation
Based on RFM scores, customers are grouped into meaningful segments:

| Segment | Description |
|---------|------------|
| Champions | Highest-value customers |
| Loyal Customers | Consistent buyers |
| Potential Loyalists | Growing engagement |
| At Risk | Declining activity |
| Low Value | Least engaged customers |

---

## Predictive Modeling
A **Gradient Boosting Classifier** is used to predict customer purchase likelihood using:
- Behavioral data
- RFM score
- Engagement metrics

### Model Evaluation
- Accuracy
- Precision & Recall
- Confusion Matrix
- Feature Importance

---

## Business Insights
- High RFM score customers have a significantly higher likelihood of purchase
- Email engagement and purchase frequency are strong predictors
- Customer segmentation enables targeted marketing rather than mass campaigns
- The model supports smarter allocation of marketing resources

---

## Future Enhancements
- SQL-based RFM analysis
- Power BI dashboard integration
- Model deployment as an API
- Time-based trend analysis

