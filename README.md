# st2195_assignment_3
Practice Assignment 3

Download the _Data Expo 2009_ data from the _Harvard Dataverse_ [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7] and construct an **SQLite Database** called “airline2.db” with the following tables:
1. ontime (with the data from 2000 to 2005 – including 2000 and 2005)
2. airports (with the data in airports.csv)
3. carriers (with the data in carriers.csv)
4. planes (with the data in plane-data.csv)

Create a **GitHub** repository called “st2195_assignment_3” that includes:

1. A "README.md" file with a short markdown description of this assignment and a reference to the _Data Expo 2009_ data, and the _Harvard Dataverse_ [_1 point_]

2. A folder called “r_sql” with a R code for constructing the database (from the csv inputs) and executing the following queries. The latter should be done both using **DBI** and **dplyr** notation [_1.75 points each_]

a. Which airplanes has the lowest associated average departure delay (excluding cancelled and diverted flights)?
b. Which cities has the highest number of inbound flights (excluding cancelled flights)?
c. Which companies has the highest number of cancelled flights?
d. Which companies has the highest number of cancelled flights, relative to their number of total flights?

3. A folder called “python_sql” with a Python version of the code in point 2, based on **sqlite3** [_1.75 points_]

4. A simplified solution for the query in point 2(d) in either R or Python (placed either in the R or Python “*_sql” folder) [_1.75 points_]

Note that the database file should not be placed in the **GitHub** repository (it is quite large). Also, the R and Python scripts should save the output of the queries in csv within their respective folders [_1 point each_]
