# Election Analysis

## Overview of Election Audit

The script written in this project computes key aspects of elections and also outputs the findings onto a text file. The algorithm quickly calculates the total votes casted and then assigns the votes to the respective county and the candidate. It then moves on to find each candidates/county's share of vote eventually deducing the winner/highest turn out county. These results are then transferred to a text file.

## Election-Audit Results

### * How many votes were cast in the election?

Election Results

Total Votes: 369,711

### * Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

County Votes:  
Jefferson: 10.5% (38,855).  
Denver: 82.8% (306,055).   
Arapahoe: 6.7% (24,801). 

### * Which county had the largest number of votes?

Largest County Turnout: Denver

### * Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Charles Casper Stockham: 23.0% (85,213).   
Diana DeGette: 73.8% (272,892).    
Raymon Anthony Doane: 3.1% (11,606).    

### * Which candidate won the election, what was their vote count, and what was their percentage of the total votes?


Winner: Diana DeGette.     
Winning Vote Count: 272,892.  
Winning Percentage: 73.8%.     



## Election-Audit Summary

This script can me modified in multiple ways in order to use it for different elections. For example the first and most import change can be the ammendment of the file path. Instead of encoding this particular csv file, any other file can be chosen in order to be analyzed. Secondly if the election commission wants to print out the loser instead of the winner, the code can be slightly modified. It can be done by adding an elif statement as shown below:

<img width="588" alt="Screen Shot 2021-01-14 at 4 54 08 PM" src="https://user-images.githubusercontent.com/73799417/104653832-32ef8b80-5689-11eb-9f08-8fdd1b44810e.png">
