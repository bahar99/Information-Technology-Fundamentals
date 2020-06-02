# Movie_Rating_Spreadsheet
In this assignment we will go over the attached spreadsheet, and analyze the data inside it using python.

## Overview
There are 5 deliverables for this assignment. Each deliverable represents a different analysis of the data pro-
vided. The first three deliverables represent non-personalized summary statistics; The last two represent a
demographic analysis to explore whether using gender would be wise given this dataset.


## Requirements
For This Project You Need below Requirements :

 - Python
 - Pandas
For installing pandas package in Ubuntu :
```
pip install pandas
```

## Steps To Run 
You can run this code simply with :
```
python3 HW2.py
```
**Rec_data.csv** is also atached to the project.

## Explanation 
I answered each question in specific function (every function has a comment showing it's question).I start with reading the .csv using pandas . Function Mean_Rating computes the mean rating using python mean function for every coloumn,then sorts and reverse the result.Function Rating_Count do the same thing but counts the number of filled cells of each coloumn using python count function.Function Rating_of_4plus counts the number of filled cells also it counts number of cells with number equal or higher than 4 ,then computes the percentage.Functions Mean_Rating_Difference and Rating_of_4plus_difference work like function 1 and 3 but we compute mean and number of 4pluses separately for men and women .This functions compute overall ratings and percentages for each gender separately and also compute difference between men and women.
At the end all the functions write their outputs in a file.
