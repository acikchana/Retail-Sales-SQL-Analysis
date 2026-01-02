# 🛒 Retail Sales SQL Analysis

## 📌 Project Overview
**Retail Sales SQL Analysis** is a beginner-to-intermediate SQL project designed to showcase essential data analysis skills using transactional retail data.  
The project demonstrates how SQL can be used to clean data, explore patterns, and answer real-world business questions relevant to sales and customer behavior.

This project is suitable for aspiring **Data Analysts / Business Analysts** who want to build a strong foundation in SQL-based analytics.

---

## 🎯 Objectives
- Build and manage a retail sales database using SQL  
- Clean and validate transactional data  
- Perform exploratory data analysis (EDA)  
- Answer business-driven questions using analytical SQL queries  
- Extract insights related to sales trends, customer behavior, and operations  

---

## 🧰 Tools & Technologies
- **Database**: MySQL 8.0  
- **Language**: SQL  
- **Techniques Used**:
  - Data Cleaning & Validation  
  - Aggregation (`SUM`, `AVG`, `COUNT`)  
  - Window Functions (`RANK() OVER`)  
  - Common Table Expressions (CTE)  
  - Conditional Logic (`CASE WHEN`)  
  - Date & Time Analysis  

---

## 🗂 Dataset Description
The dataset contains retail transaction records with the following attributes:

- `transaction_id`
- `sale_date`
- `sale_time`
- `customer_id`
- `gender`
- `age`
- `category`
- `quantity`
- `price_per_unit`
- `cogs`
- `total_sale`

Each row represents a single sales transaction.

---

## 🧹 Data Cleaning & Exploration
Key data preparation steps include:
- Checking total records and unique customers  
- Identifying unique product categories  
- Removing records with missing values in critical columns  
- Ensuring data consistency before analysis  

Basic EDA was performed to understand:
- Sales volume  
- Customer distribution  
- Category coverage  

---

## 📊 Business Questions & Analysis

### 1️⃣ Sales Performance by Date
- Retrieved all transactions from a specific sales date  

### 2️⃣ Category-Based Filtering
- Identified high-quantity Clothing sales during November 2022  

### 3️⃣ Category-Level Sales Contribution
- Calculated total revenue and order count per product category  

### 4️⃣ Customer Demographics Insight
- Computed average customer age for the Beauty category  

### 5️⃣ High-Value Transactions
- Identified transactions exceeding a defined sales threshold  

### 6️⃣ Gender & Category Segmentation
- Analyzed transaction distribution by gender within each category  

### 7️⃣ Best Selling Month per Year ⭐
- Calculated average monthly sales  
- Identified the top-performing month for each year using **window functions**  

### 8️⃣ Top Customers Analysis
- Ranked customers based on total sales contribution  

### 9️⃣ Unique Customers per Category
- Measured customer reach across product categories  

### 🔟 Sales by Time Shift
- Grouped orders into Morning, Afternoon, and Evening shifts  
- Evaluated operational order distribution  

---

## 🧠 Key Insights
- **Sales Trends**: Monthly sales fluctuate across years, highlighting seasonal patterns  
- **Customer Behavior**: Certain customers contribute significantly more to total revenue  
- **Category Performance**: Product categories show different purchasing patterns  
- **Operational Insights**: Order volume varies by time of day, useful for staffing and planning  

---

## 📈 Sample Use Cases
- Business performance reporting  
- Customer segmentation analysis  
- Sales trend and seasonality analysis  
- Operational planning based on order timing  

---

## 🚀 How to Run the Project
1. Create the database and table using the SQL script  
2. Import the retail sales dataset  
3. Execute queries in sequence (cleaning → exploration → analysis)  
4. Extend the analysis using visualization tools such as Power BI or Tableau  

---

## 🔮 Future Enhancements
- Add interactive dashboards (Power BI / Tableau)  
- Implement indexing for query optimization  
- Perform cohort or customer lifetime value (CLV) analysis  

---
