# Power BI Shopping Behaviour Analysis

## 🚀 Project Overview
This Power BI project provides a comprehensive, interactive 5-page report that analyzes customer shopping behavior. Unlike static reporting, this solution utilizes a dynamic data model to identify spending patterns, product performance, and high-value customer segments through advanced filtering and drill-down capabilities.

---

## 🏗️ Data Architecture
The project follows a clean BI workflow:
1. **Data Transformation (Power Query):** * Handled data profiling and type conversion.
   * Created custom columns for `Age_Bracket`, `Spending_Tier`, and `Frequency_Tier`.
   * Standardized categorical data (Colors, Sizes, Seasons).
2. **Data Modeling:** * Organized the dataset into a Star Schema for optimized performance.
   * Established relationships between demographics, transaction facts, and time-based dimensions.
3. **DAX Measures:** Developed custom measures for **Total Revenue**, **Average Order Value (AOV)**, and **Customer Lifetime Value (CLV)** segments.

---

## 📑 Report Pages & Interactive Features

### 🟢 Page 1: Sales Performance Overview
* **Key Visuals:** Seasonal Trend Lines, Revenue by Size (Tree Map), and Category Performance (Bar Charts).
* **Business Insight:** Identifies peak shopping windows and high-moving inventory.

### 🔵 Page 2: Customer Demographics & Spending
* **Key Visuals:** Age Distribution Histograms, Spending Tier Clustered Columns.
* **Business Insight:** Pinpoints which age cohorts drive the highest transaction values.

### 🟣 Page 3: Customer Behavior Insights
* **Key Visuals:** Frequency Tier Pie Chart, Loyalty vs. Spend Scatter Plot.
* **Business Insight:** Segments the audience into *Loyal, Frequent, Occasional,* and *Rare* groups to inform retention strategies.

### 🟡 Page 4: Product Preference Analysis
* **Key Visuals:** Category by Age Group Heatmaps, Color & Size Matrix.
* **Business Insight:** Supports supply chain decisions by highlighting specific product attribute preferences.

### 🔴 Page 5: Customer Value & Segmentation
* **Key Visuals:** Subscription Status Comparison, Discount Usage Impact Analysis.
* **Business Insight:** Analyzes the ROI of discounts and the value of subscribed vs. non-subscribed customers.

---

