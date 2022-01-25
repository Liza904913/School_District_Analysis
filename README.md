# School_District_Analysis

## Overview of the school district analysis: 

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We have to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and analize the changes.

## Resources
Data Source: schools_complete.csv, students_complete.csv
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3


## Results: 

How is the district summary affected?

The average math score dropped by < 1%
The average reading score was not affected
The percentage passing math dropped by 1%
The percentage passing reading dropped by 1%
The overall passing rate dropped by 1%


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Math and reading scores for ninth graders at Thomas High School were replaced with 'NaN' (Not a Number) so that their scores would not affect future calculations.
Percentage passing math dropped from 93.2% to 66.9%
Percentage passing reading dropped from 97.3% to 69.7%
Overall passing percentage dropped from 90.9% to 65.1%
Thomas High School dropped out of the Top 5 
Scores by school spending - hanged at the $630-644 range: - percentage passing math dropped from 73% to 67% - percentage passing reading dropped from 84% to 77% - overall passing percentage dropped from 63% to 56%
Scores by school size - ercentage passing math dropped from 94% to 88% - percentage passing reading dropped from 97% to 91% - overall passing percentage dropped from 91% to 85%
Scores by school type - percentage passing math dropped from 94% to 90% - percentage passing reading dropped from 97% to 93% - overall passing percentage dropped from 90% to 87%


