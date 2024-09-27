# Table Of Content
•	Project Overview
•	Data Source
•	Tools Used
•	Data Preparation and Data Cleaning
•	Data Analysis
•	Visualization in Power BI
•	Findings
•	Limitations

 
## Project Overview
The aim of this Retail project is to evaluate the profitability and performance of the retail business. By comparing the quantity and revenue derived from each products sold, we aim to identify areas of expansion, understand customer behaviour and demographic, identify market trends and opportunities, to enable management make informed decision on better inventory control as well as growth and diversification.
### Data Source
The primary data set utilized for this analysis is sourced from Retail online project csv file, comprising comprehensive sales data essential for the analysis.
#### Tools Used
•	Microsoft Excel: To clean the data.
•	SQL Server Management Studio: To analyze the data.
•	Power BI: To visualize the outcomes.
##### Data Cleaning Process in Excel.
1.	Opened the data using Microsoft Excel.
2.	Expand the whole column in the data set.
3.	Use the trim function to properly align the Stock code column
4.	Use the find and replace function to eliminate special characters in the description column.
5.	Use the find and replace column to eliminate the minus(-) sign on figures in the unit  price and quantity column 
6.	Use the proper function on description and country column to properly structure the words.
7.	Multiply unit price by quantity using the product function to get our total(sales)
###### Database Creation and Query Execution.
In SQL Server Management Studio (SSMS), a database named Abundance6 was created to organize and manage the dataset . Within this database, a table titled Retail Online was imported into the database, various queries were executed to answer specific research questions related to the data. 
# Questions Answered in the Data Analysis Process
1.	Total of each product bought.
2.	Most bought products.
3.	Least bought product.
4.	Total revenue gotten from sales.
5.	product with highest sales value.
6.	product with the least sales value.
7.	products with sales greater than the product with the least sales.
8.	countries that generated more sales.
9.	Time/day more sales took place.
10.	Total revenue generated by each product.

## Visualization in Power BI
After completing data cleaning in Microsoft excel and data analysis in SQL Server Management Studio, the results were exported to CSV files. This csv files were then used to create a visually appealing dashboard in Power BI.
The primary purpose of this Power BI dash board was to enhance understanding of the outcomes derived from the SQL data analysis. It is important to note that Power BI dash board is non interactive.
### Findings from the analyses
1. Total sales and quantity amounted to 11.59 and 6 million respectively.
2. There were higher record of sales from the United kingdom.
3. Paper craft, Little birdie was identified as the most bought product, generating a revenue of over 169 thousand.
#### Limitations
1.There were empty spaces.
2. Products with improper names were eliminated.
3. couldn’t identity product with least sales in SQL because of the empty spaces.



