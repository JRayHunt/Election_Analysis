# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given us the following tasks to complete the election audit of a recent local congressional election. If successful, the script could be used for other elections as well.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.0, Visual Studio Code, 1.50.1

## Election Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
    - Charles Casper Stockham
    - Dian DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23% of the vote and 85,213 number of votes
    - Dian DeGette received 73.8% of the vote and 272,892 number of votes
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Summary    
The election committee should use this script for other elections because it is data driven and none of the counties or candidates are hard-coded in the data. We could make changes to add more fault tolerance such as checking values for 0 before division for the percentages. Furthermore, we could change the code to read from multiple csv files by creating an input box for users to type in the name of the csv file.

## Challenge Overview
The challenge built on work in the module by adding vote counts per county and identifying the county with the largest voter turnout. The county with the largest voter turnout was Denver.
## Challenge Summary
This challenge was tougher than the previous ones. I struggled some with debugging the for loops for lists and dictionaries. It was easy to get lost in the code and lose my place. I attended two office hours both Friday and Saturday. The TAs were very helpful.    
