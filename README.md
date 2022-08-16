Excel for Data Analysis - Cleaning Montgomery Fleet Equipment Data

Data Description
The dataset used in this project comes from the following source: https://data.world/montgomery-county-of-maryland/1f06ef22-f2db-433c-b589-59afcab814ce under a Public Domain license. This data originates from the US Open Data Portal at https://data.world/datagov-us.

Using a modified subset of that dataset

Project Scenario
In this project, you will be following the scenario of a recently hired Junior Data Analyst in a local government office, who has been tasked with importing some data from another department which relates to inventory information about their fleet of vehicles. The data is in comma-separated value (CSV) format and the data also needs cleaning up before you can start to run any kind of analysis on

Part 1
Tasks to perform:

Save the CSV file as an XLSX file: Click the 'Edit Workbook' button in the ToolTip to save the file as an XLSX file. The file is converted when you click 'OK' in the prompt.

Column widths: Sort out the widths of all columns so that the data is clearly visible in all cells.

Empty rows: Use the Filter feature to look for blanks and remove all empty rows from the data.

Duplicate records: Use either the Conditional Formatting or Remove Duplicates feature to look for and remove any duplicated records from the data.

Spelling: The original source file data has not been checked for errors in the spelling. Check for spelling mistakes in the data and fix them.

Whitespace: Use the Find and Replace feature to remove all double-spaces from the data.

Department names: When the data was converted from its data source, the department names (see correct list below) didn’t import correctly and they are now split over two columns in the data. Use Flash Fill to reduce the department names to just one column, and then remove any unnecessary columns.

Save your workbook: Use 'Save As' to save your completed workbook as Montgomery_Fleet_Equipment_Inventory_FA_PART_1_END.XLSX

Department Department
Board of Elections Economic Development
Circuit Court Environmental Protection
Community Engagement Cluster Finance
Community Use of Public Facilities Fire and Rescue
Consumer Protection General Services
Correction and Rehabilitation Health and Human Services
County Executives Office

Part 2
Tasks to perform:

Format the data as a table: Use the Format as Table option to format the data as a table.

Use AutoSum to calculate values: Use AutoSum to find the following values for column 'C' and record each of the values:

SUM
AVERAGE
MIN
MAX
COUNT
Create a Pivot Table: Use the PivotTable feature to create a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department.

Sort the pivot table data: Use the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count.

Make two more pivot tables exactly the same as task 3: Follow the same steps you performed in Tasks 3 and 4 to create two more identical pivot tables so that you end up with 3 worksheets that contain identical pivot tables.

Analyze data in the pivot table: Use the PivotTable Fields pane to manipulate and analyze data in the two copied pivot table as follows:

In pivot table 2 add the Equipment Class field below the Department field so that the different vehicle types appear under each department with their respective counts.
Collapse all fields except the top one - Transportation

In pivot table 3 add the Equipment Class field above the Department field so that the different vehicle types appear first, with the different departments listed underneath each vehicle type with their respective counts.
Collapse all fields except the top one - CUV

Save your workbook: Use 'Save As' to save your workbook as Montgomery_Fleet_Equipment_Inventory_FA_PART_2_END.XLSX
