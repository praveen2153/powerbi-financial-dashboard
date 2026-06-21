# 📊 Financial Sales Analysis Dashboard | Power BI

## 📌 Project Overview

This project focuses on analyzing sales, profit, products, countries, and customer segments using Power BI. The objective is to derive meaningful business insights and support data-driven decision-making through interactive dashboards.

---

## 🎯 Business Problem

Tasks to answer the following questions:

- Which month and year had the highest profit?
- Which country/region is performing the best?
- Which product and segment should the company continue investing in?
- How can business insights be visualized effectively through an interactive dashboard?

---

## 📂 Dataset

The dataset contains sales transactions including:

- Segment
- Country
- Product
- Sales
- Profit
- COGS
- Discounts
- Units Sold
- Date

---

## 📈 Business Questions & Answers

### 1️⃣ Which month and year had the highest profit?

✅ **December 2014**

---

### 2️⃣ Which country generated the highest profit?

✅ **France**

---

### 3️⃣ Which product and segment should the company continue investing in?

✅ **Product:** Paseo  
✅ **Segment:** Government

---

### 4️⃣ Business Update

⚠️ Montana product was discontinued and should not be considered for future investment decisions.

---

# 📊 Dashboard Features

- KPI Cards
- Profit Trend Analysis
- Country-wise Performance Analysis
- Product Analysis
- Segment Analysis
- Interactive Slicers
- Tooltips
- Conditional Formatting
- Dynamic Filtering

---

# 📌 Key KPIs

| KPI | Description |
|-----|-------------|
| Total Sales | Overall revenue generated |
| Total Profit | Total company profit |
| Units Sold | Total quantity sold |
| Profit Margin | Profit percentage |
| Top Country | Highest profit country |
| Top Product | Most profitable product |

---

# 📈 Dashboard Pages

### 1. Executive Overview
- Total Sales
- Total Profit
- Units Sold
- Profit Margin

### 2. Profit Trend Analysis
- Profit by Month and Year

### 3. Country Performance
- Profit by Country

### 4. Product Analysis
- Profit by Product

### 5. Segment Analysis
- Profit by Segment

---

# 🎨 Power BI Features Used

- DAX Measures
- Slicers
- Tooltips
- Conditional Formatting
- Bar Charts
- Column Charts
- KPI Cards
- Line Charts
- Matrix Visual
- Interactive Filters

---

# 🧮 DAX Measures

```DAX
Total Sales = SUM(Financials[Sales])

Total Profit = SUM(Financials[Profit])

Total Units Sold = SUM(Financials[Units Sold])

Profit Margin =
DIVIDE(
    SUM(Financials[Profit]),
    SUM(Financials[Sales])
)
```

---

# 🎯 Conditional Formatting

Used conditional formatting to highlight high-performing categories.

Example:

- Profit > 2,000,000 → Green
- Profit < 2,000,000 → Gray

```DAX
Bar Color =
IF(
    SUM(Financials[Profit]) > 2000000,
    "#00B050",
    "#D3D3D3"
)
```

---

# 📊 Insights

✅ December 2014 generated the highest profit.

✅ France is the most profitable country.

✅ Government is the best-performing segment.

✅ Paseo is the most profitable product.

✅ Montana has been discontinued.

---

# 🛠️ Tools & Technologies

- Power BI
- DAX
- Microsoft Excel
- Data Visualization
- Business Intelligence
  
---

# 📁 Repository Structure

```text
Financial-Sales-Analysis-PowerBI/
│
├── README.md
├── Financial Sales Dashboard.pbix
├── Financial Sample.xlsx

```

---

# 🚀 Project Outcome

This dashboard enables stakeholders to:

- Monitor business performance.
- Identify profitable regions.
- Evaluate product performance.
- Make investment decisions.
- Track profit trends over time.

---

# 💼 Resume Project Description

**Financial Sales Analysis Dashboard | Power BI**

- Developed an interactive Power BI dashboard to analyze sales and profitability.
- Identified top-performing countries, products, and customer segments.
- Created DAX measures, KPIs, slicers, tooltips, and conditional formatting.
- Delivered actionable business insights through data visualization.

---

# 🔗 Skills Demonstrated

- Data Analysis
- Business Intelligence
- Power BI
- DAX
- Dashboard Design
- Data Visualization
- Business Insights
- KPI Development

---

## ⭐ If you found this project helpful, please give it a star.
