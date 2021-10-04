# Pewlett-Hackard-Analysis

## Overview of the analysis

Following our previous analysis of the intially provided data sets, we are given two more assignments which include determining the number of retiring employees per title, and identifying employees who are eligible to participate in a mentorship program. This will allow the resource department to plan accordingly as they prepare for this up coming shift in personel. 

## Results

### Number of Retiring Employees by Title

Our first assignment is to find the number of retiring employees per title. 

Using the code below, we created a Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955.

![](Queries/Capture1.PNG)

The results from our first code show that there are duplicate entries for some employees because they have switched titles over the years. We used the following query to remove the duplicates and keep only the most recent title for each employee. 

![](Queries/Capture2.PNG)

We then retrieved the number of employees by their most recent job title who are about to retire using the following query. 

![](Queries/Capture3.PNG)

The key results that we would like to keep in mind are: 

- Total of 90,398 will be retiring in the near future.
- 29,415 Senior Engineers, 28,254 Senior Staff, 14,222 Engineers, 12,243 Staffs, 4,502 Technical Leaders, 1,761 Assistant Engineers and 2 Managers. 

### Employees Eligible for Mentorship Program

Our second assignment is to identify employees who are eligible to participate in the mentorship program. 

We had to create a Mentorship Eligibility table that holds the employees who are eligible to participate in a mentorship program using the following query. 

![](Queries/Capture4.PNG)

As a result, we find a total of 1,549 employees are eligeable to participate in the mentorship program. 

## Summary 

In the end, 



