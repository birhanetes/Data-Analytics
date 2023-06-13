# Data Cleaning and Pivot Table in Excel

/*
The dataset used in this project comes from the following source:
https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr under a Public Domain license. 
*\

**Part 1: Cleaning the data**

1. After downloding the file, I Sorted out the widths of all columns so that the data is clearly visible in all cells.

2. I used the Filter feature to look for blanks and remove all empty rows from the data.

3. Using the Conditional Formatting (Remove Duplicates) feature to look for and remove any duplicated records from the data.

4. I also checked for spelling mistakes in the data and fixed them.

5. I used the Find and Replace feature to remove all double-spaces from the data.
 
6.  Since the data has not been imported correctly, the department names are splited over two columns in the data. To fix this, I used Flash Fill to reduce the department names to just one column, and then removed any unnecessary columns.


**Part 2: Create table and Use the aggregated functiuns**

1. Formated the data as a table

2. Used AutoSum to calculate values to find the following values for column ‘C’ and record each of the values:
SUM, AVERAGE, MIN, MAX, and COUNT


**Part 3: Create Pivot Table and Analyze the data**

1. I created a Pivot Table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department. Then, I used the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count. See "Pivot1".

2. In "pivot2", I added the Equipment Class field below the Department field so that the different vehicle types appear under each department with their respective counts.

3. In "pivot3", I added the Equipment Class field above the Department field so that the different vehicle types appear first, with the different departments listed underneath each vehicle type with their respective counts.



