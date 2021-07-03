# Election_Analysis

## Project Overview
This project was commissioned by the Colorado Board of Elections to complete the election audit of a recent local congressional race.  The votes were collected through three methods:  Mail-In Ballots (hand counted), Punch Cards (machine counted), and Direct Recording Electronic (computer counted).  The deliverables to be reported in the Vote Count Report, in order to certify the congressional race, were:

1. Calculate the  total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.5, Visual Studio Code 1.57.1

## Summary
The results of the Vote Count Report were:

![election_results](https://user-images.githubusercontent.com/85590155/124362334-76b35e80-dbf1-11eb-8831-bca34d570c7e.PNG)

- There were 369,711 votes cast in the election.
- The counties in which votes were cast:
    - Arapahoe
    - Denver
    - Jefferson
- The county results were:
    - Arapahoe votes cast were 24,801 which was 6.7% of total votes.
    - Denver votes cast were 306,055 which was 82.8% of total votes.
    - Jefferson votes cast were 38,855 which was 10.5% of total votes.
- The largest county turnout was Denver.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
    - Candidate Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Challenge Summary
The Vote Count Report is usually tabulated using excel.  But in this instance Python was used in order to automate the process.  This will allow the audit to be used in future congressional districts, senatorial districts, and local elections.  Part of the flexibility is that the Python code does not need to know the candidate or county name.  Rather it can read it from the csv file.  Snippet of code below:

![audit_code_example](https://user-images.githubusercontent.com/85590155/124362681-b713dc00-dbf3-11eb-87d6-47b65d0e0c4e.PNG)

Going forward, this Python code can be used to audit future elections with a couple of modifications:
- Building on the existing decision statements and logical operators within the code, breakdown candidate's results by county and/or region.  This would allow for greater insight into the results, inform on future trends, and troubleshoot if necessary.
- Utilize additional decision statements, comparison operators, and f strings in order to rank the candidates in the report by percentage of votes.  This will give better transparency into the complete results of the election.  This could be especially helpful with a large pool of candidates.
