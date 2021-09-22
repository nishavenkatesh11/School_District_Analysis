# School_District_Analysis

## Project Oveview

###Background
The school board has noted evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. 

### Purpose
The purpose of this analysis is to adjust the prior analysis to remove ninth grade data from Thomas High School and to describe how these changes affected the overall analysis.

### Methodology
The math and reading scores for Thomas High School will be replaced with NaNs while keeping the rest of the data intact. Once the math and reading scores have been replaced, the school district analysis was repeated to discover changes to the overall analysis

## Results
The changes to the analysis after the grade nine data for Thomas High School was disregarded is described below.

### District Summary

The revised district summary is pictured below.
 
A marginal decrease in scores and percentages is noted, and summarized below:
* Avg Math Score went from 79.0 to 78.9
* Avg Reading Score stayed the same
* Percent Passing Math went from 75.0 to 74.8
* Percent Passing Reading went from 85.8 to 85.7
* Percent overall passing went from 65.2 to 64.9

### School Summary
The revised school summary is pictured below. This school summary removes the ninth grade student numbers for Thomas High School from the analysis to normalize the skew created by nullifying the associated grades.
 

As data for only Thomas High School was adjusted, the data for all other schools remains the same. The differences in the scores for Thomas High School are summarized below:
* Avg Math Score went from 83.42 to 83.35
* Avg Reading Score went from 83.85 to 83.90
* Percent Passing Math went from 93.27 to 93.19
* Percent Passing Reading went from 97.31 to 97.02
* Percent overall passing went from 90.95 to 90.63

There is a slight decrease in all averaged scores and percentage calculations with the exception of reading scores. Reading scores marginally increased following the adjustment.


###Thomas High School Performance
The revised top 5 performing schools are pictured below.
 
Thomas High School's performance in relation to other schools remained relatively the same following the adjustment. Where previously, Thomas High Schools percent passing reading was higher than Cabrera High School, following the adjustment it is lower in comparison.


### Ninth-Grade Scores
Replacing the ninth-grade scores affect the following:
* Math and reading scores by grade show that Thomas High School's ninth grade data was replaced with nans.
* Scores by school spending saw no change
* Scores by school size saw no change
* Scores by school type saw no change
 

##Summary
Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been removed.

* Thomas High School 9th Grade Math and Reading scores replaced with NaN.
* Thomas HIgh School 9th Grade student count removed from analysis.
* Dropping Thomas High School 9th Grade students from analysis lead to only a marginal decrease in Thomas High school average scores and percentages.
* Overall district summary did not change from misconduct mitigation measures in analysis.  