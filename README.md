# Colorado Elections Audit

## Overview of Election Audit
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local
congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of counties particpating in the election.
3. Calculate the total number of votes cast in each county.
4. Caluclate the percentage of votes cast in each county.
5. Determine the county with the largest turnout.
6. Get a complete list of candidates who received votes.
7. Calculate the total number of votes each candidate received.
8. Calculate the percentage of votes each candidate won.
9. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election Audit Summary
The analysis of the election show that:
There were 369,711 votes cast in the election.

The counties polled were:
- Jefferson
- Denver
- Arapahoe

The county turnout results were:
- Jefferson has 10.5% of the total vote share with a total of 38,855 ballots cast.
- Denver has 82.8% of the total vote share with a total of 306,055 ballots cast.
- Arapahoe has 6.7% of the total vote share with a total of 24,801.

The county with the largest number of ballots cast is Denver, with 82.8% of the total vote and 306,055 ballots cast.

The candidates were:
- Charles Casper Stockham
- Diana DeGette
- Raymon Anthony Doane

The candidate results were:
- Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
- Diana DeGette received 73.8% of the vote and 272,892 votes.
- Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.

The winner of the election was:
Diana DeGette, who received 73.8% of the vote and 272,892 votes.

## Election Audit Summary

In summation, a total of 369,711 ballots were cast in three counties; Jefferson, Denver, and Arapahoe.  Denver ballots make up the majority of votes cast with 306,055 ballots, amountng to 82.8% of the total vote.  Ballots were cast for three candidates; Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane.  Of the three candidates, Diana DeGette won the popular vote with 73.8% of the vote and 272,892 votes.   

Given the programatic structure of the code file, it may be used in future election audits given the proper modifications.  As it is written with reference to files using file paths, analysis of future election data would need to be updated to reflect current working directories and associated file lcoations.  Furthermore, care would have to be paid to checking the columns associated with certian data, such as candidate name and county, in raw data files.  With these simple adjustments, this code can be repurposed for election audits for years to come. 

