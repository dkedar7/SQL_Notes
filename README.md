# SQL Notes
This repository contains sample relational databases and sample queries.
The purpose of this repository is to serve as a quick reference guide to queries in SQL with results displayed to help understand subtleties. Visualizing the resulting views is particularly important to explain and remember some convoluted concepts like OUTER JOINS and the difference bertween the functions ROLLUP and CUBE.

For this reason, the tool of choice is Jupyter Notebook where one can type a query and see the result instantly.
This is only a list of different SQL queries and does not attempt to analyze data using SQL.

The sample database (chinook.db) has been obtained from https://github.com/lerocha/chinook-database. The diagram of this database is as follows:
![ok](http://www.sqlitetutorial.net/wp-content/uploads/2015/11/sqlite-sample-database-color.jpg)

Python library sqlite3 has been used to process SQL queries. The 'to_sql_query' functionality of Pandas helps view the resultiung views as a Pandas dataFrame.
