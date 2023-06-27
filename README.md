# Sales_data_dashboard

Dataset is available at PowerBI official site and is open source can be used for experimenting and learning

The data set contains 3 tables namely orders, returns and people.

Orders Table contain 24 columns(fields) and 51,290 Rows(records). There was not much of cleaning required in this dataset only the postal field had the null value.
I have avoided cleaning it since it was not required to clean it and it was not used in making of the dashboard.
using the order date I had created 3 more columns that were delivery days(to know how many days it took to get shipped after placing the order), year and month.

returns table contained 3 columns and had around 1000 rows. Here I have created one additionaly columns returned order (since the returned column contained categorical
value i.e. "Yes" so it was converted into Numerical field for the making of the dashboard. )

Person table contains 2 column and 24 rows.

The relation between the table were made using the OrdersID column as Primary key from the Orders table, OrdersID as foreign key in the Returns table, 
People Table was connected with the region table using region as Primary Key in return table and region as forgein key in People table.

The Dashboard contains 4 KPIs (Total sales, Total Quantity, Avg. Delivery days and total returned orders.
Further Information can be seen from the dashboard itself.
