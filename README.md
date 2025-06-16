# 📊 Sales Performance Analysis Dashboard (2003–2005)

This project is an interactive Power BI dashboard that analyzes global sales data from 2003 to 2005. It provides insights into key sales performance metrics, product trends, geographic distribution, and customer segmentation by deal size. The dashboard is filterable and dynamically updates based on user selections, making it an ideal tool for sales monitoring and strategic decision-making.

---

## 🛠️ Tools Used

- **Power BI Desktop** – Data modeling, DAX measures, visualization design
- **Microsoft Excel** – Initial data cleaning and transformation
- **DAX (Data Analysis Expressions)** – Calculated measures for KPIs, rolling averages
- **Power BI Service** – Published and shared interactive version

---

## 🧹 Data Cleaning & Preparation

The dataset used was a sample sales dataset from Kaggle (link to dataset: https://www.kaggle.com/datasets/kyanyoga/sample-sales-data). Cleaning was done in Excel before importing into Power BI. Key cleaning steps:

- **Converted `Order Date`** to date format and extracted `Month`, `Year`, and `Month-Year`
- **Recalculated `Sales`** column as `Quantity Ordered × Price Each` due to inconsistencies
- **Handled missing values**:
  - Cleaned whitespace and formatting in `Country`, `State`, and `Address` fields
- **Created calculated columns**:
  - `Calculated Sales`
  - `Month-Year`
- Removed duplicates and ensured consistent data types across columns

---

## 📊 Dashboard Features & Analysis

The dashboard includes the following key elements:

### KPI Summary Cards
- **Total Sales** – Overall revenue across all orders
- **Total Orders** – Count of unique orders placed
- **Total Quantity** – Total items sold

### Product Performance
- Bar chart showing sales by product line
- Clearly highlights top-performing categories like *Classic Cars* and *Vintage Cars*

### Geographic Sales Distribution
- Interactive map displaying sales across countries
- Slicer included for filtering by country

### Sales Over Time
- Area chart with a 3-month rolling average
- Smooths fluctuations to show long-term sales trends

### Customer Segmentation by Deal Size
- Donut chart showing revenue contribution by deal size (Small, Medium, Large)

---

## 📈 Key Insights

- **Classic Cars** generated the highest revenue across all categories.
- **Medium-sized deals** dominated overall sales, contributing over 60% of total revenue.
- **Sales peaked** in late 2003 and early 2004, with noticeable seasonality patterns.
- The company’s strongest regions by revenue included **North America and Europe**.

---

## 🔗 Live Dashboard

➡️ [Click here to view the interactive dashboard](https://app.powerbi.com/reportEmbed?reportId=439f92ff-a5eb-49ca-a34b-26373726950b&autoAuth=true&ctid=6c425ff2-6865-42df-a4db-8e6af634813d)

---

## 📁 Files Included

- `Sales Performance Analysis Dashboard.pbix` – Power BI project file
- `dashboard-preview.png` – Screenshot of the dashboard
- `sales_data_sample.xlsx` – Cleaned Excel data
- `dashboard.pdf` – Exported version

