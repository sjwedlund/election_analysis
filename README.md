# Election Analysis

## Project Overview
A Colorado Board of Elections has given me the following tasks to complete the election audit of a recent local congressional election:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1 Visual Studio Code, 1.38.1

## Summary
<img width="343" alt="election_results" src="https://user-images.githubusercontent.com/85920136/148452931-6aee4372-8637-4f97-92d5-27ac0c86c3d8.png">


The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
    - Diana DeGette received 73.8% of the vote and 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 votes.

## Challenge Overview
I am assisting Tom, a Colorado Board of Elections employee, in this audit of the tabulated results for a US Congressional precinct in Colorado. My task is to report the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on the popular vote. I am automating the process using Python. If this audit is done successfully using Python, the code Tom and I write will be used to audit other congressional districts and senatorial districts and local elections. We will take into account three voting methods: Mail-in Ballot, Punch Cards, and Direct Recording Electronic. The votes cast by these three methods combined will determine the final election results. After the votes are counted, my assignment is to generate a vote count report to certify this US Congressional Race. 
## Challenge Summary
After downloading the complete list of candidates who received votes in a .csv file, using Python to automate the process, I have calculated the total number of votes each candidate received , and the percentage of votes each candidate won. Then I determined the winner of the election based on popular vote: Diana DeGette. 

## Election Audit Summary
I have kept this script generic so that it can be used for any election in any region. All you need is a CSV file with the county and candidate names for the area. For example, this script could perhaps be used for a local mayor or governor race. In order to repurpose the script, you only need to change the variable names to match the type of region where the votes are being tabulated from. 
