# Coding Assessment 2023 Fall - Super
### Problem Statement

The provided dataset cines in a stringified table where delimiter is ';' and line_terminator is '\n'.

The main task is to create a new table based on the provided data with certain requirements, as detailed below:

1. FlightCodes column: Some values are null. Flight Codes are supposed to increase by 10 with each row so 1010 and 1030 will have 1020 in the middle. Fill in these missing numbers and make the column an integer column (instead of a float column).

2. To_From column: Should be split into two separate columns for better analysis! Split on '_' to create two new columns respectively. Also, the case of the column is not very readable, convert the column into capital case.

3. Airline Code column: Clean the Airline Codes to have no punctuation except spaces in the middle. E.g. '(Porter Airways. )' should become 'Porter Airways'.

### Solution

The solution provided utilizes `**pandas**` library in Python for manipulation and analysis of data, and also cleaning the datas for requirements.

### Dependencies
- Python 3
- pandas
- re

### Execution
The solution can be run in any Python 3 environment where the dependencies are installed. 
