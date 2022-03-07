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

- For the entire district the Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing all decreased with the removed data. The Average Reading score also technically went down but since the number is rounded the differences are not visible. 
There are only 461 students in 9th grade at Thomas High School so it is not surprising the overall percentages only dropped a few basis points considering the Total Students number is 39,170. 

**Top Schools (Original)**

![Top Schools (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Top%20Schools%20(Old).png)

**Top Schools (Updated)**

![Top Schools (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Top%20Schools%20(New).png)

- The top five ranking of schools (based on % Overall Passing) did not change. While Thomas High School's % Overall Passing did decrease slightly it was not enough to knock it out of second place.

**Bottom Schools (Original)**

![Bottom Schools (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Bottom%20Schools%20(Old).png)

**Bottom Schools (Updated)**

![Bottom Schools (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Bottom%20Schools%20(New).png)

- Since Thomas High School is not one of the bottom five schools, even after accounting for the potentially fraudulent data, there were no changes in this section. 
**Math Scores (Original)**

![Math Scores (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Math%20Scores%20(Old).png)

**Math Scores (Updated)**

![Math Scores (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Math%20Scores%20(New).png)

- 9th grade for Thomas High School correctly showing NaN. No other numbers affected.

**Reading Scores (Original)**

![Reading Scores (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Reading%20Scores%20(Old).png)

**Reading Scores (Updated)**

![Reading Scores (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Reading%20Scores%20(New).png)

- Reading scores not affected.

**Spending Summary (Original)**

![Spending Summary (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Spending%20Summary%20(Old).png)

**Spending Summary (Updated)**

![Spending Summary (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/Spending%20Summary%20(New).png)

- Small changes to the scores for the group $630-644 (less than 1%). 

**School Size (Original)**

![School Size (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/School%20Size%20(Old).png)

**School Size (Updated)**

![School Size (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/School%20Size%20(New).png)

- The changes affected the Medium(1000-2000) group slightly (less than 1%)

**School Type (Original)**

![School Type (Original)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/School%20Type%20(Old).png)

**School Type (Updated)**

![School Type (Updated)](https://github.com/gonzalesbarrett/School_District_Analysis/blob/main/PNGs/School%20Type%20(New).png)

- Since Thomas High School is a Charter school there were some small changes (less than 1%) to the results

## Summary

- For the district analysis, all scores changed on average .05% or less. 
- Top school ranking was not affected even though Thomas High School's % Overall Passing did decrease slightly
- The School Spending scores were slightly impacted in the $630-644 section.
- The School Size scores were slightly affected in the Medium category.
- The School Type scores were slightly affected in the Charter section.