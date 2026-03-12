# 📊 Fintech User Retention & Churn Analysis

A data analysis project that explores customer churn patterns in a fintech/banking context, identifying key drivers of user drop-off and providing actionable retention strategies.

---

## 🔍 Overview

Customer churn is one of the most critical problems faced by fintech companies. This project analyzes a **Bank Customer Churn dataset (10,000+ records)** to answer:

- Why do customers leave the platform?
- Which user segments are most at risk?
- Which features correlate with retention?
- How can product teams reduce churn?

---

## 📁 Project Structure

```
fintech-churn-analysis/
│
├── churn_analysis.ipynb       # Main analysis notebook
├── churn.csv                  # Dataset
├── churn_distribution.png     # Churn distribution chart
├── funnel.png                 # User activation funnel
├── cohort_churn.png           # Churn rate by age group
├── churn_heatmap.png          # Feature correlation heatmap
└── README.md
```

---

## 📦 Dataset

**Source:** Bank Customer Churn Dataset

| Column | Description |
|---|---|
| `credit_score` | Customer's credit score |
| `country` | Country of residence |
| `gender` | Customer gender |
| `age` | Customer age |
| `tenure` | Years with the bank |
| `balance` | Account balance |
| `products_number` | Number of financial products used |
| `credit_card` | Whether customer has a credit card |
| `active_member` | Whether customer is active |
| `estimated_salary` | Estimated yearly salary |
| `churn` | Target: 1 = churned, 0 = retained |

---

## 🛠️ Technologies Used

- **Python** — core language
- **pandas** — data manipulation
- **matplotlib** — data visualization
- **seaborn** — advanced charts

---

## 📈 Analyses Performed

### 1. Churn Distribution
Visualizes the proportion of customers who stayed vs. left. Approximately **20% of customers churn** — meaning 1 in 5 users leave the platform.

![Churn Distribution](churn_distribution.png)

### 2. User Activation Funnel
Simulates a four-stage product funnel:

```
Registered → Active → Engaged → Retained
```

Identifies where users drop off and highlights the impact of product engagement on retention.

![Funnel](funnel.png)

### 3. Cohort Analysis by Age
Groups users by age bracket and measures churn rate per group. Key finding: **users aged 46–55 show the highest churn rate**.

![Cohort](cohort_churn.png)

### 4. Feature Correlation Heatmap
Highlights relationships between variables. Key correlations:
- Active members churn less
- Multiple product users are more loyal
- Age positively correlates with churn risk
  
![Heatmap](churn_heatmap.png)

---

## 💡 Key Findings

- ~**20%** of customers churn overall
- **Ages 46–55** have the highest churn rate
- Users with **multiple products** churn significantly less
- **Inactive members** are far more likely to churn

---

## ✅ Business Recommendations

1. **Cross-sell products** to increase engagement and reduce churn
2. **Target high-risk age groups** (46–55) with personalized retention campaigns
3. **Re-engage inactive users** through notifications, offers, or onboarding nudges
4. **Offer personalized financial services** to improve satisfaction and loyalty

---

## 🚀 Future Improvements

- Machine learning churn prediction models
- Customer segmentation via clustering
- Interactive dashboards (Streamlit or Power BI)
- Time-series analysis of churn trends

---

## 👤 Author

**Sunidhi Choudhary**

