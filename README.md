# Election_Analysis

## Project Overview
A Colorado Board of Election employee has given me the following tasks to complete the election audit of a recent local congressioal election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Challenge Overview
A Colorado Board of Election employee has requested additional information to complete the analysis.

1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana Degette
  - Raymon Anthony Doane
 - The candidate results were:
   - Charles Casper Stockham received 23.0% of the vote with 85,213 number of votes.
   - Diana DeGette received 73.8% of the vote with 272,892 number of votes.
   - Raymon Anthony Doane received 3.1% of the vote with 11,606 number of votes.
 - The Winner of the election was:
   - Diana Degett who received 73.8% of the votes and 272,892 number of votes.
  
  ## Challenge Summary
  The additional analysis of the election shows that:
  - There were 369,711 votes cast in the election.
  - The counties the votes were cast from were:
    - Jefferson
    - Denver
    - Arapahoe
   - The county results were:
     - Jefferson County cast 10.5% of the vote with 38,855 votes.
     - Denver County cast 82.8% of the vote with 306,055 votes.
     - Arapahoe County cast 6.7% of the vote with 24,801 votes.
   - County in which most votes were cast:
     - Denver County voters cast the most votes at 82.8% of the vote with 306,055 votes.

# Election-Audit Summary
  This audit was created at the request of the Colorado Board of Elections Comittee. The comittee found it very useful to summarize the election with a simple program. This program has been built in a way that is easily modifiable for any election in the future as well. 
  
  This data was taken from a CSV file from Excel. Any election which compiles the data onto this file type can be used with only slight modifications as long as there is a column containing Counts(Ballot IDs), Counties, or Candidates. It doesn't matter which column in the file they are located because this program can be set to grab the data from any column. In order to change the column locations, the program only needs to be modifed in 2 lines.
  It also will not matter what the specific candidate's names or county names are. This program will work with any number of candidates and names without needing to change the code. This makes the program very useful for upcomming elections in other counties and even for other events. 
  
  This program can also be uaed for school elections. Instead of counties, you can use classes and only need to modify the names in the output (text and terminal). This makes this program easy to use and extremely versatile, being useful for anything from small calss elections to county elections and everything in-between! The best part of this program is it is very affordable as well. 
  
  
  
  
