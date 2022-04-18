# MLS_Salary_Project

# Objective
Analyze yearly salary trends for Major League Soccer (MLS) clubs since the league's beginning in 2007

## Goals
1.) Identify any differences (if any) in salary growth based on player position

2.) Identify any differences (if any) in salary growth based on club

3.) Compare the growth of average salaries for all MLS clubs to the growth in the number of MLS clubs

### Excel File
The Excel file contains salary information for all players in the MLS for each season from 2007-2017. Dataset was found [here](https://github.com/data-is-plural/mls-salaries) in CSV formats for each individual season. I utilized Excel's PowerQuery to join these CSV files for each season into a single table, adding a "Year" column to help analyze salary accross seasons. I then removed duplicate player values for any players with the same Team, First & Last Name, and Year. Finally, I added a "Player Position" column to clean the original "Position" column and classify players into the 4 main position categories. Data from this file was utilized in Tableau to build a dashboard.

### Tableau Files
The "MLS Growth" file is a dashboard that helps compare the growth of avg. club salaries in the MLS with the growth in number of MLS clubs (satisfying goal #3 of this project). Users have the option to filter the avg. club salaries by player position (satisfying goal #1 of this project) and by various MLS clubs (satisfying goal #2 of this project). 

The "Avg Yearly MLS Club Salary" file is a dynamic table that allows the user to show the avg. salary for each club, filtering by year.

# Skills Used
Tableau, Dual Axis Charts, PowerQuery
