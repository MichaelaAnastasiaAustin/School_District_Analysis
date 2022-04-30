# School_District_Analysis
## Overview and Purpose of School District Analysis
The purpose of this analysis was to help chief data scientist, Maria, analyze data on student funding and students’ standardized test scores, and showcase trends in school performance. After completing the analysis, the school board notified us that there had been evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. In response, we replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact, and repeated the school district analysis. This README details how this change affected the overall analysis.

## Resources
Data Source: schools_complete.csv, students_complete.csv

Software: Python 3.7, Anaconda, Jupyter Notebook

## Results 

Note: The first analysis “PyCitySchools” included the entire set of student data. In the second analysis, “PyCitySchools_Challenge”, Thomas High School’s ninth grade students’ scores were removed from the data, and replaced with NaN. This README refers to the PyCitySchools analysis as "Original" and second analysis as "Updated".

### District Summary Results
By removing the ninth grade students’ scores, scores in each category of the district summary lowered, as shown in the screenshots below.

Original District Summary:

![original district summary](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/Original_District_Summary_2f.png)

Updated District Summary:

![refactored district summary](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/District_Summary_2f.png)

### School Summary Results

When Thomas High School ninth grade student scores are removed from the school summary, the scores across each category execept "Average Reading Score" decreased, as shown in the screenshots below:

![school_summary_headers](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/School_Summary_Headers.png)

Original School Summary:

![original_school_summary](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/Original_School_Summary-formatted.png)

Updated School Summary:
![v3](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/School_Summary_v3.png)

### School Performance
Thomas High School's ranking does not change. After removing 9th graders' scores, Thomas High School remains the second best performing school in the district with an overall passing rate of 90.63%.

### Math and Reading Scores by Grade

The only impact on the math and reading scores by grade, is the substitution of 9th grade Thomas High School reading and math scores for NaN, as shown in the screenshots below.

Original Math Scores by Grade
![original_math](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/Math_Scores_Original.png)
Updated Math Scores by Grade
![refactored_math](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/Math_Scores_Challenge.png)

Original Reading Scores by Grade
![original_reading](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/Reading%20Scores_Original.png)
Updated Reading Scores by Grade
![refactored_reading](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/Reading_Scores_Challenge.png)

### Scores by School Spending
There was a slight change in the scores by school spending groups for the category that Thomas High School is in, $631-645. All categories except "Average Reading Score" decreased slightly, while "Average Reading Score" increased slightly. These changes are very small, and do not appear in the rounded, formatted versions of the code (see screenshots below).

Original 
![original_spending](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/spending_original_unformatted.png)
Updated
![refactored_spending](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/spending_challenge_unformatted.png)

Original (formatted)
![original_spending formatted](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/spending_original_formatted.png)
Updated (formatted)
![refactored_spending_formatted](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/spending_challenge_formatted.png)

### Scores by School Size
There was a slight change in the Medium size school data, as this is the catgory Thomas High School is in. All categories except "Average Reading Score" decreased slightly, while "Average Reading Score" increased slightly. Similarly to above, the changes are so small that when rounded in the formatted datasets, the changes are not apparant.

Original
![original_size_unformatted](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/original_size_unformatted.png)

Updated
![challenge_size_unformatted](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/challenge_size_unformatted.png)

Original(formatted)
![original_size_formatted](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/original_size_formatted.png)

Updated (formatted)
![challenge_size_formatted](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/challenge_size_formatted.png)

### Scores by School Type

Finally, for the scores by school type, there was a small change in the Charter school scores, as this was the category Thomas High School is part of. All categories except "Average Reading Score" decreased slightly, while "Average Reading Score" increased slightly. Once again, the changes are so small that when rounded in the formatted datasets, the changes are not apparant.

Original
![original_type_unformatted](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/original_unformatted_type.png)
Updated
![challenge_type_unformatted](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/challenge_unformatted_type.png)

Original (formatted)
![original_type_formatted](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/original_formatted_type.png)

Updated (formatted)
![challenge_type_formatted](https://github.com/MichaelaAnastasiaAustin/School_District_Analysis/blob/main/challenge_formatted_type.png)

## Summary

All in all, replacing the ninth grade at Thomas High School with NaNs showed a trend across School Summary, Scores by School Spending, School Type, and School Size-- "Average Math Score", "% Passing Math", "% Passing Reading", and % Overall Passing" all decreased slightly, while "Average Reading Score" increased slightly. However, these changes were so small, that they did not appear in any of our formatted, rounded data tables. This insignificant impact is largely due to the small number of 9th graders in Thomas High School -- 461 students out of the 39,170 students total in the analysis. The insignificant impact of replacing Thomas High School 9th graders scores with NaN is most easily summarized by the School Performance Ranking. Thomas High School remains the second best performing school in the district with an overall passing rate of 90.63%.


