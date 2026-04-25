# E-Commerce Sales Dashboard

**Type:** Data Analytics Project | **Tool:** Power BI

An interactive Power BI dashboard built using orders and customer data to track sales performance, profit trends, and customer behavior across states, categories, and payment modes.

Built as a portfolio project to demonstrate end-to-end data analytics and business intelligence skills.

## Objective

To analyze e-commerce sales performance and uncover actionable insights across sales, profit, and customer behavior to support data-driven business decisions.

## Dashboard Preview

![E-Commerce Sales Dashboard](https://github.com/user-attachments/assets/937cf1aa-1740-4988-a91d-5e55da4e160e)

---

## Dataset

- `Orders.csv` — Transaction-level order data containing:
  - Order ID, order date, customer name
  - State, city, and region
  - Payment mode
- `Details.csv` — Product and sales details containing:
  - Product category and sub-category
  - Quantity, amount, profit
  - Payment breakdown

---

## Tools & Technologies

- **Power BI** — Dashboard design, data modeling, and visualizations
- **Power Query** — Data cleaning & transformation
- **DAX** — KPI calculations (Total Amount, Profit, AOV, Quantity)
- **CSV** — Raw data source

---

## Key Features

**Sales Overview (KPI Cards)**
- Total Amount (438K), Total Quantity (5,615), Total Profit (37K), Average Order Value — AOV (121K)

**Sales Analysis**
- Revenue by State — top performing states (Maharashtra, Madhya Pradesh, Uttar Pradesh, Delhi)
- Profit by Month — monthly trend across full year
- Profit by Sub-Category — top performers (Printers, Bookcases, Saree, Accessories, Tables)
- Quantity by Category — Clothing (63%), Electronics (21%), Furniture (17%)

**Customer & Payment Analysis**
- Top customers by revenue (Harivansh, Madhav, Madan Mohan, Shiva)
- Payment mode distribution — COD (44%), UPI (21%), Debit Card (13%), Credit Card (12%), EMI (10%)

**Filters**
- Quarter filter (Q1–Q4)
- State-level slicer

---

## Key Insights

- Total sales amount is **438K** with **37K** profit across **5,615** units sold
- **Clothing** dominates sales with **63%** of total quantity sold
- **Maharashtra** is the highest revenue-generating state
- **COD** is the most preferred payment method at **44%**
- **Printers** generate the highest profit among all sub-categories
- Profit dips significantly in **June**, indicating a potential opportunity for seasonal promotion strategies

---

## Business Impact

This dashboard enables e-commerce teams to:
- Identify top-performing states and product categories for focused business decisions
- Understand customer payment preferences to optimize checkout experience
- Track monthly profit trends and identify seasonal performance gaps
- Identify high-value customers for targeted retention strategies

---

## How to Use

1. Download the `.pbix` file from this repository
2. Open in **Power BI Desktop** (free download at [powerbi.microsoft.com](https://powerbi.microsoft.com))
3. The dashboard loads with all data pre-connected — no additional setup required
4. Use the **quarter filter** (Q1–Q4) and **state slicer** to explore the data
5. Hover over any chart for detailed tooltips
6. To use your own data, go to **Home → Transform Data** and replace the source with your own CSV files

---

## Project Structure

ecommerce-sales-dashboard/
├── E_Commerce_Sales_Dashboard.pbix # Power BI dashboard file
├── Orders.csv # Orders dataset
├── Details.csv # Product & customer dataset
└── E-Commerce_Sales_Dashboard.pdf # Static dashboard export (preview)

---

## Author

**Fizza Shabbir** — [LinkedIn](https://linkedin.com/in/fizzashabbir) | [GitHub](https://github.com/Fizza232)
