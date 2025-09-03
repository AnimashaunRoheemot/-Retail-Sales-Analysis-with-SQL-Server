# 📊 Retail Sales Analysis with SQL Server  

## 🔎 About the Project  
This project demonstrates the use of *SQL Server Management Studio (SSMS)* to perform *data cleaning* and *business analysis* on a retail sales dataset.  

I created a *Retail Sales Database, imported raw data from a CSV file, cleaned it, and then answered key **business questions* using SQL queries.  

---

## 📂 Project Workflow  

### 1️⃣ Importing the Data  
- ### Created a *RetailSales* database in SQL Server.
  ![Database Creation](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/db_creation.png.png)
  ![Database Creation Confirmation](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(144).png) 
- ### Imported the CSV file as a flat file into the database.
  ![CSV Import Step 1](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(146).png)  
![CSV Import Step 2](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(147).png)  
![CSV Import Step 3](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(148).png)  
- ### Verified successful import and select Top 1000 of the dataset. 
![verify import1](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(149).png)
![show top 1000 of dataset](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(152).png) 

### 2️⃣ Data Cleaning  
- ### Fixed a column name typo: changed quantiy → quantity.
  ![Column Rename](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(158).png) 
- ### Checked and removed null values from the dataset.    
![Check Nulls](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(159).png)  
![Remove Nulls](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(160).png)  

---

## 🎯 Business Questions Answered  

1. # Retrieve all sales made on *2022-11-05*  
   ![Sales on Date](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(161).png)  

2. # Retrieve all *Clothing transactions* where the quantity sold is greater than 4 in November 2022  
   📌 Result: No transaction met this condition  
   ![Clothing Query](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(162).png)  

3. # Calculate *total sales for each category*  
   📌 Result: Electronics had the highest sales, Beauty had the lowest  
   ![Sales by Category](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(165).png)  

4. # Find the *average age of customers* who purchased from the Beauty category  
   📌 Result: Average age = 40  
   ![Beauty Age](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(166).png)  

5. # Find all *transactions where total sales > 1000*  
   ![Sales Above 1000](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(167).png)  

6. # Find the *number of transactions* made by each gender in each category  
   📌 Result: Female customers had the highest transactions  
   ![Transactions by Gender](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(168).png)  

7. # Calculate the *average sales per month* and identify the *best-selling month* in each year  
   📌 Result:  (Month 7) which is july is best selling month for 2022 &  (Month 2)  which is february is the best selling month for 2023.
   ![Monthly Sales](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(170).png)  

8. # Find the *top 5 customers* based on highest total sales  
   ![Top 5 Customers](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(171).png)  

9. # Find the *number of unique customers* in each category  
   ![Unique Customers](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(173).png)  

10. # Create *sales shifts* (Morning <12, Afternoon 12–17, Evening >17) and calculate the number of orders in each shift  
    📌 Result: Evening shift had the highest orders, Afternoon had the lowest  
    ![Orders by Shift](https://github.com/AnimashaunRoheemot/-Retail-Sales-Analysis-with-SQL-Server/blob/main/Screenshot%20(176).png)  

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
