# election_analysis

## Project Overview:

A Colorado Board of Elections employee has tasked us with performing an election audit of a recent local congressional election. Working with a raw data CSV file provided, they would like the following information generated via a repeatable Python script:

* Total number of votes cast
* A complete list of all counties where votes were cast
* The voter turnout in each county where votes were cast
* The percentage of the total votes each county represents
* The county with the highest voter turnout
* A complete list of candidates who received votes
* Total number of votes each candidate received
* Percentage of votes each candidate won
* The winner of the election based on popular vote

## Resources:

Data Source: election_results.csv (as provided by the CBE)
Software: Python 3.7.6, Visual Studio Code 1.50.1

## Summary Results:

* The total votes cast in this election were 369,711
* Three counties registered cast votes (Jefferson, Denver, and Arapahoe)
* The breakdown of votes by county, both in percentage and absolute, are:
    1. Denver: 82.8% (306,055)
    2. Jefferson: 10.5% (38,855)
    3. Arapahoe: 6.7% (24,801)
* The county with the largest turnout was Denver
* Three candidates received votes (Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane)
* The breakdown of votes by candidate, both in percentage and absolute, are:
    1. Diana DeGette: 73.8% (272,892)
    2. Charles Casper Stockham: 23.0% (85,213)
    3. Raymon Anthony Doane: 3.1% (11,606)

* The winner of the election was **Diana DeGette**, with **272,892 votes**, representing **73.8%** of the total votes cast.

## Audit Summary & Opportunities

The current script as written is relatively extensible. Values and variables for the candidates and counties is not hard coded and should work on similarly formatted data. Using similar data structures, the script could be extended to other data fields, such as the time the individual vote was cast (for forecasting staffing needs at the polls). The output is currently batch run and output to a text file, but the same basic core script could also be used to generate real-time data for an election day dashboard.
