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
📌[**Datasets**]() – Project datasets provided as CSV files  

Structure: Relational dataset

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

Fact Table: Sales

Dimension Tables: Products, Customers, Stores, Date

This data model enables flexible analysis across time, geography, customer segments, product hierarchies, and store attributes.

#### 📐 Key Metrics & DAX Calculations

Several DAX measures were created to calculate core business KPIs:

Total Revenue

Total Quantity Sold

Number of Orders

Number of Distinct Customers

Average Order Value (AOV)

Customer Retention Rate

Gross Profit Margin

Year-over-Year (YoY) Growth %

Custom measures were also developed to compare current year vs last year performance and visually highlight positive and negative trends across the dashboards.

---

### 📊 Key Insights & Visualizations
#### I. Overview – Business Performance

The Overview Dashboard provides a high-level snapshot of the company’s overall performance.

Key insights:

Total Revenue reached $55.8M, reflecting a +12.14% year-over-year growth

Total Quantity Sold increased to 197.8K units

The number of Orders reached 26K, indicating steady demand

Distinct Customers totaled 12K, with moderate growth compared to revenue

Monthly revenue trends show consistent performance throughout the year, with stronger results in the final months, suggesting seasonal demand effects.

#### II. Customer Behavior Analysis

This dashboard focuses on understanding customer purchasing behavior and retention.

Key insights:

Returning customers generate the majority of total revenue

Average Order Value (AOV) slightly declined (-0.56% YoY), indicating potential pricing or basket-size challenges

Customers aged 60+ generate the highest revenue among all age groups

North America contributes over 60% of total global revenue

Despite growth in new customers, the customer retention rate remains relatively low, highlighting an opportunity to improve long-term customer loyalty.

#### III. Product Performance Analysis

The Product Performance Dashboard evaluates how products, categories, and brands contribute to revenue.

Key insights:

Computers and Home Appliances are the top revenue-generating categories

A small number of brands drive a disproportionate share of total revenue

Some high-priced products fall into a “premium niche” category with low sales volume

Several mid-priced products achieve strong volume but lower margins

These findings indicate opportunities to optimize pricing strategy and product mix.

#### IV. Store Performance Analysis

This dashboard assesses store efficiency and operational performance.

Key insights:

Large stores (>1000 m²) generate over 65% of total revenue

Online stores outperform many physical locations

Revenue per store and revenue per square meter vary significantly across regions

Store size has a stronger correlation with revenue than store age

This suggests that store footprint optimization could significantly improve business efficiency.

---

### 💡 Recommendations

The following recommendations are derived from dashboard insights:

Stakeholder	Focus Area	Insight	Recommendation
Management	Revenue Growth	Revenue growth is driven mainly by volume rather than AOV	Introduce targeted pricing and bundling strategies to increase basket size
Marketing	Customer Retention	Retention rate is low despite new customer growth	Develop loyalty programs for high-value and returning customers
Product Team	Product Strategy	Revenue is concentrated in a few categories	Expand and promote mid-performing categories with strong margins
Operations	Store Efficiency	Large stores outperform smaller ones	Reassess store footprint and optimize or consolidate underperforming locations

---

### 🎯 Project Impact

This Power BI dashboard delivers a clear, data-driven view of business performance, enabling stakeholders to:

Monitor KPIs efficiently

Identify revenue drivers and operational risks

Understand customer, product, and store dynamics

Support strategic and operational decision-making
