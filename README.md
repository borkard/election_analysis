# Election-Audit Analysis

## Overview of Election Audit
### Purpose
The purpose of this election analysis was to determine the winner of the election after a thorough analysis of the votes and percentage of votes cast for each candidate in the election, as well as a breakdown by county and to determine the county with the largest turnout. The election-audit analysis was conducted through a Python script that ran through the election_results.csv file with all the data from the election and counted the votes per candidate and by county to determine the winner and largest county turnout, as well as information on the number and percentage of votes for each candidate and county.

## Election-Audit Results

* There were **369,711** votes cast in this election.
* A breakdown of the number of votes and the percentage of total votes for each county in the precinct is below: <br />
![county_votes](https://github.com/borkard/election_analysis/blob/main/county_votes.PNG)

* **Denver** is the county with the largest number of votes.
* A breakdown of the number of votes and the percentage of the total votes each candidate received is below: <br />
![candidate_results](https://github.com/borkard/election_analysis/blob/main/candidate_results.PNG)

* The winning candidate results are below:<br />
  **Winner:** Diana DeGette<br />
  **Winning Vote Count:** 272,892<br />
  **Winning Percentage:** 73.8%

## Election-Audit Summary
This python script can be used, with some modifications, for any election. The script is made to run through any number of votes, counties, and candidates and count the number and percentage of votes received by candidate and county and determine the winner of the election and the county with the largest turnout. This script could be modified for other elections to include a breakdown of candidate votes (and percentage of votes) within each county to drive the analysis a little deeper. This could be done by using an if statement within a for loop to count the votes for each candidate name within the county name. Another way to modify the script for another election could be to add more information about the county with the largest turnout by including the vote count and percentage in the print function, similar to printing the winning candidate summary.
