# School_District_Analysis
Module_4 Project Data


## Project Overview & Challenge
In module challenge, School District Analysis, we need to help Maria to analyze using the student data to inform the school district on their budget and priorities.
After the analysis, Maria was informed that Thomas High School 9th grader results were altered on  in. We now need to show evidence of academic dishonesty; specifically, reading and math grades. The first step is to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once we've replaced the math and reading scores, we need to repeat the school district analysis that we did in this module and write up a report to describe how these changes affected the overall analysis.
 

## Resources
    - Data Source: schools_complete.csv  and students_complete.csv
    - Software: Conda version 4.10.0 using Jupyter Notebook Pandas and Numpy libraries

## Summary & Results

### School District Summary
![School_District_Summary](https://user-images.githubusercontent.com/80075982/114335205-243a3880-9b01-11eb-8a29-bf65410287bd.png)


Comparing the results of the charts above, district summary chart incuding all schools and district summary chart without Thomas High School, there is a 1% change on the % Overall Passing. When the Thomas High School grade was removed, overall passing percentage dropped to 1%

### School Summary

 Chart comparison of school summary including all schools and school summary without the 9th grades score, there was a significant change in Thomas High School % of passing math, passing reading and over all passing.From the original data, Thomas High School % is 90% and over. After removing the 9th grade scores, the % is under 70%.

    - Math and reading scores by grade
        -Math & Reeading score for the 9th grade was removed therfore no grades showing for the entire 9th grade
        -Reviewing the Top 5 results, as you can see from the charts, Thomas High School rank 2nd  with the 9th grade scores. When it 9th grade scores were no included, Thomas High School was on the list of top 5 
        -Revieiwing the Bottom 5 results, as you can see from the chart, the ranking was affected by schools

    - Scores by school spending
        - The scores by spending also shows that the % passing math, passing reading and overall passing with overall passing from 63% tp 56%

    - Scores by school size
        -The scores by school size shows a change of the % of passing math, passing reading and overall passing  with overall passing from 91% to 85%

    - Scores by school type
        - The scores by school type was also affected. The Charter % passing math, passing reading and overall passing went down. Although it is still at the 90% passing grade
   
## Challenge Summary

Changing the score or replacing Thomas High School 9th grade scores to nan, the % of passing math, passing reading and overall passing was affected . This shows that there are changes on the Math and reading scores, scores by school spending, school of size and school of type. On the top 5 and bottom 5 also shows a significant or important changes on the ranking of the each schools. It showed that Thomas High School ranked 2nd and after all the changes, Thomas High School was not on the top 5. The ranking order was also changed because Thomas High School is no longer on 2nd spot and not on the top 5 order.

    




