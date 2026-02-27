# SQL-Data-Warehouse-Project
In this project, I take a company's messy data and then clean it up, removing all empty spaces, standardising the data etc. 
This makes the data able to be used by data analysts.

Spesicically what the code does:

=== "SILVER LAYER GENERATION"
This takes the dirty 'bronze' CSV files, in SQLite, and it cleans it up and then creates tables, inerting it into a cleaned stage two, the 'silver' layer.
