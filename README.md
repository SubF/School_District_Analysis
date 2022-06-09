# School_District_Analysis

## Overview of the School District Analysis

Maria has requested for a new analysis be completed after evidence of academic dishonesty was found in the reading and math scores for Thomas High School. In this new analysis the Thomas High School 9th grade math and reading scores will be removed and the school district analysis will be run with the new dataset. The two school district analysis results will then be compared to find any changes. 


## Results

Using bulleted lists and images of DataFrames as support, address the following questions.
The following results compare the new data with Thomas High School 9th graders removed which will be refered to as the "new dataset" and the "original data" which included Thomas High School 9th graders.

When comparing the district summaries between the new dataset and original dataset there was a drop of less than 1% for every metric. The Average Math Score dropped the most with just over a 0.54% drop and the Average Reading Score dropped just over 0.02%. This caused a drop in the % Overall Passing by just over 0.31%.

When comparing the school summaries between the new dataset and original dataset there was a drop in the average math scores by 0.08 but there was an increase in the average reading scores by 0.09. The main difference was in the % of passing students. The %'s increased by the following:
- % Passing Math increased by 27%
- % Passing Reading increased by 27%
- % Overall Passing increased by 26%

By replacing Thomas High School's 9th grade math and reading scores it greatly increased the passing % for math, reading, and overall. This increased the schools overall standing significantly. 

Replacing the Thomas High School 9th grader's scores results in the following changes:
- The average 9th grade math score drops by 0.08 and the average 9th grade reading score drops by 0.24
- The average scores by school spending in the $631-645 range which Thomas High School is in also drops when the Thomas High School 9th grader's scores are removed.
- The average scores by school size drop slightly for math but increase slightly for reading when the Thomas High School 9th grader's scores are removed
- The average scores by school type also drop slightly for math but increase slightly for reading when the Thomas High School 9th grader's scores are removed


## Summary: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
When analyzing the results of the data differences between the new data and original data the following results can be seen.
- When comparing by district the changes in average math scores, average reading scores, and passing % are negligible at less than 1% change for all metrics.
- When comparing by school we see the largest change which resulted in a 26% increase in the overall passing % of Thomas High School. Although the passing % changed significantly, the average math and reading scores had negligible change.
- The average scores in Thomas High Schools per student spending range ($631-645) dropped when Thomas High School 9th graders were removed. These results were also a negligible change.
- The average scores by school size and school type both saw the same results with math slightly increasing and reading slightly decreasing when Thomas High School's 9th graders were removed. These results were also a negligible change.
