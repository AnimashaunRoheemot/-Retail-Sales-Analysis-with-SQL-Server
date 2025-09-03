# 📊 Retail Sales Analysis with SQL Server  

## 🔎 About the Project  
This project demonstrates the use of *SQL Server Management Studio (SSMS)* to perform *data cleaning* and *business analysis* on a retail sales dataset.  

I created a *Retail Sales Database, imported raw data from a CSV file, cleaned it, and then answered key **business questions* using SQL queries.  

---

## 📂 Project Workflow  

### 1️⃣ Importing the Data  
- Created a *RetailSales* database in SQL Server.  
- Imported the CSV file as a flat file into the database.  
- Verified successful import.  

📸 Screenshots:  
![Database Creation](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/db_creation.png.png)  
![Database Creation Confirmation](images/db_creation_confirm.png)  
![CSV Import Step 1](images/csv_import1.png)  
![CSV Import Step 2](images/csv_import2.png)  
![CSV Import Step 3](images/csv_import3.png)  

---

### 2️⃣ Data Cleaning  
- Fixed a column name typo: changed quantiy → quantity.  
- Checked and removed null values from the dataset.  

📸 Screenshots:  
![Column Rename](images/column_rename.png)  
![Check Nulls](images/check_nulls.png)  
![Remove Nulls](images/remove_nulls.png)  

---

## 🎯 Business Questions Answered  

1. Retrieve all sales made on *2022-11-05*  
   ![Sales on Date](images/sales_on_date.png)  

2. Retrieve all *Clothing transactions* where the quantity sold is greater than 4 in November 2022  
   📌 Result: No transaction met this condition  
   ![Clothing Query](images/clothing_query.png)  

3. Calculate *total sales for each category*  
   📌 Result: Electronics had the highest sales, Beauty had the lowest  
   ![Sales by Category](images/sales_by_category.png)  

4. Find the *average age of customers* who purchased from the Beauty category  
   📌 Result: Average age = 40  
   ![Beauty Age](images/beauty_age.png)  

5. Find all *transactions where total sales > 1000*  
   ![Sales Above 1000](images/sales_above_1000.png)  

6. Find the *number of transactions* made by each gender in each category  
   📌 Result: Female customers had the highest transactions  
   ![Transactions by Gender](images/transactions_by_gender.png)  

7. Calculate the *average sales per month* and identify the *best-selling month* in each year  
   📌 Result: July 2022 (Month 7) & February 2023 (Month 2)  
   ![Monthly Sales](images/monthly_sales.png)  

8. Find the *top 5 customers* based on highest total sales  
   ![Top 5 Customers](images/top5_customers.png)  

9. Find the *number of unique customers* in each category  
   ![Unique Customers](images/unique_customers.png)  

10. Create *sales shifts* (Morning <12, Afternoon 12–17, Evening >17) and calculate the number of orders in each shift  
    📌 Result: Evening shift had the highest orders, Afternoon had the lowest  
    ![Orders by Shift](images/orders_by_shift.png)  

---

## ✅ Key Insights  
- *Electronics* category generated the highest revenue.  
- *Female customers* made more purchases across categories.  
- *July 2022* and *February 2023* were the peak sales months.  
- *Evening shifts* recorded the highest order volume.  

---

## 🚀 Tools Used  
- SQL Server Management Studio (SSMS)  
- SQL Server Database Engine  
- CSV Data Import (Flat File)  
- GitHub for Portfolio  

---

✨ This project highlights my ability to clean, query, and analyze real-world retail sales data using SQL Server.
