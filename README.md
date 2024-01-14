# SuperStore_BI

# Problem Statement
This dashboard helps the global superstore owners know their sales, customers, their best selling products, as well as other meaningful insights. This dashboard helps the store 


# Data Cleaning
At first after importing the excel file (global_superstore.xlsx) in power BI. We open our power query editor from the home tab.

From the 'People' and 'Returns'table we fix the column heads by selecting use first row as headers.


# Creating Necessary Columns and  Minor changes
- Step 1: Creating a column named 'Delivery Days' in the 'orders' table using custom column from the home tab.The syntax will be (Ship Date - Order Date). And change the format of its data type into whole number from the home tab.
  
- Step 2: Go to the Table view and after clicking the 'Sales' column from the table, click on the format option from column tools tab which is set to general. Then change it to currency and then in dollars.

- Step 3: Creating a column named 'Year' in the 'orders' table using custom column from the hometab. The syntax will be Date.Year([Order Date]).

- Step 4: Creating a conditional column named 'Return Orders' in the 'Returns' table from add column tab in power query editor. The condition is if the 'returned' column of the 'Returns' table equals 'yes' then the output will be 1 else 0.Then go to column tools tab after selecting the 'return orders' column and set the data type to whole number.


	
# Goals of our Dashboard

- step 1: To show the sales, quantity, avg delivery days and returned orders for a period of 4 years(2012 - 2015).

- step 2: To show the map where we can see the sales by region.

- step 3: To show the profit(Top 5) by the product name i.e top 5 profit products using stacked bar chart.

- step 4: To show the loss(Top 5) by the product name i.e top 5 loss products using stacked bar chart.

- step 5: to show the sales by segment i.e corporate, home office, consumer using pie chart.

- step 6: to show the sales by market i.e asia pacific,europe,usca,latam,africa using pie chart.

- step 7: to show the customers name(Top 10) by profit margin using stacked column chart.















