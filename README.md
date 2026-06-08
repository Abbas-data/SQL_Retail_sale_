 # 🛍️ SQL Retail Sales Analysis

## 📌 Project Overview
This project focuses on analyzing retail sales data using SQL to uncover business insights and answer important business questions.

The analysis includes customer behavior, sales trends, category performance, top customers, and transaction insights.

## 🛠️ Tools Used
- SQL
- PostgreSQL
- CSV Dataset

## 📂 Dataset Information
The dataset contains retail sales transaction details, including:

- Transaction ID
- Sale Date & Time
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price Per Unit
- COGS (Cost of Goods Sold)
- Total Sale

## 🧹 Data Cleaning
Before analysis, null values were checked and removed from important columns such as:
- Transaction ID
- Sale Date
- Customer ID
- Gender
- Age
- Category
- Quantity
- Price Per Unit
- COGS
- Total Sale

## 📊 Business Questions Solved

### 1. Sales on Specific Date
Retrieved all sales made on **2022-11-05**.

### 2. Clothing Sales Analysis
Found clothing transactions with quantity sold in **November 2022**.

### 3. Category-wise Total Sales
Calculated total sales and total orders for each category.

### 4. Average Customer Age
Found the average age of customers in the **Beauty** category.

### 5. High Value Transactions
Retrieved transactions where total sales were greater than **1000**.

### 6. Gender-wise Transactions
Calculated total transactions made by each gender across categories.

### 7. Monthly Sales Analysis
Calculated average monthly sales and analyzed sales performance.

### 8. Top 5 Customers
Identified the top 5 customers based on highest sales.

### 9. Unique Customers by Category
Calculated the number of unique customers in each category.

### 10. Sales Shift Analysis
Created sales shifts:
- **Morning** → Before 12 PM  
- **Afternoon** → Between 12 PM and 5 PM  
- **Evening** → After 5 PM  

## 📈 Key Insights
- Category-wise sales performance was analyzed.
- Customer purchasing behavior was explored.
- Top customers were identified based on spending.
- Sales patterns by time shift were studied.

## 📁 Project Files
- `SQL Analysis` → SQL queries for analysis  
- `Retail Sales Analysis.csv` → Dataset file  

## 🚀 How to Run the Project
1. Import the CSV dataset into PostgreSQL.
2. Create the required table.
3. Run SQL queries from `main3.sql`.
4. Analyze the output and insights.

## 👨‍💻 Author
**Abbas**
