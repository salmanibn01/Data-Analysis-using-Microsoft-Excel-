# Data-Analysis-using-Microsoft-Excel-

## Data cleaning
-- Finding the duplicates
Select the entire spreadsheet. Then remove the duplicates using clicking "remove duplicates" option while selcting all the columns
-- Cleaning the "marital status" column
Select column B > press ctrl+H > Find and Replace box pops up > Find what >> S >> replace with Single >> Find what >> M >> Replace with Married
-- Adding a new "Age Bracket" column using IF function 
=IF(L2<31, "Adoloscent", "Invalid")
-- Using nested IF function to a "middle age" group
=IF(L3>=31, "Middle age", IF(L3>31, "Invalid","Adoloscent"))
