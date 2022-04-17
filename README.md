# Election_Analysis

# Election Audit with Python
Click here to view the Python file: [Election Analysis](https://github.com/dgeroux/election_analysis/blob/main/PyPoll_Challenge.py)

## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate received.
5. Calculate the voter turnout for each county
6. Calculate the percentage of votes from each county out of the total count
7. Determine the county with the highest turnout
8. Determine the winner of the election based on popular vote. 

## Resources
- Data Source: [election_results.csv](https://raw.githubusercontent.com/dgeroux/Election_Analysis/main/Resources/election_results.csv)
- Software: Python 3.10.4 and Visual Studio Code 1.66.1

## Election Audit Results
- **How many votes were cast in this congressional election?**<br/>
The total amount of votes that were cast in the congressional election was 369,711.
- **Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**<br/>
Jefferson County: 10.5% (38,855)<br/>
Denver County: 82.8% (306,055)<br/>
Arapahoe: 6.7% (24,801)
- **Which county had the largest number of votes?**<br/>
Denver County had the largest number of votes.
- **Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**<br/>
Charles Casper Stockham: 23.0% (85,213)<br/>
Diana DeGette: 73.8% (272,892)<br/>
Raymon Anthony Doane: 3.1% (11,606)
- **Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**<br/>
The winner of the election was Diana DeGette with 272,892 votes (73.8% of the total votes).

Below is an image of the summarized election results:

![Election Results](https://github.com/dgeroux/Election_Analysis/blob/main/Analysis/Election_Analysis_Deliverable_2.png)

## Election Audit Summary
The script that was created for this project can be used for **ANY** election audit, given that the election data provided is organized on a .csv file in a similar fashion (Ballot ID, County, Candidate). Even if the election data provided is organized in a different way, slight modifications can be made to accommadate these differences. This is huge!<br/>

Furthermore, if the election data included other characteristics (such as demographics), the script can be modiifed to include these characteristics and provide an even more detailed analysis.
