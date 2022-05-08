# School_District_Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

### How is the district summary affected?
- Slight change in Math Score, including % Passing district averages, Comparing the two dataframes above, the average show the difference when the 9th grade student Math and Reading scores from Thomas High Schools were excluded from the District Summary.

Before Clean Up

![Before_CleanUp](https://github.com/vvinci21/School_District_Analysis/blob/43f0b3af1c34242892284612ed9086fa85534b45/Resources/ds_beforeclean%202.png)


After Clean Up

![After_CleanUp](https://github.com/vvinci21/School_District_Analysis/blob/35612904d0fc32eab2dceaf7197ed0ec7a2c4374/Resources/ds_aftercleanup%202.png)

- How is the school summary affected?

There was little to no change on the `school_summary_df`. All metrics for Thomas High School varried by less than 0.5%.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the ninth graders' mat and reading score did not affect Thomas High Schools performance relative to the other schools. It remained ranked in second place.

Before Clean Up



After Clean Up


### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
> The only change here was representing the data as "NaN" using `np.nan` 

- Scores by school spending
- Scores by school size
- Scores by school type
> For scores by spending, size, and type there was no material affect. 

## Summary
- Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
> The four major changes in the school district analysis are four decreases in the District Summary and Thomas High School's Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing. Larger changes were not seen in the school district analysis because the only Thomas High School's 9th-grade’s "nan" scores were dropped from the analysis and the analysis still included Thomas High School's math and reading scores from the 10th grades - 12th-grades.
