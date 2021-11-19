# School_District_Analysis

## Project Overview
An analysis of math and reading scores for high school students in a school district was previously completed. This analysis grouped and displayed the math and reading scores of the students by school size, budget, and type of school (District, or Charter). After the analysis was originally completed, the scores of the ninth-grade students at one of the high schools in the district (Thomas High School) were found to be illegitimate. The main goal of this project was to remove the invalid math and reading scores from the data and repeat all of the analysis. The new analysis reveals any changes in the original after the bad scores were removed. The results of this analysis will be summarized below.

## Resources
- Data Source: students_complete.csv, schools_complete.csv
- Software: Python 3.7.6, Visual Studio Code, 1.62.0

## Summarized Results
  - ### District Summary
      If we look at the District Summary before and after the removal of the ninth grade scores from Thomas Highschool, we can see that the average scores and the percentage of       students passing the subjects decreased slightly, with the exception of Avereage Reading Score which stayed the same ot the tenth of a percent. Below are images of the           District Summary before and after the recalculation.
      #### District Summary Before Recalculation
      <img src = "https://github.com/AaronAKTX/School_District_Analysis/blob/main/Resources/Old_District_Summary.PNG">

      #### District Summary After Recalculation
      <img src = "https://github.com/AaronAKTX/School_District_Analysis/blob/main/Resources/New_District_Summary_DF.PNG">
      
  - ### School Summary
      The school summary shows a small change in the numbers for Thomas High School after the ninth grade scores were removed. The results can be seen in the before and after         images below. Note that all other schools are the same in both images, and Thomas High School's data is just slightly different after the recalculation.
      #### School Summary Before Recalculation
      <img src = "https://github.com/AaronAKTX/School_District_Analysis/blob/main/Resources/Old_District_Summary.PNG">

      #### School Summary After Recalculation
      <img src = "https://github.com/AaronAKTX/School_District_Analysis/blob/main/Resources/New_District_Summary_DF.PNG">
      


The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The votes per county in the precinct were:
  - Jefferson: 38,855 votes, 10.5% of the vote count
  - Denver: 306,055 votes, 82.8% of the vote count
  - Arapahoe: 24,801 votes, 6.7% of the vote count
- Denver had the largest number of votes.

- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the votes (85,213 votes).
  - Diane DeGette received 73.8% of the votes (272,892 votes).
  - Raymon Anthony Doane received 3.1% of the votes (24,801 votes).
- The winner of the election was:
  - Diane DeGette, who received 73.8% of the votes and 272,892 total votes.

- A summary of the election results is saved to a text file when this analysis script runs. The election results are also output to the screen when the script is run. The results look like the image below.
- <img src = "https://github.com/AaronAKTX/Election_Analysis/blob/main/Resources/Elections_Results.PNG">


 
## Election Audit Summary
The analysis of the election results ran very quickly with the python script created. One of the features of the script is that it prints the results to a text file seen in the Election-Audit Results section of this file.
The script is also written in a way that it can be applied to many different elections. It is taking a three-columned csv file and essentially counting the number of rows that have a specific value in the second and third columns. In this case, the second column had the county that the vote was made in, so the script counted all the votes made in each unique county and returned the votes, percentage of votes, and county with the highest percentage of the votes. The third column held the name of the candidate that was running. The script returned the number of votes cast for each candidate, the percentage of votes cast for each candidate, and the overall winner. Had this election been about a proposition being passed or not, nothing would need to be changed except for the column that held the candidate's name would now hold a 'Yes' or 'No'. The script would run the same and the results would show whether Yes or No had more votes. Only labels would need to change.
Due to the way the Python code is written, it does not depend on a fixed number of candidates or options. It is creating a dynamic list of candidates that will grow each time a row is populated with a candidate name that hasn't been added to the list yet. This makes the analysis great for primaries with a larger group of candidates and general elections which may have smaller sets of candidates. Any number of candidates would work in this format.The same is true for the list of counties, any number of counties would correctly be calculated whether there was one county or many counties reporting. 
