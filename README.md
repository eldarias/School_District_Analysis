# School District Analysis

## Project Overview
The purpose of this project was to perform a new analysis of the School District dataset and compare the overall results to observe the potential impact of removing data.  The new analysis data was kept intact except that the 9th grade reading and math scores at the Thomas High School were marked with _"NaN"_ therefore that data/scores were not taken into account on the new analysis.

## Results
Below are the results for the data comparison between the original results and the new results.

### District Summary:
There was no significant effect to the overall district summary as shown below for the original summary and the new one:

#### Original District Summary Overview:
- <image src="./analysis/images/District_Summary_Overview_original.png">

#### Reanalyzed District Summary Overview:
- <image src="./analysis/images/District_Summary_Overview_Reanalyzed.png">


### School Summary
There was no significant affect to the overall school summary as shown below, only the Thomas High School has a very minimum change, but not significant to conclude that would have had a negative effect.

#### Original School Summary Overview:
- <image src="./analysis/images/Per_School_Summary_Overview_original.png">

#### Reanalyzed School Summary Overview:
- <image src="./analysis/images/Per_School_Summary_Overview_Reanalyzed.png">


### Low and High Performing Schools Summary
Below are the results for the bottom 5 and top 5 performing schools.  It can be concluded that removing the ninth grader's math and reading scores had no effect in Thomas High School's performance relative to the other schools.  The low and high performing schools remained the same, hence this also did not affect other schools from the original results.

#### Original Bottom 5 Overview:
- <image src="./analysis/images/Bottom5_LowPerformingSchools_original.png">

#### Reanalyzed Bottom 5 Overview:
- <image src="./analysis/images/Bottom5_LowPerformingSchools_Reanalyzed.png">

#### Original Top 5 Overview:
- <image src="./analysis/images/Top5_HighPerformingSchools_original.png">

#### Reanalyzed Top 5 Overview:
- <image src="./analysis/images/Top5_HighPerformingSchools_Reanalyzed.png">


### Math and reading scores by grade
Below are the results for math and reading score by grade from the original analysis and the new analysis.  The only difference is the math and reading scores for Thomas High School, which were marked as _"nan"_ so the scores would not be taken into account when performing the new analysis.

#### Original Math and reading scores by grade Overview:
Original Math scores overview:
- <image src="./analysis/images/MathScoresbyGrade_original.png">

Original Reading scores overview:
- <image src="./analysis/images/ReadingScoresbyGrade_original.png">

#### Reanalyzed Math and reading scores by grade Overview:
Reanalyzed Math scores overview:
- <image src="./analysis/images/MathScoresbyGrade_Reanalyzed.png">

Reanalyzed Reading scores overview:
- <image src="./analysis/images/ReadingScoresbyGrade_Reanalyzed.png">


### Scores by school spending
As shown below, there was no effect to the scores by school spending:

#### Original Scores by school spending Overview:
- <image src="./analysis/images/ScoresbySchoolSpending_original.png">

#### Reanalyzed Scores by school spending Overview:
- <image src="./analysis/images/ScoresbySchoolSpending_Reanalyzed.png">


### Scores by school size
As shown below, there was no effect to the scores by school size:

#### Original Scores by school size Overview:
- <image src="./analysis/images/ScoresbySchoolSize_original.png">

#### Reanalyzed Scores by school size Overview:
- <image src="./analysis/images/ScoresbySchoolSize_Reanalyzed.png">


### Scores by school type
As shown below, there was no effect to the scores by school type:

#### Original Scores by school type Overview:
- <image src="./analysis/images/ScoresbySchoolType_original.png">

#### Reanalyzed Scores by school type Overview:
- <image src="./analysis/images/ScoresbySchoolType_Reanalyzed.png">



## Summary
In summary, although removing or adding data can be thought to skew results, in this case our analyzes confirms that there was no significant impact to Thomas High School, other schools or the district as a whole.  One possible reason for the minimum to no impact is due to the large amount of data analyzed.  We can see a very minimum change to the overall results for Thomas High School, but it is not significant to say have a concerning impact.  For example, the original **Average Math Score** was **83.418349%** and the new score is: **83.350937%**.  The original **Average Reading Score** was **83.848930%** and the new score is: **83.896082%**.  The **% Passing Math** was **93.272171%** and the new one is: **93.185690%**.  The original **% Passing Reading** was **97.308869%** and the new one is: **97.018739%**.  Finally, the **% Overall Passing** was: **90.948012%** and the new one is: **90.630324%**.


