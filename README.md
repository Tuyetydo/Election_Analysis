# Election_Analysis

## Overview of Project - Election Audit
I was requested by Tom, a Board of Elections employee to assist with the election audit of the tabulated results for the U.S. Congressional precinct in Colorado. The task was to report the total number of votes casted, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on popular vote. Tom’s boss is looking to see if it can be coded in python and if successful, this will be used not only for congressional districts but also senatorial districts and local elections. There are three primary voting methods that will be taken into account: mail-in ballots, punch cards, and direct recording electronic (DRE) counting machines. Once counted, my task was to generate a vote count report to certify this U.S congressional race. I submitted the audit results, and the election commission requested some additional data to complete the audit.


### Purpose
The purpose of this project is to provide two technical analysis deliverables and a written report to deliver the results. The requested deliverables to be provided to the election commission are:

- [x] Deliverable 1: The election results printed to the command line
- [x] Deliverable 2: The election results saved to a text file
- [x] Deliverable 3: Written analysis of the election audit

## Election-Audit Results
Below are the results based on the questions provided by the election commission:
![Election Results](/Resources/Election_Results.PNG)

- How many votes were cast in this congressional election? 
    - 369,711

- Provide a breakdown of the number of votes and the percentage of total votes for each   county in the precinct.

    - Denver | 306,055 Votes | 82.8%
    - Jefferson | 38,855 Votes | 10.5%
    - Arapahoe | 24,801 Votes | 6.7%

- Which county had the largest number of votes?
    - Denver has the largest number of votes at 305,555.

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

    - Diana DeGette | 272,892 Votes | 73.8%
    - Charles Casper Stockham | 85,213 Votes | 23.0%
    - Raymon Anthony Doane | 11,606 Votes | 3.1%

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

    - Diana DeGette won with 272,892 votes which represted 73.8% of the total votes. 

### Election-Audit Summary
As seen above, this script was able to quickly and clearly pull the additional information requested by the election commission. This script can be adapted not only for future elections for U.S. Congressional precinct in Colorado but any election. I can modify it to count the votes by the city or any other variable needed as long as we have the data. It also can be modified to show lowest turnouts as well to be used for future outreach as needed. 
