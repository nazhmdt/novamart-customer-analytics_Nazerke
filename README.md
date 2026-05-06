# 🛍️ NovaMart Customer Analytics
 
> End-to-end customer analytics project for a UAE-based omnichannel retailer — from raw data to RFM segmentation and Power BI dashboard.
 
---
 
## 📌 Overview
 
Full analytics pipeline built on NovaMart's transaction and customer data. The goal: understand customer behavior, identify key segments, and deliver actionable business recommendations.
 
---
 
## 📂 Project Structure
 
```
novamart-customer-analytics/
├── data/
│   ├── customers.csv         # Customer profiles — demographics, acquisition channel, loyalty tier
│   └── transactions.csv      # Transaction records — orders, returns, product categories
├── NovaMart_CustomerAnalytics.ipynb   # Full analysis pipeline
├── NovaMart_Dashboard.pbix            # Power BI dashboard
└── README.md
```
 
---
 
## 🔍 Analysis Pipeline
 
**1. Data Loading & Inspection** — shape, dtypes, statistical summary
 
**2. Data Cleaning**
- Datetime conversion for time-based analysis
- Missing value imputation (mode for categorical fields)
- Duplicate removal
- Return transaction filtering
- Outlier removal via IQR method
**3. Exploratory Data Analysis**
- Monthly revenue trends
- Revenue by product category
- Customer acquisition by channel
- Order value distribution
- Average order value by age group & gender
**4. RFM Segmentation**
- Recency, Frequency, Monetary scoring (quintile-based)
- 5 segments: **Champion · Loyal · New Customer · At-Risk · Lost**
- Segment summary: customer count, avg metrics, revenue share
**5. Business Insights**
- Champions = 71 customers → **52.1% of total revenue**
- At-Risk segment identified as highest-priority for reactivation
- Campaign recommendations per segment
**6. Export for Power BI**
- `transactions_clean.csv` — Sales Overview page
- `rfm_output.csv` — Segmentation page
---
 
## 🛠️ Tech Stack
 
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C9ED9?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
 
---
 
## 💡 Key Findings
 
- **Revenue is highly concentrated** — Champion segment (71 customers) drives 52.1% of total revenue
- **Instagram** is the top acquisition channel by volume, but channel quality analysis reveals nuance
- **At-Risk segment** (47 customers, 13.9% revenue share) is the most urgent target for retention campaigns
- **Clothing** is the top-performing product category by revenue
---

## 👥 Team

**Nazerke Zhumadilova** · [@nazhmdt](https://github.com/nazhmdt)  
**Inzhu Nurlan** · [@InzhuNurlan](https://github.com/InzhuNurlan)

---

## 🎓 Course

**AI in Marketing** — Astana IT University  
Instructor: **Muhammed Ali Ibrahim** 
