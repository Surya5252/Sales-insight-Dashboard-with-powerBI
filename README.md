# Sales-insight-Dashboard-with-powerBI
## Problem statement

AtliQ Hardware is a company that delivers computer hardware and peripherals to clients across multiple branches in India. The sales director is struggling to understand the company's performance and identify the challenges causing sales to decline gradually. When he contacts regional managers for updates on sales and market conditions, they often struggle to interpret the numbers in Excel files, leading to frustration and difficulty in making informed decisions.

## Solution

The sales director of AtliQ Hardware decided to build a PowerBI dashboard to convert data into visual representations, enabling data-driven decisions. To accomplish this, he hired a team of data experts to complete the task.

### AIMS Grid

Using the AIMS grid project management tool, we clarified the project's purpose, identified stakeholders, defined the end result, and established the success criteria.

## Steps Followed in this project

1. **Project Planning**: Learned about the AIMS grid for effective project planning.
2. **Data Retrieval**: Used MySQL to extract data from the database into Power BI.
3. **Data Cleaning**: Cleaned the data using Power Query.
4. **ETL Process**: Performed the Extract, Transform, and Load (ETL) process.
5. **Measure Creation**: Created necessary measures and used them to build visuals in Power BI.
6. **Currency Conversion**: Handled multiple currencies in transactions by performing currency conversion to standardize the data.
7. **Data Validation**: Validated the data to ensure accuracy.
8. **Data Modeling and Visualization**: Modeled the data and created visualizations in Power BI.

## Major Changes/Customizations Made

1. **Resolved the ‘(blank)’ Issue**: Addressed the issue in the products section by deleting the original products table and replacing it with a self-modified products table. In this new table, I added products ranging from Prod280 to Prod339 and assigned them random product types (either ‘Own Brand’ or ‘Distribution’).
2. **Merged Tables for Enhanced Insights**: Combined the original modified ‘sales_transaction’ table with a new version that includes additional fields such as profit margin, cost price, etc.

### Insights

1. **Overall Performance**: Over the last 4 years, the company generated total revenue of ₹985M, with a total profit margin of ₹24.7M (2.5% profit margin) and a sales quantity of 2M units. In 2020 alone, the company achieved ₹142M in revenue by selling 350K units, earning a profit of ₹2.1M.
  
2. **Top Market**: Delhi NCR is the largest market in terms of revenue, contributing ₹520M (52.8% of total revenue) over 4 years. However, the profit margin in Delhi NCR is only 2.3%.
  
3. **Highest Profit Margin**: In 2020, Bhubaneswar recorded the highest profit margin at 10.48%. In terms of Profit Contribution %, Mumbai leads with 23.89% of the total profit contribution.
  
4. **Lowest Profit Margin**: Bengaluru has the lowest profit margin over the 4 years, at -20.8%. It also has the lowest Profit Contribution %, contributing -0.3% to the total profit.
  
5. **Top Customers**: Electricalsara Stores is the biggest customer, generating ₹413M in revenue over the 4 years.
  
6. **Top Products**: Prod318 is the highest revenue-generating product, with total revenue of ₹69M over 4 years.
  
7. **Product Type Performance**: Both Distribution and Own Brand product types generated equal revenue of ₹494M each over the entire 4 years.
  
8. **Revenue and Profit Trends**: The revenue trend shows a significant decline in June 2020 compared to the previous year, with the lowest profit margin recorded in April 2020.

### Key Learnings

1. Gained an understanding of real-world business datasets and their complexities.
2. Acquired skills in writing major analytical queries using MySQL.
3. Learned how to connect database tables to Power BI and effectively clean and modify data using Power Query.
4. Developed knowledge of practical DAX functions and how to create measures in Power BI.
5. Gained experience in creating and interpreting key analytical visuals and reports.

## Final result 

#### Dashboard KPI Page

-------
<img src= "https://github.com/Surya5252/Sales-insight-Dashboard-with-powerBI/blob/main/Key%20Insights.png" class="center">

#### Dashboard Performance Insights
-------
<img src="https://github.com/Surya5252/Sales-insight-Dashboard-with-powerBI/blob/main/Performance%20Insights.png" class="center">

 #### Dashboard Profit Analysis
 -------
 <img src="https://github.com/Surya5252/Sales-insight-Dashboard-with-powerBI/blob/main/Profit%20Analysis.png" class="center">
 




 

