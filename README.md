#  Future Interns — Data Science Task 2  
**Social Media & Advertising Campaign Performance Analysis**

This repository contains my submission for **Future Interns — Data Science Task 2**, focused on analyzing **advertising and marketing channel performance** using Python, Power BI, and business metrics.

---

## Objective
The goal of this task is to **analyze ad spend across multiple marketing channels** and derive actionable insights on which channels contribute most effectively to product sales and return on investment.

---

##  Dataset Overview

**File:** `Advertising_Data.csv`

| Column | Description |
|:--------|:-------------|
| `tv` | Amount spent on TV advertising |
| `billboards` | Amount spent on billboard advertising |
| `google_ads` | Spend on Google ad campaigns |
| `social_media` | Spend on social media ads (Facebook, Instagram, etc.) |
| `influencer_marketing` | Budget allocated to influencer promotions |
| `affiliate_marketing` | Spend on affiliate partnerships |
| `product_sold` | Number of products sold resulting from all campaigns |

---

## Key Performance Indicators (KPIs)

| Metric | Formula | Purpose |
|:-------|:---------|:--------|
| **Total Spend** | `tv + billboards + google_ads + social_media + influencer_marketing + affiliate_marketing` | Total advertising cost |
| **Total Units Sold** | `SUM(product_sold)` | Overall sales performance |
| **Cost per Sale (CPS)** | `Total Spend / Total Units Sold` | Average cost to sell one product |
| **ROI (Return on Investment)** | `(Revenue - Total Spend) / Total Spend * 100` | Profitability of the campaigns |

> *Optional*: If revenue per unit is known, you can extend the analysis to compute `Revenue` and `ROI`.

---

##  Tools & Technologies Used

| Tool | Purpose |
|:------|:---------|
| **Power BI** | Data cleaning, transformation, and dashboard visualization |
| **Python (Pandas, Matplotlib)** | Exploratory Data Analysis (EDA) |
| **Excel** | Data preprocessing and validation |
| **Git & GitHub** | Version control and project hosting |

---

##  Insights Derived

- Identified which advertising channels yield the **highest sales impact per spend**.  
- Compared **digital vs. traditional media performance** (Google Ads, Social Media vs. TV, Billboards).  
- Calculated **CPS** to determine cost-efficiency per product sold.  
- Designed **interactive Power BI dashboard** showing channel-wise spend, ROI trends, and total performance.

---

## 📁 Folder Structure

