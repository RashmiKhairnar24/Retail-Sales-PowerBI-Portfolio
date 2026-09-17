# 📊 Northgate Sales Analytics — Power BI Dashboard

An interactive **Retail Sales Analytics Dashboard** built in **Microsoft Power BI** using the Northgate 2023 sales dataset.

The project analyzes sales performance across regions, product categories, products, and sales representatives. The dashboard is designed to turn transaction-level sales data into clear business KPIs, trends, and performance comparisons.

## 🎯 Project Objective

The objective of this project is to analyze 2023 retail sales data and answer questions such as:

- How is total revenue performing over time?
- Which regions generate the most revenue?
- Which product categories contribute the most sales?
- Which products are the top revenue generators?
- How are sales representatives performing?
- How do gross profit and gross margin vary across the business?

---

## 🛠️ Tools Used

- **Microsoft Power BI** — dashboard and visualization
- **Power Query** — data preparation and transformation
- **DAX** — KPI and business calculations
- **CSV** — source sales dataset
- **GitHub** — project versioning and portfolio presentation

---

## 📁 Repository Structure

```text
Northgate-Sales-Analytics/
│
├── README.md
├── northgate_sales_2023.csv
├── Retail-Sales-Analytics-Dashboard(1).pbix
└── Retail-Sales-Analytics-Dashboard(1).pdf
```

The `.pbix` file is the interactive Power BI report.

The `.pdf` file is a static export of the dashboard for quick viewing.

The `.csv` file is the underlying sales dataset used for the analysis.

---

# 📂 Dataset Overview

The source file contains **2,415 transaction rows** and **15 columns** covering sales activity in 2023.

### Dataset fields

| Column | Description |
|---|---|
| `transaction_id` | Unique transaction identifier |
| `order_date` | Date of the transaction |
| `customer_id` | Customer identifier |
| `customer_name` | Customer name |
| `region` | Sales region |
| `city` | Customer city |
| `sales_rep` | Sales representative |
| `category` | Product category |
| `product_name` | Product name |
| `product_id` | Product identifier |
| `quantity` | Units sold |
| `unit_price` | Selling price per unit |
| `unit_cost` | Cost per unit |
| `discount_pct` | Discount percentage |
| `returns` | Return status |

### Dataset coverage

- **Year:** 2023
- **Regions:** East, West, North, South
- **Categories:** Electronics, Clothing, Home & Garden
- **Products:** 15
- **Sales Representatives:** 19

---

# 📊 Dashboard Pages

## 1. Sales Performance Dashboard

The first page provides a high-level view of business performance.

### Main KPIs

- Total Revenue
- Gross Profit
- Gross Margin %
- Total Orders
- Total Customers

### Visualizations

The dashboard includes:

- Monthly Total Revenue trend
- Total Revenue by Region
- Total Revenue and Gross Margin % by Category
- Total Revenue by Category

### Filters

Users can interact with the dashboard using:

- Region
- Category
- Month / Year

The dashboard is designed to make regional, category, and time-based comparisons easy to explore.

---

## 2. Product & Sales Rep Performance

The second page focuses on product and sales representative performance.

### Visualizations

- Top Products by Revenue
- Revenue by Sales Representative
- Detailed product-level performance table

### Product table metrics

The table includes:

- Product Name
- Total Revenue
- Total Cost
- Gross Profit
- Gross Margin %
- Units Sold

### Filters

Users can filter the analysis by:

- Region
- Product
- Date

---

# 💡 Dashboard Insights

The dashboard contains a dedicated **Key Business Insights & Recommendations** section.

The displayed analysis highlights:

- **Regional margin performance:** the dashboard identifies differences in margin performance between regions and links these differences to discounting and category mix.
- **Category performance:** Electronics generate the highest revenue volume while the dashboard highlights lower margin performance compared with other categories.
- **Monthly performance:** February is highlighted as a lower-revenue month compared with the normal monthly run rate.
- **Sales representative performance:** the dashboard compares representative revenue and connects lower revenue performance with transaction volume and discounting.
- **Discount control:** the dashboard recommends tighter control of discretionary discounts and the use of higher-margin accessory bundles.

These are the findings and recommendations presented within the dashboard itself.

---

# 📌 Dashboard Preview

The project also includes a PDF export of the finished dashboard:

**`Retail-Sales-Analytics-Dashboard(1).pdf`**

The PDF contains both dashboard pages:

1. **Sales Performance Dashboard | 2023**
2. **Product & Sales Rep Performance**

---

# 🔄 Project Workflow

```text
Raw CSV Data
     ↓
Power Query
     ↓
Data Preparation
     ↓
Power BI Data Model
     ↓
DAX / KPI Calculations
     ↓
Interactive Visualizations
     ↓
Business Insights
```

---

# 📈 Skills Demonstrated

This project demonstrates practical experience with:

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- KPI Development
- Sales Analysis
- Revenue Analysis
- Profitability Analysis
- Product Performance Analysis
- Regional Analysis
- Sales Representative Analysis
- Dashboard Design
- Business Reporting

---

# 🚀 How to Use the Project

### Open the Power BI dashboard

1. Download the repository.
2. Install **Microsoft Power BI Desktop**.
3. Open:

```text
Retail-Sales-Analytics-Dashboard(1).pbix
```

4. If Power BI asks for the source file, select:

```text
northgate_sales_2023.csv
```

5. Refresh the report if required.
6. Use the filters and visuals to explore the dashboard.

---

# 🖼️ Dashboard Screenshot

After adding the PNG version of the PDF to your repository, you can display it here:

```markdown
![Northgate Sales Analytics Dashboard](dashboard-preview.png)
```

---

# 👩‍💻 Author

**Rashmi Khairnar**

Aspiring **Data Analyst / Business Analyst**

Skills and areas of interest:

- Data Analytics
- Business Intelligence
- Power BI
- DAX
- Excel
- SQL
- Business Analytics

---

## ⭐ Project Purpose

This project was created as a **data analytics portfolio project** to demonstrate the ability to transform raw retail transaction data into an interactive business dashboard and communicate useful sales insights through data visualization.

---

## 📄 License

This project is intended for **educational and portfolio purposes**.
