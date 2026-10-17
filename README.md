# Bank Account & Customer Transaction Performance Analytics Dashboard

## Executive Summary
This **Power BI Analytics Dashboard** provides an end-to-end view of banking operations, customer portfolio health, transaction volumes, and balance distributions.

The dataset was generated using **AI (LLMs)** and structured into a relational database using **SQL** before being imported into **Power BI** for data modeling and interactive visualization.

The project monitors account performance across **Savings vs Current accounts**, identifies **inactive account trends**, tracks **monthly transaction patterns**, and breaks down **customer demographics**.

---

## Tools & Technologies Used
* **AI Prompts / Generation**: Synthetic data creation and initial dashboard structure recommendation.
* **SQL**: Table schema creation, data insertion, and data transformation.
* **Power BI Desktop**: Data modeling, dynamic measures, and chart custom visualizations.
* **DAX & Data Aggregations**: Calculated measures for demographic segmentation and monthly volume metrics.

---

## Dashboard Pages & Visualizations

### 1. Customer Demographics & Balance Overview (Page 1)
* **Total Balance by Name**: Tracks high-value vs deficit customer balances (e.g., Mark Lee, Sarah Khan, Priya Singh).
* **Monthly Transaction Balance Trend**: Monthly cash flow movement throughout the year with key dips in January, May (-1.58M), and October (-1.42M).
* **Account Count by Account Type**: Treemap breakdown showing an equal split between **Current (200)** and **Savings (200)** accounts.
* **Age Group Distribution**: Customer volume across **26–35 (100)**, **36–50 (100)**, and **51+ (100)** age groups.
* **Gender Ratio Breakdown**: Donut chart distribution showing **Male (25%)**, **Female (25%)**, and **Blank/Unspecified (50%)**.

---

### 2. Transaction Amount & Account Health Analysis (Page 2)
* **Total Amount by Customer Name**: Customer net debit/credit balance analysis (e.g., Sarah Khan at **0.25M** vs Mark Lee at **-0.24M**).
* **Total Balance by Account Type**: Comparison showing **Savings** account holding (**1.48K**) vs **Current** account holding (**-15782.44K**).
* **Inactive Accounts by Month**: Consistent tracking showing a steady baseline of **5 inactive accounts** every month.
* **Monthly Transaction Amount Trend**: Visualizes transaction volume shifts, peaking in **July (4.1M)** and **January (4.0M)**, with a low in **February (0.9M)**.
* **Count of Transaction by Type**: Equal distribution across transaction types (**5K / 50% each**).

---

## Key Business Insights
1. **Portfolio Distribution**: The account base is evenly split between Savings (200) and Current (200) accounts, but Current accounts reflect significant negative balance flow requiring risk evaluation.
2. **Transaction Seasonality**: High activity peaks occur in **January (4.0M)** and **July (4.1M)**, whereas February experiences the lowest transaction activity (**0.9M**).
3. **Account Inactivity**: A baseline of **5 dormant accounts per month** indicates a predictable segment for automated re-engagement campaigns.

