# Election_Analysis

## Project Overview
A Colorado Board of Elections empolyee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.52.1

## Election-Audit Results
The analysis of the election shows that:
- There were ***369,711*** votes cast in the election.

- The county results were:
  - Jefferson county: **38,855** voters for ***10.5%*** of the total votes cast.
  - Denver county: **306,055** voters for ***82.8%*** of the total votes cast.
  - Arapahoe county: **24,801** voters for ***6.7%*** of the total votes cast.

    > The county with the largest number of votes was: ***Denver***
  
- The candidates were:
  - **Charles Casper Stockham**
  - **Diana DeGette**
  - **Raymon Anthony Doane**

- The candidate results were:

  | Candidate | # of Votes | % of Votes |
  | :---| :---: | :---: |
  | Charles Stockham | 85,213 | 23.0% |
  | Diana DeGette | 272,892 | 73.8% |
  | Raymon Doane | 11,606 | 3.1% |

> The winner of the election was:
>   - **Diane DeGette**, who received ***73.8%*** of the vote and **272,892** votes.
  
## Election-Audit Summary

> With a few minor changes to the code script for this election audit, it could be used for audits at any level: local, state and national.
> - At a national level we could make an adjustment and audit results only by county, but also be state by adding a couple of lines in the tally 'for' loop to tabulate state results.
> - The script could also be modified for use in primary elections between candidates in two or more political parties by duplicating the 'for' loops to find the winner for each political party and returning those results.
