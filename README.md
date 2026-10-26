# 🛒 Global E-Commerce Sales & Customer Analytics Dashboard

##  Project Overview
An interactive Power BI dashboard analyzing 1 million+ global e-commerce transactions from 2024–2026. The dashboard uncovers actionable insights across sales performance, customer behavior, product profitability, and delivery operations — designed to simulate real-world business intelligence reporting.

---

##  Objectives
- Track and monitor global revenue, profit, and order trends
- Understand customer segments, demographics, and loyalty behavior
- Identify top-performing and underperforming product categories and brands
- Evaluate delivery efficiency and operational bottlenecks across shipping methods

---

##  Dashboard Pages

### Page 1 — Sales Overview
Provides an executive-level summary of business performance.
- **KPIs:** Total Orders (992K), Total Revenue ($403M), Avg Margin (39.47%), Total Profit ($160M), Profit Margin %
- **Charts:**
  - Monthly Revenue Trend (Line chart with trend line)
  - Total Orders by Order Status (Donut chart)
  - Revenue by Country & Category (Filled Map)
  - Revenue by Category (Treemap)
  - Weekend vs Weekday Orders (Column chart)
  - Country-wise Revenue, Profit & Margin (Table)
- **Slicers:** Category, Country, Order Status, Customer Segment, Order Date.

---

### Page 2 — Customer Analytics
Deep dive into customer demographics, segments, and behavior.
- **KPIs:** Total Customers (992K), Avg Loyalty Score (49.97), Avg Rating (3.00), Regular Customer % (60.11%), Mobile User % (33.40%)
- **Charts:**
  - Revenue by Age Group (Column chart)
  - Total Customers by Segment (Donut chart)
  - Revenue & Customers by Traffic Source (Bar chart)
  - Total Customers by Device Type (Donut chart)
  - Revenue by Customer Segment (Bar chart)
  - Avg Loyalty Score vs Total Revenue by Segment (Scatter chart)
- **Slicers:** Country, Category, Customer Segment, Order Status, Order Date

---

### Page 3 — Product & Sales Performance
Analyzes product categories, brands, discounts, and customer satisfaction.
- **KPIs:** Total Categories (5), Total Brands (20), Avg Product Rating (4.00), Avg Discount % (8.50), Avg Profit Margin % (39.47%)
- **Charts:**
  - Revenue vs Profit Margin % by Category (Scatter chart)
  - Revenue & Profit Margin by Customer Segment (Bar chart)
  - Total Revenue by Category (Bar chart)
  - Review Sentiment Breakdown (Donut chart)
  - Revenue by Rating Bucket (Column chart)
  - Top 10 Brands by Revenue (Bar chart)
- **Slicers:** Country, Category, Customer Segment, Order Status, Order Date

---

### Page 4 — Delivery & Operations
Monitors shipping performance, delivery trends, and operational health.
- **KPIs:** Avg Delivery Days (7.51), Delivered % (75.07%), Avg Rating (3.00), Avg Product Rating (4.00), Failed Delivery %
- **Charts:**
  - Avg Delivery Days by Month (Line chart)
  - Avg Profit Margin % by Shipping Method (Column chart)
  - Profit by Order Status (Bar chart)
  - Delivery Status Distribution (Donut chart)
  - Top 10 Countries by Avg Delivery Days (Bar chart)
- **Slicers:** Country, Category, Customer Segment, Order Status, Delivery Status, Order Date

---

## 📂 Dataset

**Dataset:** Global E-Commerce Dataset (2024–2026)

### Dataset Highlights

- 990K+ Orders
- Multiple Countries
- Customer Segments
- Product Categories
- Brand Information
- Revenue & Profit
- Shipping & Delivery
- Customer Ratings & Review Sentiment
- Payment & Traffic Sources

  
----

### Columns Used

| Group | Columns |
|---|---|
| Order & Date | order_id, order_date, order_status, is_weekend |
| Customer | customer_id, gender, age, customer_segment, country |
| Product | category, sub_category, brand, product_rating_avg |
| Financials | total_price_usd, profit_usd, profit_margin_percent, discount_percent |
| Operations | payment_method, shipping_method, delivery_days, delivery_status |

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design and visualization |
| **Power Query (M Language)** | Data cleaning and transformation |
| **DAX** | Calculated measures and KPIs |
| **Microsoft Excel** | Initial data exploration |

---

## 🧹 Data Cleaning Steps (Power Query)

1. **Removed 42 redundant columns** — kept 21 focused columns from original 63
2. **Created Age Group column** — bucketed age into 18–25, 26–35, 36–45, 46–60, 60+
3. **Created Rating Bucket column** — grouped product_rating_avg into 1–2★, 2–3★, 3–4★, 4–5★
4. **Replaced is_weekend TRUE/FALSE** — with "Weekend" / "Weekday" for readability
5. **Fixed data types** — order_date set to Date, numeric columns verified as Decimal


---

## 💡 Key Business Insights

1. **Electronics dominates revenue** — $70M+ making it the highest revenue category, but margin analysis reveals Health has a stronger profit margin.
2. **46–60 age group is the biggest spender** — contributing $100M+ in revenue, making them the primary target demographic.
3. **75% of orders are delivered successfully** — 15% remain In Transit and 5% Failed, indicating an operational improvement opportunity.
4. **All traffic sources perform equally** — Social, Direct, Email, Search, Referral each contribute ~$81M, suggesting no single channel dominates acquisition.
5. **Weekend vs Weekday ordering pattern** — reveals whether the business is B2B (weekday heavy) or B2C (weekend heavy).
6. **39.47% average profit margin** — healthy margin across all categories, with discount impact visible in the scatter analysis.

---
# 🚀 Learning Outcomes

- Designed an end-to-end business intelligence dashboard.
- Built interactive reports using Power BI.
- Applied DAX to create business KPIs and calculated measures.
- Performed data cleaning and transformation using Power Query.
- Implemented data modeling for efficient analysis.
- Created interactive navigation using bookmarks and buttons.
- Delivered actionable insights through business-focused visualizations.

---

# 📷 Dashboard Preview

### 📈 Executive Overview

<img width="1355" height="743" alt="image" src="https://github.com/user-attachments/assets/89cabed4-88ec-4083-b883-4ea8329606b7" />

---

### 👥 Customer Analytics

<img width="1356" height="737" alt="image" src="https://github.com/user-attachments/assets/79de5e7d-0c20-494a-a09c-65285893f722" />

---

### 📦 Product Analytics

<img width="1362" height="747" alt="image" src="https://github.com/user-attachments/assets/344906bd-c7fc-4193-b3da-ecaf05c51195" />

---

### 🚚 Operations Analytics

<img width="1355" height="732" alt="image" src="https://github.com/user-attachments/assets/ccdb2b2d-ea86-411d-9e24-bfb629340d34" />

---


## 📁 Project Structure

```
Global-Ecommerce-Dashboard/
│
├── GlobalEcommerce.pbix          # Power BI dashboard file
├── ecommerce_data.csv            # Raw dataset (source: Kaggle)
└── README.md                     # Project documentation
```

---

##  Author
**Pranav**

🔗 LinkedIn:
[www.linkedin.com/in/pranav-chavan000/](https://www.linkedin.com/in/pranav-chavan000/)

💻 GitHub:
https://github.com/Pranavchavan109
---
