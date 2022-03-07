# School_District_Analysis

## Project Overview
The goal of this project was to analyze key metrics for a specific school district. The request is to provide the key metrics in a presentable table format. The primary asks include:

- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school

We are tasked with ensuring the data is clean and correct. However, the initial data is later determined to have some significant anomolies related to the 9th grade students at Thomas High School. After our initial summary of the data we were required to recontruct our tables and remove the offending parties.
We will show below the impact the metrics had when accounting for & removing the potential fraudulent data.

## Resources
- Software
Jupyter 6.4.5
Python 3.6.7

- Libraries
Pandas
Numpy

- Raw Data
schools_complete.csv
students_complete.csv

## Analysis Results
**Impact Analysis**

*For reference, if the screenshot is tagged as 'Original' this is all of the data from the sources. If the screenshot is tagged as 'Updated' this is screenshot of the summary with the 9th grade students from Thomas High School data removed.*

**District Summary (Original)**

![District Summary (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/District%20Summary%20(Old).png)

**District Summary (Updated)**

![District Summary (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/District%20Summary%20(New).png)

- Removing the data did not have a significant impact on the overall numbers. % Overall Passing and % Passing Math took the biggest hits.

**Top Schools (Original)**

![Top Schools (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Top%20Schools%20(Old).png)

**Top Schools (Updated)**

![Top Schools (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/District%20Summary%20(New).png)

- Top school ranking did not change order though Thomas High School % Overall Passing did decrease.

**Bottom Schools (Original)**

![Bottom Schools (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Bottom%20Schools%20(Old).png)

**Bottom Schools (Updated)**


![Bottom Schools (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Bottom%20Schools%20(New).png)

- Since Thomas High School was not in the bottom five these numbers were not impacted.

**Math Scores (Original)**

![Math Scores (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Math%20Scores%20(Old).png)

**Math Scores (Updated)**


![Math Scores (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Math%20Scores%20(New).png)

- Thomas High School 9th graders Math Percentages is correctly showing as ‘nan’.

**Reading Scores (Original)**

![Reading Scores (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Reading%20Scores%20(Old).png)

**Reading Scores (Updated)**

![Reading Scores (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Reading%20Scores%20(New).png)

- Reading scores not impacted.

**Spending Summary (Original)**

![Spending Summary (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Spending%20Summary%20(Old).png)

**Spending Summary (Updated)**

![Spending Summary (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Spending%20Summary%20(New).png)

- The $630-644 category was slightly impacted.

**School Size (Original)**

![School Size (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/School%20Size%20(Old).png)

**School Size (Updated)**

![School Size (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/School%20Size%20(New).png)

- The Medium (1000-2000) category was slightly impacted.

**School Type (Original)**

![School Type (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/School%20Type%20(Old).png)

**School Type (Updated)**

![School Type (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/School%20Type%20(New).png)

- Charter category was slightly impacted

## Summary

- The District Analysis changes were all under 1% which was to be expected considering the total 9th grade students at Thomas High School only represent a little over 1% of total students.
- The Top School ranking was not affected even though Thomas High School decreased slightly overall.
- Scores by School Spending changed slightly in the $630-644 category.
- Scores by School Size changed slightly in the Medium (1000-2000) group.
- Scores by School Type changed slightly in the Charter type.

