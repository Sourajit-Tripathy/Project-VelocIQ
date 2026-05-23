<div align="center">

# 🚀 Project VelocIQ
### Revenue Intelligence & Customer Analytics
**Client: ZenKart Commerce Pvt. Ltd.**

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green?style=for-the-badge&logo=pandas)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

> **Found Rs. 4.2 Crore in hidden revenue leakage across 1 million e-commerce transactions in 6 weeks.**

[![LinkedIn](https://img.shields.io/badge/Connect%20on-LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](YOUR_LINKEDIN_URL_HERE)
[![Power BI](https://img.shields.io/badge/View-Live%20Dashboard-F2C811?style=for-the-badge&logo=powerbi)](YOUR_POWERBI_URL_HERE)

</div>

---

## 📌 Project Overview

| Field | Details |
|-------|---------|
| **Project Name** | VelocIQ (VI-2024-001) |
| **Client** | ZenKart Commerce Pvt. Ltd. |
| **Lead Analyst** | Jeet |
| **Head of Analytics** | Sourajit Tripathy |
| **Dataset Size** | 1,000,000 rows |
| **Clean Dataset** | 884,708 rows |
| **Date Range** | Jan 2023 – Dec 2024 |
| **Timeline** | 6 weeks |
| **Total Impact Found** | Rs. 4.2 Crore / year |

---

## 🔥 3 Key Findings

### 📱 Finding 1 — Mobile Cart Abandonment
- Mobile abandon rate: **42.1%** vs Desktop: **20.0%**
- 55% of all orders initiated on mobile
- **Revenue lost: Rs. 1.8 Crore / year**
- Root cause: 6-step checkout, UPI timeout, no guest checkout

### 📍 Finding 2 — South Region AOV Gap
- South region AOV: **Rs. 66** vs Platform average: **Rs. 72**
- 8% below average — persisted across both years
- **Opportunity: Rs. 1.1 Crore / year**
- Root cause: High Food & Grocery mix, low Electronics penetration, excess discounting

### 👑 Finding 3 — Customer Concentration Risk
- Top **8% of customers** drive **52% of revenue**
- 58,000 Champion customers with no VIP programme
- **Revenue at risk: Rs. 3.5 Crore** if Champions churn
- Root cause: No loyalty tier, no early warning system

---

## 🛠 Tech Stack

Data Generation    →  Python, Faker, NumPy, Pandas
Data Cleaning      →  Pandas, SciPy (IQR method)
Feature Engineering→  Pandas GroupBy, DateTime, qcut
EDA & Charts       →  Matplotlib, Seaborn (8 charts)
Segmentation       →  RFM scoring (300K customers)
Dashboard          →  Power BI Desktop, DAX measures
PDF Report         →  ReportLab

---

## 📁 Repository Structure
📁 Project-VelocIQ/
│
├── 📄 README.md
│
├── 📂 data/
│   ├── zenkart_velociq_clean.csv       # 884,708 clean rows
│   └── zenkart_velociq_rfm.csv         # RFM segments (300K customers)
│
├── 📂 scripts/
│   ├── zenkart_velociq_data_generator.py   # Generate 1M rows
│   └── zenkart_velociq_eda.py              # Full EDA & cleaning pipeline
│
├── 📂 charts/
│   ├── 01_monthly_revenue_trend.png
│   ├── 02_aov_by_region.png
│   ├── 03_cart_abandon_by_device.png
│   ├── 04_revenue_by_category.png
│   ├── 05_revenue_distribution.png
│   ├── 06_rfm_segments.png
│   ├── 07_discount_vs_revenue.png
│   └── 08_correlation_heatmap.png
│
├── 📂 reports/
│   └── VelocIQ_Stakeholder_Script_Jeet.pdf
│
└── 📂 docs/
└── PowerBI_DAX_Guide.md

---

## ⚡ Quick Start

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/Project-VelocIQ.git
cd Project-VelocIQ
```

### 2. Install dependencies
```bash
pip install pandas numpy faker matplotlib seaborn scipy tqdm reportlab
```

### 3. Generate the 1M row dataset
```bash
python scripts/zenkart_velociq_data_generator.py
```
⏱ Runs in under 20 seconds. Outputs `zenkart_velociq_1M.csv`

### 4. Run the full EDA pipeline
```bash
python scripts/zenkart_velociq_eda.py
```
Outputs:
- `zenkart_velociq_clean.csv` — 884,708 clean rows
- `zenkart_velociq_rfm.csv` — RFM segments
- `charts/` — 8 PNG visualisations

### 5. Open Power BI Dashboard
- Import `zenkart_velociq_clean.csv` and `zenkart_velociq_rfm.csv`
- Follow the DAX setup in `docs/PowerBI_DAX_Guide.md`

---

## 📊 EDA Charts Preview

| Chart | Insight |
|-------|---------|
| Monthly Revenue Trend | Festive peaks in Oct–Nov (45% above avg) |
| AOV by Region | South is 8% below platform average |
| Cart Abandon by Device | Mobile 42% vs Desktop 20% |
| Revenue by Category | Electronics highest, Food lowest |
| Revenue Distribution | Right-skewed, mean Rs. 72 |
| RFM Segments | Champions = 8% customers, 52% revenue |
| Discount vs Revenue | Higher discounts don't lift basket size |
| Correlation Heatmap | Session duration + revenue positively correlated |

---

## 💡 RFM Segments

| Segment | Customers | Avg Spend | Priority |
|---------|-----------|-----------|----------|
| 👑 Champions | 58,000 | Rs. 605 | RETAIN |
| 💙 Loyal | 57,000 | Rs. 210 | NURTURE |
| 🌱 Potential Loyalist | 62,000 | Rs. 130 | CONVERT |
| ⚠️ At Risk | 69,000 | Rs. 84 | REACTIVATE |
| 💤 Lost | 54,000 | Rs. 52 | WIN BACK |

---

## 📋 4 Recommendations

| # | Action | Owner | Timeline | Impact |
|---|--------|-------|----------|--------|
| 1 | Fix mobile checkout (6 steps → 4, guest checkout, UPI fix) | Engineering | 6 weeks | Rs. 1.8 Cr/yr |
| 2 | Abandoned cart retargeting (push + email within 1 hr) | VP Marketing | 2 weeks | Rs. 40L/yr |
| 3 | Champions VIP programme (early access, free shipping) | Marketing + CRM | 4 weeks | Rs. 1.2 Cr/yr |
| 4 | South region Electronics push + reduce discounting 30% | Marketing + Ops | 3 weeks | Rs. 75L/yr |
| | **TOTAL** | | **All in 30 days** | **Rs. 4.2 Cr/yr** |

---

## 📄 Power BI DAX Measures

```dax
Total Revenue = SUM(zenkart_velociq_clean[final_revenue_inr])

Total Orders = COUNTROWS(zenkart_velociq_clean)

Avg Order Value = AVERAGE(zenkart_velociq_clean[final_revenue_inr])

Cart Abandon Rate =
DIVIDE(
  COUNTROWS(FILTER(zenkart_velociq_clean, zenkart_velociq_clean[cart_abandon_flag] = 1)),
  COUNTROWS(zenkart_velociq_clean)
)

MoM Revenue Growth =
DIVIDE(
  [Total Revenue] - CALCULATE([Total Revenue], PREVIOUSMONTH(DateTable[Date])),
  CALCULATE([Total Revenue], PREVIOUSMONTH(DateTable[Date]))
)

Abandon Alert =
VAR Rate = [Cart Abandon Rate]
RETURN IF(Rate > 0.35, "🚨 CRITICAL — " & FORMAT(Rate,"0.0%"),
       IF(Rate > 0.28, "⚠ WARNING — " & FORMAT(Rate,"0.0%"),
       "✓ HEALTHY — " & FORMAT(Rate,"0.0%")))
```

---

## 👥 Team

| Role | Name |
|------|------|
| Lead Analyst (External) | **Jeet** |
| Head of Analytics | **Sourajit Tripathy** |
| CEO | Rajesh Kapoor |
| CFO | Ananya Mehta |
| VP Marketing | Vikram Nair |
| VP Operations | Sneha Pillai |

---

## 🌐 Links

| | Link |
|---|---|
| 📊 Live Power BI Dashboard | [View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMzQxM2UxZDEtZTYwMy00ZjdhLWJmNmYtNjY4NDg1ZDkzNmM4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9) |
| 💼 LinkedIn | [Connect with Sourajit](https://www.linkedin.com/in/sourajit-tripathy/) |

---

## 💬 Want to be added to this project's contributor wall?

> Drop a ⭐ star on this repo AND comment on the LinkedIn post with **#VelocIQ** — I'll add your name and LinkedIn here!

### 🏆 Contributor Wall
*Be the first! Star the repo + comment #VelocIQ on LinkedIn to get added here.*

| Name | LinkedIn | Role |
|------|----------|------|
  | Sourajit | [Connect](https://www.linkedin.com/in/sourajit-tripathy/) |  Analyst |
| *(your name here)* | *(your link)* | *(community contributor)* |

---

<div align="center">

**Project VelocIQ · ZenKart Commerce Pvt. Ltd. · Analyst: Jeet**

*"Data does not lie. Act on it."*

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=YOUR_USERNAME.Project-VelocIQ)

</div>
