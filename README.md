# Project-1-Data-analysis-with-Excel
Analyzing Fleet equipment inventory for Montgomery County.

## Part 1
This assignment involved loading CSV file in Excel for the web, converting it to an Excel format and cleaning and preparing the data.

Major Tasks performed:

Saved the CSV file as an XLSX file
Column widths: Sorted out the widths of all columns so that the data is clearly visible in all cells.
Empty rows: Used the Filter feature to look for blanks and remove all empty rows from the data.
Duplicate records: Used Remove Duplicates feature to look for and remove any duplicated records from the data.
Spelling: Checked for spelling mistakes in the data and fixed them.
Whitespace: Used the Find and Replace feature to remove all double-spaces from the data.
Department names: When the data was converted from its data source, the department names (see correct list below) didn’t import correctly and they were split over two columns in the data. I used Flash Fill to reduce the department names to just one column, and then removed any unnecessary columns.

## Part 2
The next part of then project involved cleaning and preparing the data and then creating some pivot tables from it to help you analyze the data.

Major Tasks performed: 

Format the data as a table: Used the Format as Table option to format the data as a table.
Use AutoSum to calculate values: Used AutoSum to find the following values for column ‘C’ and record each of the values:
Create a Pivot Table: Used the PivotTable feature to create a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department.
Sort the pivot table data: Used the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count.
Make two more pivot tables exactly the same as task 3: Followed the same steps you performed in Tasks 3 and 4 to create two more identical pivot tables so that you end up with 3 worksheets that contain identical pivot tables.
Analyze data in the pivot table: Used the PivotTable Fields pane to manipulate and analyze data in the two copied pivot table as follows:

In pivot table 2 added the Equipment Class field below the Department field so that the different vehicle types appear under each department with their respective counts.
Collapse all fields except the top one - Transportation
In pivot table 3 added the Equipment Class field above the Department field so that the different vehicle types appear first, with the different departments listed underneath each vehicle type with their respective counts.
Collapse all fields except the top one - CUV

The dataset used in this lab comes from a source under a Public Domain license provided by coursera.
