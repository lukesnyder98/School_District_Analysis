# School District Analysis
 
## Overview
The purpose of this analysis is to determine the average math and reading scores, percentages of students passing math and reading individually, and the percentages of students passing both classes for all of the high schools in the district. We also look at how these scores and percentages are affected by school spending, school size, and whether the school is a charter or district school.

Thomas High School's ninth graders appeared to have altered math and reading scores, and so they were replaced with NaN's in the student data. The results and summary below explain how this affected the district and school summaries.

## Results

* In the district summary, there were slight decreases in the average math and reading scores,  percentages of students passing math and reading, and the overall passing percentage.
* In the school summary, Thomas High School's average math score, passing math percentage, passing reading percentage, and overall passing percentage decreased, while the average reading score increased by about 0.05.
* Thomas High School's performance relative to the other schools did not change. It still has the second highest overall passing percentage.
* Thomas High School's ninth grade math and reading scores display as "NaN" in the grade analysis DataFrames, but the rest of the data was not affected.
* The spending summary was not affected.
* The size summary was not affected.
* The type summary was not affected.

## Summary
After replacing Thomas High School's ninth grade reading and math data with NaN's, the average math score across the district decreased by 0.1, the percentage of students passing math decreased by 0.2, the percentage of students passing reading decreased by 0.1, and the percentage of students passing both math and reading decreased by 0.3.