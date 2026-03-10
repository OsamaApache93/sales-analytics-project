 Sales Analytics Project (SQL)

🧠 Project Overview
This project explores a retail sales dataset using SQL to uncover insights about **customers, products, and revenue**. The goal is to analyze sales trends, identify top-performing products and customers, and calculate key metrics for business decision-making.  

The project demonstrates **data exploration, aggregation, ranking, and window functions** using SQL (T-SQL / SQL Server).  

---

 📦 Dataset
The database consists of three main tables:

| Table | Description |
|-------|-------------|
| `gold.dim_customers` | Customer information, including `customer_key`, name, gender, birthdate, and country. |
| `gold.dim_products`  | Product information, including `product_key`, name, category, subcategory, price, and cost. |
| `gold.fact_sales`    | Sales transactions, including `order_number`, `customer_key`, `product_key`, `sales_amount`, `quantity`, `price`, and `order_date`. |

---

 🛠 SQL Queries / Sections
The project includes the following SQL analyses:

1. **Database Exploration**
   - Inspect tables and columns in the database.
   - Understand the structure of customers, products, and sales tables.

2. **Dimension Exploration**
   - Identify unique countries, product categories, and subcategories.

3. **Date Analysis**
   - Find first and last order dates.
   - Calculate age range of customers.

4. **Measures Exploration**
   - Total sales, total quantity, average price.
   - Total orders, products, and customers.
   - Create a summary table of all key metrics.

5. **Magnitude Analysis**
   - Customers by country and gender.
   - Products by category and average cost.
   - Total revenue by category and country.
   - Revenue by individual customers.

6. **Ranking Analysis**
   - Top 5 and bottom 5 products by revenue.
   - Top 10 customers by revenue with average order value.
   - Bottom 3 customers by number of orders.

---

## 📊 Key Insights
- **Top Products:** Certain products contribute a large portion of total revenue.  
- **Top Customers:** Top 10 customers generate a significant portion of sales.  
- **Revenue Distribution:** Sales are concentrated in specific countries and product categories.  
- **Customer Insights:** The database includes a wide age range and both genders.  
- **Business Metrics:** Summary table allows for quick KPI tracking (total sales, average price, total orders, etc.).  

These insights can inform decisions like:
- Product promotions and inventory management.
- Customer loyalty programs targeting high-value customers.
- Regional sales strategies based on country-level analysis.

---

## 🚀 How to Run
1. Open SQL Server Management Studio (SSMS) or any SQL tool that supports T-SQL.  
2. Ensure the database `DataWarehouseAnalytics` is created and tables are loaded (`dim_customers`, `dim_products`, `fact_sales`).  
3. Open `My EDA Project.sql` (or the separate SQL scripts).  
4. Run queries section by section to explore metrics, distributions, and rankings.  

---

## 💡 Future Work / Next Steps
- Create a **Power BI or Tableau dashboard** to visualize key metrics and trends.  
- Segment customers by revenue, frequency, and recency (RFM analysis).  
- Forecast future sales trends by product and category.  
- Incorporate additional KPIs like profit margin and return rates.  

---

## 📁 Repository Structure
