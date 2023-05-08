Download Link: https://assignmentchef.com/product/solved-sql-server-database-called-busdriver
<br>
<p class="ui header product-top-header" title=" SQL Server database called BusDriver Solution">Write a script to create a new SQL Server database called BusDriver, which contains the three tables with columns and relationships as defined in the above figure. Save this script file as BusDriver.sql and upload it here for grading.

Your script must be able to be executed as a whole to have the database and all tables created at once with no errors. *It’s important you include a GO and USE command after the database is created and before any table is created. See p.361 for example of the script that createa the AP database and its tables.

For the purpose of this assignment, all relationships must be implemented such that (1) when a primary key value is updated, its corresponding foreign key value is updated automatically, and (2) if a primary key value is referenced by a foreign key table, the row with this primary key value cannot be deleted, i.e., no action.

Column specifications are given below:

Driver table

DriverID: int

Name: varchar(60), not null

Age: int and must between 25 and 60, not null

BusNo: char(3), null

Bus table

BusNo: char(3)

Mileage: int, must be positive, null

Model: char(2), null

BusModel table

ModelCode: char(2)

ModelName: varchar(15), null

TotalSeats: int, null, must be at least 20 but no more than 50

5/5 - (1 vote)