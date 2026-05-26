# 🍕 Pizza Sales Dashboard

An interactive two-page Power BI dashboard analyzing pizza sales performance — covering revenue, order trends, category breakdowns, and best/worst selling products.

---

## 📋 Project Overview

This dashboard turns pizza transaction data into actionable sales insights. It tracks key revenue and order KPIs, identifies daily and monthly ordering patterns, breaks down sales by pizza category and size, and spotlights the top and bottom performing pizzas — all filterable by category and date.

---

## 🖥️ Dashboard Pages

### Page 1 — Home (Sales Overview)

| Visual | Title | What It Shows |
|---|---|---|
| **KPI Card** | — | Total Revenue, Total Orders, Total Pizzas Sold, Avg Order Value, Avg Pizzas Per Order |
| **Column Chart** | Daily Trends for Total Orders | Order volume by day of the week |
| **Area Chart** | Monthly Trend for Total Orders | Order volume across months |
| **Donut Chart** | % of Sales by Pizza Category | Revenue share by category |
| **Donut Chart** | % of Sales by Pizza Size | Revenue share by pizza size |
| **Funnel Chart** | Total Pizzas Sold by Pizza Category | Volume comparison across categories |
| **Slicer** | — | Filter by Pizza Category |
| **Slicer** | — | Filter by Order Date |

---

### Page 2 — Best / Worst Sellers

| Visual | Title | What It Shows |
|---|---|---|
| **KPI Card** | — | Same KPIs as Home page |
| **Bar Chart** | Top 5 Pizzas By Revenue | Highest earning pizzas |
| **Bar Chart** | Bottom 5 Pizzas By Revenue | Lowest earning pizzas |
| **Bar Chart** | Top 5 Pizzas By Quantity | Most units sold |
| **Bar Chart** | Bottom 5 Pizzas By Quantity | Fewest units sold |
| **Bar Chart** | Top 5 Pizzas By Orders | Most frequently ordered |
| **Bar Chart** | Bottom 5 Pizzas By Orders | Least frequently ordered |
| **Slicer** | — | Filter by Pizza Category |
| **Slicer** | — | Filter by Order Date |

---

## 📐 KPIs Tracked

| Metric | Description |
|---|---|
| `Total Revenue` | Sum of all sales revenue |
| `Total Orders` | Count of distinct orders placed |
| `Total Pizzas Sold` | Total units sold across all orders |
| `Average Order Value` | Revenue per order |
| `Average Pizzas Per Order` | Units per order on average |

---

## 🗂️ Data Fields Used

| Field | Description |
|---|---|
| `pizza_name` | Name of the pizza product |
| `pizza_category` | Category (e.g. Classic, Veggie, Supreme, Chicken) |
| `pizza_size` | Size of the pizza (S, M, L, XL, XXL) |
| `order_date` | Date the order was placed |
| `MonthName` | Derived month label for trend analysis |
| `Day Name Short` | Derived day-of-week label for daily trends |

---

## 🔍 Key Insights

- **Daily trends** reveal which days of the week drive peak order volumes
- **Monthly trends** highlight seasonal patterns across the year
- **Category & size breakdowns** show which pizza types and sizes generate the most revenue
- **Best/Worst sellers** page enables data-driven menu decisions — identifying stars and underperformers by revenue, quantity, and order count

---

## 🛠️ Tools Used

- **Power BI Desktop** — Report design, page navigation, and interactive slicers
- **DAX** — Calculated measures for KPIs (Total Revenue, Avg Order Value, etc.)
- **Power Query** — Data transformation and date/time column derivations

---

## 🚀 How to Use

1. Download `PizzaSalesDashboard.pbix`
2. Open in **Power BI Desktop** (free at [powerbi.microsoft.com](https://powerbi.microsoft.com))
3. Start on the **Home** page for the sales overview
4. Navigate to **Best/Worst Sellers** for product-level performance
5. Use the **Category** and **Date** slicers to filter any view

---

## 📌 Use Cases

- Portfolio project demonstrating multi-page Power BI dashboard design and DAX measures
- Sales performance reporting template adaptable to any food & beverage or retail dataset
- Reference for implementing best/worst ranking visuals and trend charts in Power BI

---

## 👤 Author

> Pavan Kalyan Guntakanti

---

## 📄 License

This project is open for learning and portfolio use. Data used for educational purposes.
