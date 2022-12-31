https://www.dropbox.com/scl/fi/uggja0jbvkc21z7v43yw3/online_retail.xlsx?dl=0&rlkey=s80sd5z48baf9u1zu26cxnom4

In this project I analyzed retail sales data with MS Excel and Power BI. The above link is for the excel workbook that was too big to fit in the repository. All other files are in the repository.  

First I verified data integrity by removing any duplicate rows. Then I filtered out any rows in the "Quantity" column that were less than 1, and any rows in the "UnitPrice" column that where less than 0.

After cleaning the data, I created a new column called "Revenue" by multiplying "Quantity" by "UnitPrice" for the first row, then populating the remaining rows in that column with the same formula.

Now we move to Power BI. I created four visualizations to gain insights into past sales:
1. A line chart showing total revenue for the entire year (2011)
2. A clustered bar chart showing the top ten countries by total revenue. Quantity was also included.
3. A bar chart displaying top ten customers by revenue generated.
4. A map chart showing all countries by ratio of total revenue generated.
