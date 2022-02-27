# School-District-Analysis

## Project Overview
The Chief data scientist for a city school district has asked for help to aggregate standardized test data, for analysis and reporting on trends and school performance.     Data provided includes math and reading test scores, as well as student funding, and information on the schools they attend.    This analysis will assist the school board in making decisions regarding the school budgets and priorities.

Additionally, the reading and math grades for one school in the District, Thomas High School, appear to have been altered for the ninth grade class.  This analysis replaced those scores with null values, while keeping the rest of the data intact.   This report will detail how those changes have affected the overall analysis.

## Resources
Python 3.7.6, Jupyter notebook 6.4.6

##  School District Analysis Results
  - How is the district summary affected?
    - The original total count of 39,170 students was reduced by 461 students as the result of removing the ninth grade Thomas High School test scores.
    - This represents 1.1% of the total sample size, which is immaterial in total.
    - ![image](https://user-images.githubusercontent.com/98435855/155897353-22a5cf5d-1587-4cc0-a06d-bb2b67c19f48.png)


  - How is the school summary affected?
    - The original total count of 1,635 students test scores at Thomas High School was reduced by 461 test scores, or 28% of the results, which is statistically significant.
    
  - How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
    - The removal of the ninth grade test scores from Thomas High School resulted in a substantially lower  
