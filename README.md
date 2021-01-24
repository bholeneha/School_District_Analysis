# School_District_Analysis

## Overview 
This analysis project is to prepare standardizing test data for analysis and gain insights about school performance trends to help the school board make strategic decisions regarding school budgets and priorities. The school board has notified the analyst regarding evidence of academic dishonesty within the data set in regards to altered reading and math scores for Thomas High School ninth graders.

### Purpose 
The purpose of this analysis is to replace the math and reading scores for Thomas High School (THS) with NaNs while keeping the rest of the data intact, determine how these changes have affected the analysis and report the following:

    * District School Summary (describing total students, total budget, average scores)
    * School Summary (describing the above for each school)
    * Scores by Grade
    * Scores by School Budget
    * Scores by School Size
    * Scores by School Type


## Analysis 

Data Source: [Schools Data Set](Resources/school_data.csv),
            [Students Data Set](Resources/student_data.csv)

Software used: Python 3.7.6, Jupyter Notebooks

Analysis Code: [PyCitySchools_Challenge](PyCitySchools_Challenge.ipynb)

## Results

Following are the results on how each of the seven school district metrics was affected by the changes in the data.


### District Summary

|           |          |
|-----------|----------|        
|District summary with the original data set   |![Original School District Summary](Images/School_District_Summary_Original.PNG)|
|District summary after replacing THS grade 9 scores with NaN|![New School District Summary](Images/School_District_Summary_Challenge.PNG)|

As shown in the table above, there is a very slight difference in the values for average scores, percentages and overall passing percentage. Therefore, the school district summary wasn't significantly affected by the changes made to the data. 

### School Summary

The summaries for schools in this DataFrame were unaffected except for Thomas High School.  

|    |    |
|----|----|
|THS school summary with original data set|![Original School Summary](Images/School_Summary_Original.PNG)|
|After replacing THS 9th Grade Scores with NaN|![New School Summary](Images/School_Summary_Challenge.PNG)|
|After removing THS 9th grade scores from the analysis|![After removing Grade 9 from Total Student](Images/School_Summary_ChallengeAfter.PNG)|

In the above comparison, it is evident that the changes in the data wouldve affected the performance summary for THS. THS's overall passing percentage was at 90.9 % before replacing the 9th grade values and dropped to 65% after. However, summary for THS was recalculated by disregarding the grade 9 scores entirely, which brought THS's overall passing percentage back up to 90.6 %.

[//]: # "How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?"

###### The following analysis was conducted by omitting the Thomas High School's grade 9 scores from the analysis. 
 
### Math and Reading Scores by Grade
| Math Scores | Reading Scores|
|-------------|---------------|
|![Math Scores by Grade after replacing 9th Grade Scores](Images/Math_Scores_by_Grade_New.png) | ![Reading Scores by Grade after replacing 9th Grade Scores](Images/Reading_Scores_by_Grade_New.png)| 

The results for math and reading scores by grade for each school remained unchanged except the scores for grade 9 for THS were replaced with NaN.
    
### Scores by School Spending
![Scores by School Spending](Images/Scores_by_School_Spending.png)

The results (above image) for scores by school spending were unaffected by the changes in the data. 

### Scores by School Size

![Scores by School Size](Images/School_Type_Challenge.PNG)

The results (above image) for scores by school size were unaffected by the changes in the data.

### Scores by School Type

![New School Type Summary](Images/School_Type_Challenge.PNG)

The result for scores by school type was unaffected by the changes in the data.


## Summary

[//]: # "Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
There is a statement summarizing four major changes to the school district analysis after reading and math scores have been replaced"

### 





### 