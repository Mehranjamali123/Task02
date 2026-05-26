# Project 2 — Exploratory Data Analysis (EDA)
**DecodeLabs Industrial Training | Batch 2026**

## Overview
EDA on an E-Commerce Orders dataset to uncover patterns, trends, and outliers.

## Dataset
| Property | Detail |
|---|---|
| File | Dataset for Data Analytics.xlsx |
| Rows | 1,200 |
| Columns | 14 |
| Date Range | Jan 2023 – Jun 2025 |

## Tools Used
Python · Pandas · NumPy · Matplotlib · Seaborn · SciPy

## What I Did
- ✅ Data cleaning — datetime parsing, filled 309 missing CouponCode values
- ✅ Descriptive statistics — mean, median, std, five-number summary
- ✅ Outlier detection — IQR method + Z-Score method
- ✅ Correlation analysis — Pearson heatmap
- ✅ 6 visualizations — revenue, trends, order status, referral source

## Key Findings
- 📦 TotalPrice is **right-skewed** → median ($823) is better than mean ($1,053)
- ⚠️ **20.8% cancellation rate** — needs business action
- 📣 **Instagram** drives the highest revenue among referral sources
- 🔗 UnitPrice ↔ TotalPrice correlation: **r = 0.72** (strong)
- 🎟️ **74%** of customers used a discount coupon

## Files
```
├── supermarket_eda.py        # main script
├── chart1_revenue_by_product.png
├── chart2_totalprice_dist.png
├── chart3_boxplot.png
├── chart4_order_status.png
├── chart5_monthly_trend.png
├── chart6_referral_payment.png
└── README.md
```

## How to Run
```bash
pip install pandas numpy matplotlib seaborn scipy openpyxl
python supermarket_eda.py
```

---
*DecodeLabs Internship — Batch 2026*
