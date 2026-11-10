# Bike Sales Analytics & Executive Dashboard

An interactive Excel analytics project evaluating customer demographics, income levels, and commute habits to identify key drivers of bike purchases.

---

## 📊 Executive Summary

This project transforms raw customer transaction data into an interactive dashboard to answer a core business question: **Which customer segments are most likely to purchase a bike?**

---

## 🗂️ Data Architecture & Workflow

1. **Raw Data (`bike_buyers Data`):** Customer records spanning demographics, financial metrics, and purchase decisions.
2. **Data Cleaning (`Clean Data`):**
   - Removed duplicate entries for data integrity.
   - Standardized coded values (e.g., `M`/`S` → `Married`/`Single`; `F`/`M` → `Female`/`Male`).
   - Grouped ages into a custom **Age Bracket** column (`Middle Age`, `Senior`, `Adolescent`).
3. **Aggregations (`Pivot Tables`):** Structured PivotTables to evaluate purchase behavior against income, commute distance, and age.
4. **Interactive Dashboard (`Dashboard`):** Executive visualization layout with dynamic slicers.

---

## 📉 Key Dashboard Metrics

* **Average Income by Purchase Status:** Compares buyer vs. non-buyer earnings by gender.
* **Commute Distance Impact:** Tracks purchase volume against distance traveled to work.
* **Age Group Distribution:** Highlights peak purchasing age categories.
* **Interactive Slicers:** Dynamic filtering across **Marital Status**, **Region**, and **Occupation**.

---

## 💡 Key Business Insights

* **Income Correlation:** Higher average income correlates directly with higher bike purchase rates.
* **Commute Range:** Short-distance commuters (0–1 miles) represent the largest target market for bike sales.
* **Core Target Demographic:** Middle-aged customers demonstrate the highest conversion rate compared to adolescents and seniors.
