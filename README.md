# School District Analysis

## Overview and Purpose

This analysis was performed on data from both District and Charter schools in a certain region
in order to get an idea of the percentage of students who are passing reading and math. With
this information the district will make decisions based on how to best allocate funds after
reviewing how each type of school performed. The analysis was performed twice because it was 
brought to our attention that the data for 9th graders at Thomas High School may have been altered. 
I replaced these grades with null values for these students and performed the same analysis again 
to compare the differences. 

## Results

### The District Summary

See a screenshot of the DataFrame for the original district summary:
![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/original_district_summary.png)


Here is the screenshot for the new district summary (without Thomas High 9th grade scores):
![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/new_district_summary.png)
 

It looks like the average reading score on both summaries is the same. The math scores are slightly lower.
Because of this, and because the overall student count changed due to the deleted scores, the percents for
passing scores in math and reading went down slightly (reading was affected more than math).
This also cause the overall passing percentage to go down. 

These changes were all within a few percent points of each other, so overall there wasn't much of a change. 

### School Summary

See a screenshot of the original school summary:
![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/original_school_summary.png)


Here is the screenshot for the new school summary:
![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/new_school_summary.png)


Keep in mind that the only difference in these outputs is in the Thomas High School row.
We can see the biggest impact here! The passing percents went from around 90% to around 65%
in each category. We can see that the altered scores were really altering our view of the 
Thomas High School data.

### Overall Look at Changes

As mentioned above, the change mostly affected the percentage of passing scores for the school, and
pretty dramatically at that! Since this study was performed to get a better insight on how the district
should be allocating their funds, this could be very valuable information to our study.

### Math and Reading Scores by Grade

See are screenshots of the original scores by grade level:

#### Original Math by Grade

![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/original_math_by_grade.png)

#### Original Reading by Grade

![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/original_reading_by_grade.png)

Here are the screenshots for the new scores by grade level:

#### New Math by Grade

![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/new_math_by_grade.png)

#### New Reading by Grade

![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/new_reading_by_grade.png)

These outputs should be the same, except the second one has the nan value for the 9th grade scores
as Thomas High School. This can be really helpful data for both educators and district personell to 
get a glimpse into how each grade level is doing at each school.

### Scores by School Spending Categories

See the screenshot of the original scores by spending categories:

![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/original_socres_by_spending.png)

Here is the new one:
![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/new_scores_by_spending.png)


As we begin to finish out the analysis with an adjusted student count and ignoring the null scores, the 
data seems to be relatively similar. 


### Scores by School Size

Original scores based on size:

![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/original_scores_by_size.png)

New scores based on size:

![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/new_scores_by_size.png)

There was also very little impact on the scores based on school size. 

### Scores by School Type

Original scores based on type of school:

![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/original_scores_by_type.png)

New scores based on type:

![screenshot](https://github.com/KW0114/school-district-analysis/blob/7b8d8945582fa1df4016b0b4c6951079492aa638/Resources/new_scores_by_type.png)

Very little impact on the scores based on type of school.

## Summary

Here are four changes that happened based on erasing the 9th grade scores for Thomas High School:

1. At the district level, it seems that the math scores were affected the most. Reading scores
mostly stayed the same.

2. The biggest difference was seen at the school level (which makes sense). The overall passing
scores for each subject dropped from about 90% down to 65%. This is a huge change that would most
likely affect their school ranking.

3. While the top schools came out to be the same after redoing all the stats with an adjusted amount
not accounting for the 9th graders. If you use the school summary from above, Thomas High School went 
from the 2nd school to the 8th spot. This could mean big changes for spending for that school!

4. The last main difference that can be observed is just with the math and reading scores per grade level.
This shows we really did replace all the 9th grade values for THS with NaN!
