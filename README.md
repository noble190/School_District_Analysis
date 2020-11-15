# School District Analysis

## Overview
<hr>

As part of Module 4, we have used Pandas DataFrames to load and analyze CSV school and student data, in order to determine relative school performance (expressed as % of students passing math and reading).
In addition to displaying data for all schools, data is further broken down by spending per student, school size, and school type.

The purpose of this exercise is to remove the fraudulent grade data for 461 Grade 9 students of Thomas High School (THS), and repeat the above analysis with updated data.

## Results
<hr>

### District Summary
District-level data was not impacted much by the removal of the fraudulent grades. Because only 461 grades were removed from the calculation out of a total of 39,170 students, district-level measures were lowered by 0.1 - 0.3 percentage points.

District Summary (before):

District Summary (after):

### School Summary
School-level data for THS was impacted noticeably by the removal of fraudulent Grade 9 grade data. After the data was removed, the recalculated summary showed a considerable increase of students passing math and reading. The overall passing rate has increased from ~65% to ~91%. It can be speculated that the school may have misrepresented data in order to attract more funding.

School Summary (before):

School Summary (after):

### Changes to Thomas High School's relative performance

After removing the fraudulent grade data, we can see that THS has entered the top 5 schools list. Before the removal, it was not found in either the top 5 or the bottom 5 schools.

### Impact of replacing Grade 9 scores

* Math and reading scores by grade
The Grade 9 value for THS is now showing 'NaN', as expected. Otherwise, data has not been impacted.

* Scores by school spending
The average grades for the THS spending bucket ($630-$644) have increased slightly after the data was updated.

* Scores by school size
The average grades for the THS size bucket (Medium) have increased slightly after the data was updated.

* Scores by school type
The average grades for the THS type bucket (Charter) have increased slightly after the data was updated.

## Summary
<hr>
The School Districut Analysis data has been visibly impacted after removing THS Grade 9 grade data. While district-level data was not severely impacted by removing data for one grade for one school, school summary data had a more visible impact. After the fraudulent grades were removed, THS began to appear in the top-5 list of schools by performance. Similar to the district-level summary, data by spending, size, and school type buckets were impacted, but not significantly.
