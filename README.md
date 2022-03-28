# School_District_Analysis

## Overview of the school district analysis: 

The project of school district analysis analyzed how students are performing in math and reading, plus the size of the school budgets, and how the school performs at school and district levels. This analysis will assist the board and superintendent in decisions regarding the school budgets and priorities.

### Purpose
The purpose of this project is to evaluate the math and reading grades for Thomas High School students. A key dataset utilized in evaluating the analysis, indicates that there is evidence of academic dishonesty, as the grades for ninth grade students appear to have been altered. A comparative analysis was completed to indicate whether replacing math and reading scores for Thomas High School ninth grade students with NaNs, will affect the outcome of the analysis.


## Results:

    How is the district summary affected?
The district summary comparison shows that the main difference between the initial and updated analysis is that the average math score decreased by 0.1% and the percent of students who passed math decreased by 0.2%. The average reading score remained the same, but the percent of students who passed reading decreased by 0.3%. The overall percent of students who passed only varied by 0.1%.

    How is the school summary affected?
The school summary shows that Thomas High School was the only school where scores were affected. There was a slight difference with the average math and reading scores, however the most significant changes in the data were with respect to the percentage of students who passed math and reading. The initial analysis shows that the percentage of Thomas Jefferson Students who passed math dropped from 93.272171% down to 66.911315% and the percentage who passed reading also dropped from 97.308869% to 69.663609%.

    How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 - Replacing the scores of math and reading for ninth graders' in Thomas High School, their performance ranking dropped from having the second place percentage of overall students passing (90.94801%) down to having the eighth place percentage of overall students passing (65.07645%), in the school district.

    How does replacing the ninth-grade scores affect the following:
 - Math and reading scores by grade: Ninth grade math and reading scores dropped, when the scores were replaced to reflect NaN in the dataset. 
 - Scores by school spending: The spending range of $630 - $644 per student, at Thomas High School, remained the same. However, the percentage of overall students passing dropped from 79% to 63%, in that spending range.
 
 - Scores by school size: Thomas High School is a medium sized school, that falls within the 1000 - 2000 bracket of school size. Average math and reading scores within this bracket remained the same, however the percentage of students passing math and reading, both dropped by 6%. As such, schools within the medium school size bracket experienced a drop in percentage of overall students passing by 6%.
 
 - Scores by school type: Charter schools consistently performed better than District schools. Although, replacing the ninth-grade scores did not have an impact on the average or percentage of passing math and reading scores, the percentage of overall students passing dropped by 20% for District Schools.
 
## Summary
By conducting the analysis, four major changes occurred in the updated school district analysis after the reading and math scores for ninth grade students were replaced with NaNs for Thomas High School.

1. Utilizing NaN is a way to find inconsistencies in a dataset, without skewing the data by having to enter zeros in its place.

2. School spending ranges per student does not impact the math and reading scores.

3. School size does have an impact on testing scores. The larger the school, the lower the test scores and percentage of overall students passing occurs. 

4. Charter Schools are stronger in testing performance than those of District Schools, as they have higher testing scores and percentages of overall students passing. 



### Resources Used for analysis
* **CSV Files:** 
[schools_complete.csv](https://github.com/RabidZippers/School_District_Analysis/blob/main/Resources/schools_complete%20(1).csv), 
[students_complete.csv](https://github.com/RabidZippers/School_District_Analysis/blob/main/Resources/students_complete%20(1).csv), 
[clean_students_complete.csv](https://github.com/RabidZippers/School_District_Analysis/blob/main/Resources/clean_students_complete.csv)
* **Jupyter Notebook Files:**: 
[PyCitySchools.ipynb](https://github.com/RabidZippers/School_District_Analysis/blob/main/PyCitySchools.ipynb), 
[PyCitySchools_Challenge.ipynb](https://github.com/RabidZippers/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)
