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
    - The removal of the ninth grade test scores from Thomas High School resulted in a substantially lower overall percentage of passing students, due to the reduction of 461 results.
    - However, the updated average math and reading scores did not significantly change with the removal of ninth grade results, suggesting that any manipulation of ninth grade test scores did not skew results.
    
### Additional Analysis

  - Math and reading scores by grade 
    - The initial ninth grade math and reading scores at Thomas HS were 83.6 and 83.7, respectively.   
    - These were within 1% of the grades posted for tenth through twelfth graders at Thomas HS.
    - The overall average math schores for all ninth graders changed from 80.35 to 80.12 following the removal of questionable data.
    
  - Scores by school spending
    - The average math score declined by -0.077, from 83.418349 to 83.350937, which is statistically insignificant.
    - The average reading score increased by +0.047, from 83.848930 to 83.896082, which is also not a significant impact on results.
      
  - Scores by school size
    - The revised average math and reading scores did skew results by school size. Thomas HS is in the medium size grouping, and removing a large portion of test results yielded less favorable outcomes.
        
   - Before:
    ![image](https://user-images.githubusercontent.com/98435855/155899134-deea4639-f9ee-456c-8032-4806ec2a1182.png)

   - After :
    ![image](https://user-images.githubusercontent.com/98435855/155899149-16d87719-c907-4139-afa8-e05139cc97ec.png)

      
  - Scores by school type
    - Finally, there was a change in outcomes regarding school type, since Thomas HS is a charter school.  The impact is seen as a lower percentage of students passing math and reading.
      
    - Before:
    ![image](https://user-images.githubusercontent.com/98435855/155899200-eda214fe-e76b-463a-a0ac-da69975f52c4.png)

    - After :
    ![image](https://user-images.githubusercontent.com/98435855/155899213-458ccccd-8998-4e3c-84dc-e955961ada10.png)

## Summary
    - The percentage of students passing math and reading by school type (Charter, District) declined with the removal of suspect data.
    - The percentage of students passing math and reading by school size (Small, Medium, Large) declined for the Medium group.
    - The percentage of students passing math and reading by spending range per student ( <$584, $585-629, $630-644, $645-675) declined for the $630-644 group.
    - The average scores of ninth grade students declined from 80.351617 to 80.120302.
