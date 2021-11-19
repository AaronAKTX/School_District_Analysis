# School_District_Analysis

## Project Overview
An analysis of math and reading scores for high school students in a school district was previously completed. This analysis grouped and displayed the math and reading scores of the students by school size, budget, and type of school (District, or Charter). After the analysis was originally completed, the scores of the ninth-grade students at one of the high schools in the district (Thomas High School) were found to be illegitimate. The main goal of this project was to remove the invalid math and reading scores from the data and repeat all of the analysis. The new analysis reveals any changes in the original after the bad scores were removed. The results of this analysis will be summarized below.

## Resources
- Data Source: students_complete.csv, schools_complete.csv
- Software: Python 3.7.6, Visual Studio Code, 1.62.0

## Summarized Results
  - ### District Summary
      If we look at the District Summary before and after the removal of the ninth-grade scores from Thomas Highschool, we can see that the average scores and the percentage of students passing the subjects decreased slightly, with the exception of Average Reading Score which stayed the same to the tenth of a percent. Below are images of the           District Summary before and after the recalculation.
      #### District Summary Before Recalculation
      <img src = "https://github.com/AaronAKTX/School_District_Analysis/blob/main/Resources/Old_District_Summary.PNG">

      #### District Summary After Recalculation
      <img src = "https://github.com/AaronAKTX/School_District_Analysis/blob/main/Resources/New_District_Summary_DF.PNG">
     
  - ### School Summary
      The school summary shows a small change in the numbers for Thomas High School after the ninth-grade scores were removed. The results can be seen in the before and after images below. Note that all other schools are the same in both images, and Thomas High School's data is just slightly different after the recalculation.
      #### School Summary Before Recalculation
      <img src = "https://github.com/AaronAKTX/School_District_Analysis/blob/main/Resources/Origina_Per_School.PNG">

      #### School Summary After Recalculation
      <img src = "https://github.com/AaronAKTX/School_District_Analysis/blob/main/Resources/New_Per_School_With_Recalculation.PNG">
     
  - ### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
      Replacing the ninth-grade scores did not affect Thomas High School's performance relative to other schools to any notable degree. Of course, calculating the average scores for math and reading without adjusting the total students in the calculation had a big effect. It brought Thomas down relative to other schools. But, once the total number of students was updated to not include the invalid scoring students, the numbers righted themselves and Thomas' standing among other schools remained the same.

  - ### How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
      Replacing the ninth-grade scores only affected how Thomas compared with other schools' ninth-grade scores. These scores no longer exist for Thomas so they could not be compared with other school scores. The scores for all other schools and the scores for Thomas High School 10th, 11th, and 12th grade did not change. Ninth-grade scores for other schools that were originally below Thomas, would have moved up one ranking position.
   
    - Scores by school spending
      The scores by school spending will still reflect the same slight drop in scores for Thomas High School but their position among schools that spend $630-$644 per student remains the same as before. The amount spent per student doesn't change by removing the ninth-grade scores as the size and the budget did not change.
     
    - Scores by school size
      The scores by school size will still reflect the same slight drop in scores for Thomas High School but their position among schools that are medium-sized remained the same. The size of the school doesn't change by removing the ninth-grade scores.
     
    - Scores by school type
      Thomas High School is a charter school. The average scores of charter schools may have dropped by the smallest of margins but the scores of charter schools still far outperform the district schools.

 
## District Analysis Summary
After removing the ninth-grade students from Thomas High School, the analysis showed some changes. First, the total number of students being used to calculate the average scores was decreased. It seems the invalid scores were generally passing scores as the average math scores and the percentage of students passing math and reading all decreased after the data was recalculated. The overall percentage of students passing both math and reading also dropped. Thomas High School's summary showed a drop in average reading, and math scores as well as a drop in the percentage of students passing reading, math, and both reading and math.
