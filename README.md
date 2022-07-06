# School_District_Analysis

## Overview
The purpose of this analysis is to address the possibility of academic dishonesty in standardized testing for Py City Schools. There is suspicion that the scores have been altered for Thomas High School 9th graders so this report explores what the data would look like if all 9th grade scores from Thomas High School were nullified and the remaining scores recalculated.  Only the raw scores have been considered in this report. No other context into the situation was given.

### Thomas High School Demographics
* School Type: Charter
* Total Students: 1635 (Medium-size category)
* Spending Per Student: $638 (Upper-Mid Spending Tier)
* Rank: 2nd based on Overall Passing Score


## Results
### District Summary

There were no significant changes between the original and altered averages over all schools.  Being that Thomas High School freshmen make up 1% of the total district student population, ommitting their scores made only a minor difference.  The district average scores were each reduced by less than 1%.

![District_Summaries](https://user-images.githubusercontent.com/102555125/177637013-0b10dadc-3075-4db9-81bc-8b8258c5deba.png)


### School Summary / Effect on Math and Reading Scores
Whenever a sample size is reduced, the values in it carry more weight, so the expectation is that the overall scores will change, as we can see in the below chart.  They did not change by much within Thomas High School, though.  This indicates that the scores were not outliers in the dataset and that they were close to the averages of the other grades calculated.  Omitting the 9th grade scores reduced the school averages by less than 0.5% for math, reading, and passing averages for both.

![Thomas_stats](https://user-images.githubusercontent.com/102555125/177637142-bc52cd1e-d765-4061-9071-cf054c6396a1.png)


### Performance Compared to Other Schools
Removing the 9th grade scores may have changed Thomas High School's overall scores within their school, but it did not alter their position in a ranking of all schools from highest to lowest overall passing scores. Thomas High still ranks 2nd among all 15 schools.  Had the 9th grade scores been significantly higher than the rest of the school, the expectation would be that the recalculated scores would have dropped much more than they did and, consequently, for Thomas High School to drop in ranking.  This did not happen.

![School_Summary_Original](https://user-images.githubusercontent.com/102555125/177637219-c3dfce8b-5f97-4661-b1bb-8e30fd299ab2.png)

![School_Summary_Altered](https://user-images.githubusercontent.com/102555125/177637235-888cce0e-3014-4c12-b029-44cbcb9fe02d.png)


### Comparison Based on School Spending
Following the same pattern, altered scores for Thomas High School did not affect the overall for their upper-mid spending range category.  The scores for their tier were affected by such a small margin, I was unable to discern a difference with scores formatted to the tenths place.  Unformatted scores were used to show there is a difference in the $631-$645 range.

![Per_Student_Spending_Ranges](https://user-images.githubusercontent.com/102555125/177637268-b386d0c0-13d4-4aa4-82b6-b8283ca053da.png)


### Comparison based on Size
The same issue was present with comparing scores by size as it was when scores by spending bin were compared: there is such a minute difference in the Medium-sized school range that the pre-formatted data needed to be used to show that there is any difference.  Again, the difference is negligible in this case.

![Scores_by_size](https://user-images.githubusercontent.com/102555125/177637309-99bece6a-c8bf-4bb9-a1b1-c5802bd1cbf8.png)


### Comparison based on School Type
Finally, scores based on charter or district schools were similarly minutely affected.

![Scores_by_type](https://user-images.githubusercontent.com/102555125/177637338-a2509114-4715-4384-85d2-088f3ea79692.png)



## Summary
Thomas High School's scores did not change significantly when the reading and math scores of 461 freshman were nullified and the rest were recalculated.  That means that the 9th grade scores were not skewed enough to push the averages and that they were close to the averages of the rest of the grades.  This does not mean they were *not* tampered with, it means they were not significantly different enough to affect the scores as a whole.

As making the 9th grade scores null did not significantly affect the data, this method to determine academic honesty regarding Reading and Math test scores at Thomas High School is inconclusive.  There is not enough evidence to determine whether the scores were or were not tampered with.

### Next Steps
My suggestion for next steps would be to explore why the school board feels there has been academic dishonesty and what in particular about the the data seems suspicious.  The next logical step would be to investigate the testing procedures in place by Thomas High School to see if and where there could have been opportunity for tampering.  Based on my calculations, the answer won't be found in the scores themselves.
