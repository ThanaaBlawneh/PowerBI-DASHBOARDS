🏦 Commercial Bank Performance & Customer Analytics Dashboard

An executive-level, multi-page Power BI reporting solution developed for a commercial bank in Jordan. This project delivers comprehensive visibility into financial transactions, customer demographics, cash flow dynamics, and branch-level performance.

---

## 📌 Executive Summary

Designed to empower bank management with data-driven insights, this dashboard tracks financial health, channel efficiency, and customer behavior across multiple branches and cities in Jordan.

The solution is structured across **three core analytical pages**:
1. **Banking Overview:** High-level financial summaries, net cash flow, monthly trends, and transaction types.
2. **Transactions Analysis:** Deep-dive into transaction amounts, completion success rates, channel distribution, and branch performance.
3. **Customers & Branches:** Geographic customer distribution, account type segmentation, age demographics, and branch activity.

---

## 📊 Key Performance Indicators (KPIs & Metrics)

* **Financial Metrics:** Total Completed Deposits, Total Withdrawals, Net Cash Flow (JOD), and Average Transaction Amount.
* **Volume & Reach:** Total Transactions (900), Total Unique Customers (120), and 24/7 Channel tracking.
* **Operational Quality:** Transaction Completion Rate (%) with advanced status breakdown (Completed, Failed, Pending).

---

## 🔍 Key Dashboard Sections & Visuals

* **Banking Overview Page:** Features monthly transaction trend lines, deposit vs. withdrawal comparisons per branch, and a transaction type donut chart.
* **Transactions Analysis Page:** Highlights monthly cash flow fluctuations, channel popularity (Mobile App, ATM, Online, Branch), and completion status metrics.
* **Customers & Branches Page:** Analyzes customer concentration across Jordanian cities (Amman, Irbid, Zarqa, Aqaba, Salt), account types (Current vs. Savings), and age demographics (Under 30 vs. 30 and Above).
* **Interactive Tooltips:** Hovering over branches reveals dedicated performance pop-ups containing transaction counts, completion rates, and channel breakdowns.

---

## 🛠️ Technical Stack & Implementation

* **Business Intelligence:** Microsoft Power BI Desktop
* **Data Modeling:** Star Schema architecture connecting Customers and Transactions via `CustomerID` relationship.
* **Data Transformation & DAX:** Custom calculated columns (`Transaction Month`, `Age Group`) and robust DAX measures (`DISTINCTCOUNT`, `CALCULATE`, `DIVIDE`, `FORMAT`).
* **UI/UX Design:** Professional banking-themed Navy & Teal color palette, custom page navigation buttons, and responsive cross-filtering slicers.

---

## 📁 Repository Structure

```text
├── banking-dashboard.pbix          # Core Power BI Report File
├── banking dashboard preview.png     # Dashboard Overview Image
├── Banking_PowerBI_Training_Data.xlsx # Source Dataset
└── README.md                       # Project Documentation
