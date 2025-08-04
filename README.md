# EL-Task1
This repository contains the files related to task 1-4th August 2025
**Data and Format Modifications**
1)	First, the data was read into Python by using the function in the pandas library called read_csv.
2)	The data was read using the tab separator (\ t) and saved as a dataframe. With this code, the data became more readable.
3)	Then, by applying the isnull() function the null values were read. By using the sum function with isnull() the total null values were counted.
4)	There were a total of 24 null values in the Income column
5)	Then, the null values were replaced with the mean of the Income column.
6)	After the changes, the dataframe was exported to a CSV file.

**Later, the file was formatted with the tools in Excel**
1)	All the column names were modified to improve the readability
2)	The datatypes of a few columns were updated. I.e., date datatype and Currency.
3)	The 24 cells in the Income column were modified from a number datatype to a currency datatype by using the find and replace functionality of Excel.
4)	All the columns were then converted to a table to improve the formatting.
