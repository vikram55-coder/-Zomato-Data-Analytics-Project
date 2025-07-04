# -Zomato-Data-Analytics-Project
This project demonstrates end-to-end data analysis using Excel,  SQL, Python, and Power BI on a Zomato-like food delivery dataset.

Objective
To analyze Zomato food delivery operations, identify business problems, and provide actionable insights using various tools and technologies.

Tools & Technologies Used

Excel- Data Cleaning (Removing Duplicates, Trimming Text, Formatting Dates,text function)
SQL (MySQL / SQLite) Data Storage, Querying, Joins, Aggregation
python (Pandas + Matplotlib)-Data Transformation Visual Analysis
Power BI: Interactive Dashboards and Visual Reports

 Excel Tasks

 Removed duplicate rows
 Applied `TRIM()` to clean text data
 Used `TEXT(date, "yyyy-mm-dd")` for formatting
 Converted date/time into usable formats

  SQL Tasks

 Created `orders`, `customers`, `restaurants`, and `menu` tables
 Performed joins and filters
 Sample Query:
 sql

 Python Tasks

 Loaded all `.csv` files using a `for` loop
 formatted columns
 Loaded data into MySQL / SQLite database using `sqlalchemy`
 Created bar and pie charts using `matplotlib` & `seaborn`


 Power BI Tasks

 Built dynamic visuals using the cleaned data
 KPIs: Total Orders, Revenue, Top Restaurants
 Slicers by Date (Year only), Country, Category
 Added card visuals for: Total Revenue with `$`, Total Orders, Average Rating

 Key Business Questions Solved

 1. Which restaurant has the most orders?
 2. Which city contributes the highest revenue?
 3. What are the top 10 food categories?
 4. How do restaurant ratings correlate with order counts?
 5. Identify low-performing restaurants with high order volume but poor ratings.


 Zomato_Entity Relationship Diagram

![Zomato_Entity Relationship Diagram](https://github.com/user-attachments/assets/350c0c43-5dc9-4686-8aef-8f3832446d70)



Zomato_Dashboard

![Zomato_Dashboard](https://github.com/user-attachments/assets/c83c57db-d12e-48b6-aa78-2eaa520121ce)



