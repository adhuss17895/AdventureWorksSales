# AdventureWorksSales

# AdventureWorks Sales Data
This dataset contains information about sales transactions, product models, product categories, and geographical details about customers.


Data Problems/Questions
Yearly Sales Trend Analysis: Analyze the total sales trend over the years and identify any significant growth or decline in sales.
Product Performance: Identify the top 5 performing products based on total sales and analyze their monthly sales trend for the last year.
Sales by Region: Compare total sales by geographical regions and highlight the best and worst performing regions.
Profitability Analysis: Calculate the profitability per product category and identify the most profitable category.
Market Basket Analysis: Perform a market basket analysis to find out which products are commonly purchased together.
Sales Channel Efficiency: Compare the efficiency of different sales channels (online vs. retail).
Customer Retention Analysis: Analyze the data to find out the retention rate of customers and factors affecting their loyalty.
Inventory Management: Analyze the inventory turnover rate and highlight products that are overstocked or understocked.
Cumulative Sales Analysis:
Create a DAX measure to calculate cumulative sales over a year. Use a variable to store the maximum date selected by the user and calculate sales up to that date.
Product Category Performance Comparison:
Develop a measure that calculates the percentage change in sales for each product category from the previous month. Use variables to simplify the DAX expression and enhance performance.
Dynamic Top N Analysis:
Implement a dynamic measure that allows users to select the top N products based on sales. Incorporate a slicer in your report for users to choose the value of N dynamically.
Profit Margin Analysis by Region:
Write a DAX measure to calculate the profit margin for each region. Include a dynamic filter to allow users to select specific regions or all regions, and visualize this data on a map.
Year-over-Year Growth Percentage:
Create a DAX measure that calculates the Year-over-Year growth percentage for total sales. Use a date slicer to let users dynamically select the year and visualize the growth trend.


Dynamic Ranking with Slicers:
Construct a DAX measure to dynamically rank customers or products based on sales. Allow users to adjust the ranking criteria through slicers, switching between sales, quantity, or profitability.
What-If Analysis for Discount Impact:
Implement a DAX scenario analysis to show the impact of different discount levels on profitability. Use a parameter table to allow users to select a discount rate and dynamically visualize the net profit impact.
Dynamic Measure Based on Date Ranges:
Create a measure that computes total sales within a user-defined date range. Utilize a DAX measure that adjusts based on the start and end dates provided by the user through a date range slicer.
Time Intelligence Analysis:
Calculate Year-to-Date (YTD), Quarter-to-Date (QTD), and Month-to-Date (MTD) sales and compare them with the previous periods.
Create a dynamic report that allows users to select the period and automatically updates the comparisons.
