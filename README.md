## 📊 Sales Performance Analysis & Business Insights

- Author: Sunny Vo
- Date: 01/2026
- Tools Used: Power BI, DAX

---

### 🧾 Table of Contents (TOCs)

- Background & Overview

- Dataset Description

- Data Modeling & Metrics Definition (DAX)

- Key Insights & Visualizations

- Recommendations

---

### 📌 Background & Overview
#### 🎯 Objective – What is this project about?

This project focuses on building a Power BI dashboard that enables stakeholders to monitor business performance and make data-driven decisions based on sales, customer, product, and store data.

Using a structured analytical approach, the dashboard provides a multi-dimensional and comprehensive view of the company’s operations, helping decision-makers:

- Understand overall business performance

- Track key KPIs year-over-year

- Identify revenue drivers and underperforming areas

- Optimize customer, product, and store strategies

The final solution consists of four interactive Power BI report pages, each focusing on a core business dimension.

#### 🥷 Who is this project for?

- Executive & Management Team

- Sales & Marketing Team

- Operations & Store Management Team

#### ❓ Business Questions

1. How is the business performing year-over-year?

2. Which products and categories contribute most to total revenue?

3. What customer segments generate the highest value?

4. Are returning customers driving revenue growth?

5. Which stores and regions perform best and why?

6. How efficiently are store resources being utilized?

<img width="1848" height="1024" alt="image" src="https://github.com/user-attachments/assets/78822f65-c992-4607-a1d9-436034fc47ea" />



---

### 📊 Dataset Description
📌[**Datasets**](https://github.com/sunnyvo106/Retail-Sales-Performance-KPI-Monitoring-Power-BI-/tree/main/datasets) – Project datasets provided as CSV files  

- Structure: Relational dataset

The dataset consists of four core tables:

- Sales – Transaction-level sales data including order date, quantity, revenue, product ID, customer ID, and store ID

- Products – Product information such as product name, category, subcategory, brand, and cost

- Customers – Customer demographic data including age group, gender, and geographic location

- Stores – Store details including country, state, store size, footprint, and operational attributes

These tables are integrated to support end-to-end business analysis.

---

### 🧠 Data Modeling & Metrics Definition (DAX)
#### 🧩 Data Modeling

A star schema was implemented in Power BI to ensure accurate aggregation and efficient filtering:

- Fact Table: Sales

- Dimension Tables: Products, Customers, Stores, Date

This data model enables flexible analysis across time, geography, customer segments, product hierarchies, and store attributes.

<img width="1500" height="1112" alt="image" src="https://github.com/user-attachments/assets/ee06c85c-c9b7-483b-8e06-c45fd34cb576" />


#### 📐 Key Metrics & DAX Calculations

- DAX measures were developed to track core business performance across revenue,
orders, customers, and profitability, with year-over-year comparisons used
to highlight growth trends and performance changes across dashboards.

---

### 📊 Key Insights & Visualizations
#### I. Overview – Business Performance

<img width="1816" height="1026" alt="image" src="https://github.com/user-attachments/assets/f95f24e4-f415-4032-acde-5d879b45b482" />

- The Overview Dashboard highlights how revenue, orders, customers, and sales volume move together across the years, indicating that overall performance is strongly driven by customer activity and transaction volume.

   - Across the period analysed, the business reaches a peak before experiencing a noticeable downturn. In the most recent year shown (2020), Total Revenue is $9.3M, compared with a significantly higher level in the prior year, representing an approximate 49% year-over-year decline. This decline is consistent across other core metrics, including Orders (5K), Distinct Customers (4K), and Total Quantity Sold (34.5K units), all of which decrease by roughly 40–50% YoY.

   - Monthly trends (2020) show that performance is not evenly distributed throughout the year. While January and February record relatively stronger results, most subsequent months perform below the prior year, with several months showing declines greater than 60% YoY. This suggests that the reduction in performance is sustained over time rather than limited to a short period.

   - When viewed across all years, changes in revenue closely follow changes in order volume and customer count, while average items per order remain relatively stable. This indicates that revenue fluctuations are driven more by how often customers purchase rather than by customers buying significantly more items per transaction.

**Overall, Across all years, business performance is closely linked to customer participation and order activity. Periods of weaker revenue coincide with fewer orders and fewer active customers, highlighting demand volume as a key driver of overall performance.**

#### II. Customer Behavior Analysis

  <img width="1850" height="1044" alt="image" src="https://github.com/user-attachments/assets/74185023-863e-4ca9-9df5-8b5692753df4" />

- This dashboard provides insight into how customers contribute to revenue and how sustainable that contribution is over time.

- Overall, customer-related metrics show stable revenue growth, but the underlying behavior indicates a heavy reliance on existing customers rather than strong retention or basket expansion.

   - From the dashboard, returning customers generate the majority of total revenue, while new customers contribute a smaller share. This suggests that the business currently depends on its existing customer base to sustain revenue growth. However, despite the inflow of new customers, the customer retention rate remains relatively low, indicating that many customers do not make repeat purchases over time.

   -  In terms of purchase behavior, the Average Order Value (AOV) declined slightly by 0.56% year-over-year. While the change is not large, it suggests that customers are either purchasing fewer items per order or shifting toward lower-priced products. This aligns with the observation that average items per order remain relatively flat, indicating limited basket-size growth.

   - Demographic analysis shows that customers aged 60 and above generate the highest share of revenue, outperforming younger age groups. This implies that older customers tend to have higher purchasing power or stronger purchasing intent. Geographically, North America contributes over 60% of total global revenue, highlighting a strong regional concentration and potential exposure to regional demand fluctuations.

**Overall, while revenue growth remains positive, the customer analysis reveals structural weaknesses in retention and basket growth, suggesting that long-term revenue sustainability may be at risk without targeted loyalty or engagement strategies.**

#### III. Product Performance Analysis

<img width="1860" height="1044" alt="image" src="https://github.com/user-attachments/assets/7abbac31-f31f-4cf7-8868-804c26e177f9" />

- The Product Performance Dashboard evaluates how revenue is distributed across product categories, brands, and pricing levels, and whether volume and profitability are aligned.

   - At a high level, Computers and Home Appliances emerge as the dominant revenue-generating categories, contributing the largest share of total sales. However, revenue concentration is uneven, as a small number of brands account for a disproportionate share of total revenue, indicating dependency on a limited product portfolio.

   - The relationship between price and quantity reveals a clear price–volume trade-off. Several brands operate in a high-price, low-volume position, forming a “premium niche” where higher margins are achieved but sales volume remains limited. Conversely, many mid-priced brands achieve strong sales volume but lower gross profit margins, suggesting competitive pricing pressure or higher cost structures.

   - This imbalance indicates that revenue growth is driven more by volume-heavy, mid-priced products rather than margin expansion. While premium products contribute to profitability, their low volume limits overall revenue impact.

**Overall, the product analysis suggests opportunities to rebalance the product mix, either by improving margins on high-volume products or by increasing volume for premium offerings through targeted positioning or promotion.**
 
#### IV. Store Performance Analysis

<img width="1852" height="1042" alt="image" src="https://github.com/user-attachments/assets/e7497bec-6d35-4e8f-87f0-7abe2c4a8c0b" />

- The Store Performance Dashboard focuses on operational efficiency and revenue contribution across different store formats, regions, and channels.

   - The analysis shows that large stores (over 1000 m²) generate more than 65% of total revenue, significantly outperforming medium and small stores. This indicates that store size plays a major role in revenue generation, likely due to greater product assortment and customer capacity.

   - Channel comparison further reveals that online stores outperform many physical locations, highlighting the growing importance of digital channels in overall business performance. Despite this, physical stores still account for a substantial share of revenue, suggesting that the business operates in a hybrid retail model rather than being fully digital-led.

   - Efficiency metrics such as revenue per store and revenue per square meter vary widely across regions, indicating inconsistent store performance. Some stores generate strong revenue relative to their footprint, while others underperform despite similar size or location attributes. Importantly, the dashboard shows that store size has a stronger correlation with revenue than store age, suggesting that newer stores do not automatically outperform older ones.

**Overall, the store analysis points to uneven resource utilization across the store network, implying that optimizing store footprint, channel focus, and regional strategy could significantly improve operational efficiency and profitability.**
---

### 💡 Recommendations

The following recommendations are derived from dashboard insights:

Stakeholder	Focus Area	Insight	Recommendation:
- Management	Revenue Growth	Revenue growth is driven mainly by volume rather than AOV	Introduce targeted pricing and bundling strategies to increase basket size
- Marketing	Customer Retention	Retention rate is low despite new customer growth	Develop loyalty programs for high-value and returning customers
- Product Team	Product Strategy	Revenue is concentrated in a few categories	Expand and promote mid-performing categories with strong margins
- Operations	Store Efficiency	Large stores outperform smaller ones	Reassess store footprint and optimize or consolidate underperforming locations

---

### 🎯 Project Impact

This Power BI dashboard delivers a clear, data-driven view of business performance, enabling stakeholders to:

- Monitor KPIs efficiently

- Identify revenue drivers and operational risks

- Understand customer, product, and store dynamics

- Support strategic and operational decision-making
