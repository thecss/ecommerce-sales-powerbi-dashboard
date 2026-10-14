# Ecommerce Monthly Sales Powerbi Dashboard

> An interactive Power BI sales dashboard built for operational managers and leadership to evaluate end-of-month revenue trends, fulfillment speeds, and customer satisfaction metrics.

---

## 📌 Project Overview

This Power BI dashboard provides a single-page executive overview of sales performance. It allows leadership to evaluate high-level business health across key metrics—such as **Total Revenue**, **Total Orders**, **Total Units Sold**, and **Average Order Value** while investigating regional drivers, category contributions, and operational fulfillment performance.

<br>

## 🎯 Business Problem

Leadership often lacks a single consolidated view connecting top-line revenue outcomes with operational fulfillment and customer sentiment. This dashboard addresses three key questions:
1. *Where is revenue coming from across product lines and geographic regions?*
2. *Are customer payment choices leaning heavily toward riskier methods like Cash on Delivery (COD)?*
3. *Do longer delivery times directly impact customer satisfaction ratings?*

This dashboard is used by:
* **E-Commerce Operations Managers** evaluating monthly logisitics and customer satisfaction.
* **Sales & Growth Leaders** reviewing category performance and regional revenue distribution.
* **Executive Leadership** conducting monthly strategy reviews.

This dashboard is used for **End-of-Month (EOM) Performance Reviews** to evaluate completed sales cycles, track targets, and align cross-functional teams.

 <br>
 
## 📊 Dataset Used

The dashboard relies on an e-commerce transactional dataset containing **12 core attributes**:

* **Transaction Details:** `order_id`, `order_date`, `quantity`, `revenue`
* **Product & Channel:** `product_category`, `payment_method`, `discount`
* **Geography & Logistics:** `region`, `delivery_days`, `shipping_cost`
* **Customer Feedback:** `customer_rating`

---

## 💡 Business Impact

1. **Eliminates Executive Friction:** Consolidates complex sales and shipping data into a clean, single-page UI built for fast decision-making.
2. **Identifies Operational Bottlenecks:** Helps managers pinpoint whether poor ratings stem from delivery delays or underlying product quality issues.
3. **Optimizes Sales & Inventory Strategy:** Highlights top-performing categories (Electronics & Clothing) to guide inventory stocking and targeted promotional campaigns.
4. **Improves Cash Flow & Risk Management:** Tracks payment channels, giving operational teams visibility into COD volume versus card settlements.

---

## 🛠️ Built With

* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Power Query (Data Transformation)**
