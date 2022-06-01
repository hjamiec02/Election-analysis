# Election-analysis

## Project Overview
A Colorado Board of Election employee has given the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the percentage of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data source: election_results.csv
- Software: Python 3.6.1 Visual Studio Code, 1.38.1

## Summary 
The analysis of the election show that:
 - There were 369,711 votes cast in the election.
 - The candidates were:
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
  - The candidate results were:
  - Charles Casper Stockham: 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette: 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane: 3.1% of the vote and 11,606 number of votes.
  - The winner of the election was:
  - Diana DeGette, who received 73.8% of the votes and 272.892 number of votes.

## Challenge Overview
# Overview of Election Audit
After completing an audit, requested by the Colorado Board of Election to determine the winner, additional information was requested by the commission.
The additional information requested for the audits is listed as follow:
- Voter turnout for each county
- Percentage of votes from each county out of the total count
- The county with the highest turnout

# Election-Audit Result
- There were 369,711 votes cast in the election.

- County Vote Breakdown:
  Jefferson: 10.5% (38,855)
  Denver: 82.8% (306,055)
  Arapahoe: 6.7% (24,801)
  
- Denver county had the largest number of vote at 306,055 

-The candidate results were:
  - Charles Casper Stockham: 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette: 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane: 3.1% of the vote and 11,606 number of votes.

- The winner of the election was:
  - Diana DeGette, who received 73.8% of the votes and 272.892 number of votes.

Included is a screenshot detailing the results using Python and Visual Studio
<img width="367" alt="Screen Shot 2022-05-29 at 5 02 21 PM" src="https://user-images.githubusercontent.com/105119531/170891356-a01319ea-5ca9-42cc-8b09-7d26e0e4f256.png">


## Challenge Summary
This same script could be modified and used again for other elections and produce data other than the winners and county turnout. If we were provided with data such as voter's age, sex, race or precinct by zip code we could extrapolate many data points to help us better understand the election results. Such examples could include a breakdown of candidate votes per county or also how popular each candidate was based on any of the voter demographic categories.  

