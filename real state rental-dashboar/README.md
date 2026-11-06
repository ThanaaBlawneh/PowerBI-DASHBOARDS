Markdown
# 🏡 Real Estate Rental Platform Analytics Dashboard (Masakin Al-Raaha)

An interactive, enterprise-grade Power BI dashboard developed for **Masakin Al-Raaha** (مساكن الراحة), a Saudi short-term and vacation rental platform. This project delivers strategic market insights, analyzing rental listing distributions, pricing models, location-based trends, and customer ratings across various Saudi cities.

---

## 📌 Executive Summary

**Masakin Al-Raaha** specializes in listing apartments, chalets, and studios across key tourism and business hubs in Saudi Arabia (such as Riyadh, Jeddah, and AlUla). 

This dashboard provides executive decision-makers with actionable intelligence to:
* **Optimize Pricing:** Align rental night rates with customer satisfaction and geographic demand.
* **Identify Market Opportunities:** Pinpoint high-revenue neighborhoods and underperforming listings.
* **Understand Customer Preferences:** Track top-performing property types across 24 coverage cities.

---

## 📊 Key Performance Indicators (KPIs)

* **Total Listings:** `2.388K` active listings available on the platform.
* **Number of Cities:** `24` cities covered across Saudi Arabia.
* **Average Rental Price:** `$622` per night.
* **Average Customer Rating:** `7.63 / 10`.

---

## 🔍 Key Analytical Views & Business Insights

The dashboard addresses key strategic business questions:

1. **City Distribution (عدد العقارات حسب المدينة):** 
   * Identifies top-demand tourism hubs (Riyadh, Jeddah, Abha, Taif, Madinah, Khobar, Dammam).
2. **Property Type Breakdown (توزيع أنواع العقارات):** 
   * Analyzes customer preference split across Apartments (شقة), Chalets (شاليه), and Studios (استديو).
3. **Price vs. Rating Correlation (العلاقة بين السعر والتقييم):** 
   * A scatter plot evaluation testing whether higher-rated listings command higher night rates.
4. **Neighborhood Price Ranking (متوسط السعر حسب الحي):** 
   * Highlights premium-priced zones (e.g., Al-Khaleej, Al-Danal, Al-Safa) to guide investment focus.

---

## 🛠️ Tools & Technologies Used

* **Business Intelligence:** Microsoft Power BI Desktop
* **Data Modeling & DAX:** Custom measures for metrics, average rating, dynamic aggregation, and visual wireframing.
* **Data Transformation:** Power Query (Data cleaning, type casting, schema structuring).
* **UI/UX Visual Design:** Custom dark layout with gold/salmon visual elements, responsive slicers (City, Property Type, Neighborhood, Rating).

---

## 📁 Repository Structure

```text
├── REAL STATE DASHBOARD.pbix       # Core Power BI File
├── real state rental dashboard.png   # Dashboard Preview Image
├── real_estate_rental_prices.xlsx  # Dataset (Source File)
├── نبذة عن الشركة.pdf               # Business Requirements & Context Document
└── README.md                       # Project Documentation
