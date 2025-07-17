# Internet Sales Analysis Using PowerBI
 Analysing the internet sales datawarehouse of AdventureWorks2022 database using PowerBI

I uploaded the internet sales datawarehouse of AdventureWorks2022 database in Sql Server and then connected the PowerBI to Sql Server to load the data from it.

![Sales Page](/Sales.png)
First, I made cards to show some importnat numbers of calculated measures (DAX).
![Number Of Orders](/noOfOrders.png)
![Total Due](/TotalDue.png)
![Total Freight](/TotalFreight.png)
![Total Quantity](/TotalQuantity.png)
![Total Subtotal](/TotalSubtotal.png)
![Total Tax](/TotalTax.png)
Second, I used a donut chart to show No Orders by status.

Third, I used a stacked column chart to compare between ship method by the number of orders.

Forth, I used a clustered bar chart to compare between products by the number of orders. I used here the Product Hierarcy so you can drill down to instead of camparing between products you can compare by subcategory or category.

Fifth, I used a pie chart to compare between the number of orders that has been done online or not. And for this chart I created this tooltip to show the number of orders done by this method.
![Tooltip](/Tooltip.png) 

Sixth, I used a clustered column chart to compare between territories by count of orders and sum to total due.

Finally in this page, I used a line chart to show the count of orders over time by order date, due date and ship date.

***In Maps page i made three bookmarks***
![Maps No of orders Bookmark](/MapsFileNoOrdersBookmark.jpg)
I used a map to compare between territories by number of orders.
![Maps Total Due Bookmark](/MapsFileTotalDueBookmark.jpg)
I used a map to compare between territories by sum of total dues.
![Maps Sales Persons Bookmark](/MapsFileSalesPersonBookmark.jpg)
I used a map to compare between territories by number of sales persons.

![Filter Page](/Filters.png)
First, I used a clustered column chart to compare between the sales persons by number of orders done by them.

Second, I used a clustered bar chart to compare between products by total quantity sold. I used here the Product Hierarcy so you can drill down to instead of camparing between products you can compare by subcategory or category.

Third, I used a line and stacked column chart to compare between months by number of orders and total due.

Forth, I used a 100% stacked column chart to compare between categories by total due, total frieght, total subtotal and total tax.

Finaly in this page, I made two slicers to filter by territory and by date hierarcy (years, quarters, months, days)

***Finall Thing I have done in this project that I made buttons in all pages to refer to the another pages.***