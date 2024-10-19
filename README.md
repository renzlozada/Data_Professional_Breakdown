# Project Data Professional Breakdown

## Problem Statement

This dashboard helps break down the Data Professionals in the Industry. It helps the different salary ranges and satisfactory ratings given by our Data Professionals. Through different rating, we get to know if they are happy with their current salary or if they would like improvement on their career. This Dashboard also shows the most common Programming Language and Analytical Tools they use for their daily tasks. 

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is an excel file
- Step 2 : Open power query editor & in view tab under Data preview section, observed that data type for `Salary` is in String
- Step 3 : Made changes to the salary by splitting the columns, creating a new column for `Average Salary`
- Step 4 : It was observed that multiple columns has empty values. The following columns were deleted for that reason: `Browser`, `OS`, `Reference`.
- Step 5 : For calculating the average salary, input has been taken for the (minimum amount + maximum amount) / 2
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : A Treemap has been added to easily select the country to isolate the result of the survey.
- Step 8 : Three gauge visuals were added to the Dashboard.
- Step 9 : Two card visuals were added to the canvas, one representing average age of survey takers & other representing the count of survey takers.
- Step 10 : A bar chart was also added to the report design area representing their favorite Programming Languange. 
- Step 11 : A stack bar chart was also added to determine the average salary for each job position.
 
# Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/user-attachments/assets/9f122f70-d8ef-4f82-8986-ce7902adbed7)

# Insights

A single page report was created on Power BI Desktop

## [1] Total Number of Survey Takers = 630

Average Age of Survey Takers = 29.87

Average Happiness with Current Position = 5.86/10

Average Happiness with Work/Life Balance = 5.74/10

Average Happiness with Salary = 4.27/10

## [2] Bar Charts

Favorite Programming Language = Python

        According to the data, the average user uses Python as their preferred programming Language, 
        do to its robust features for data processing.

Difficulty to Break into Data

        An Average user is on a gray area whether breaking into Data is difficult or easy.

Average Salary by Job Title

        A Data Scientist is the leading Job Title for the highest salary amongst the other Data Position. 
        Data Engineer going on the 2nd position while 
        Data Architect for the 3rd position
