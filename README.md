# Power BI Shopping Behaviour Analysis

## Project Overview
This Power BI project provides a comprehensive, interactive 5-page report that analyzes customer shopping behavior. Unlike static reporting, this solution utilizes a dynamic data model to identify spending patterns, product performance, and high-value customer segments through advanced filtering and drill-down capabilities.

---

## Data Architecture
The project follows a clean BI workflow:
1. **Data Transformation (Power Query):** * Handled data profiling and type conversion.
   * Created custom columns for `Age_Bracket`, `Spending_Tier`, and `Frequency_Tier`.
   * Standardized categorical data (Colors, Sizes, Seasons).
2. **Data Modeling:** * Organized the dataset into a Star Schema for optimized performance.
   * Established relationships between demographics, transaction facts, and time-based dimensions.


---

## Report Pages & Interactive Features

### PAGE 1: Customer Overview Dashboard
**Goal:** Establish a baseline of "Who" the customers are.
* **Visuals:** Total Customer Cards, Gender Distribution (Donut), Age Bracket Analysis (Bar), and Geographic Location (Map/Bar).
* **Key Insight:** Identify the primary demographic segments and subscription penetration.
  - <a href = "https://github.com/yvvonelle/shopping-behaviour-powerbi-dashboard/blob/main/customer%20demographics.png"> Customer Demographics </a>

### PAGE 2: Spending Behavior Dashboard
**Goal:** Quantify the financial impact of different segments.
* **Visuals:** Total Revenue & AOV Cards, Seasonal Spending (Column), and Spending Tier Distribution (Bar).
* **Key Insight:** Pinpoint which seasons and age groups drive the highest total revenue.

### PAGE 3: Loyalty & Purchase Frequency
**Goal:** Analyze customer retention and return patterns.
* **Visuals:** Frequency Tier Distribution (Bar), Average Spend by Frequency (Column), and Purchase Frequency granularity (Donut).
* **Key Insight:** Determine if "Loyal" customers actually spend more per transaction than "Occasional" shoppers.

### PAGE 4: Product Insights
**Goal:** Optimize inventory and marketing by product type.
* **Visuals:** Top 10 Items Purchased (N-Filter Bar Chart), Category Performance, and Size/Color Preference Donut Charts.
* **Key Insight:** Identify "Hero Products" and customer style preferences to guide stocking strategies.

### PAGE 5: Discounts & Payments
**Goal:** Understand financial friction and incentive effectiveness.
* **Visuals:** Discount Usage (Donut), Payment Method Popularity (Bar), and Revenue by Payment Method (Column).
* **Key Insight:** Analyze if specific payment methods correlate with higher spending or if discounts successfully drive transaction volume.

---

