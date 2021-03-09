# Module 3 Python3 Challenge: PyPoll
---
## Overview of Election Audit:
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Get a complete list of the counties where people voted in this election.
4. Calculate the total number of votes each candidate received.
5. Calculate the total number of votes that were casted in each county.
6. Calculate the percentage of votes each candidate won.
7. Calculate the percentage of votes of each county.
8. Determine the winner of the election based on popular vote.
9. Determine the county with the most votes casted.

### Resources Used:
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.54.1
---

## Election-Audit Results
The analysis of the election show that:

- There were 369,711 votes cast in the election.

- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane

- The counties that participated in this election were:
  - Jefferson
  - Arapahoe
  - Denver

- The county with the most votes was:
  - Denver County which had 82.8% of the votes relative to the total votes casted in this election.
  - Denver County received 306,055 votes in total.  

- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes. 
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
  
- The winner of the election was:
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes. 
---

## Election Audit Summary
- The winner of the recent local congressional election in Colorado was Diana Degette who received 73.8% of the vote. The county where the most votes were casted was Denver.

![Election_Results_CSV](https://github.com/mbroad1/Module-3-PyPoll-Challenge/blob/a32abfed7e9664b3a6582247af911e264eac1273/Election%20Results%20CSV.png)

- The script written to determine the total votes, the votes for each candidate, the percentage of votes for each candidate, the candidate winner, the votes casted in each county, the percentage of votes casted in each county, and the county with the most votes can be reused again for another election if the .csv file of the data for that election was formatted the same as the election_results.csv file that was used for the script (seem image above for reference). 

![Election Index Example](https://github.com/mbroad1/Module-3-PyPoll-Challenge/blob/3f950feef08bb3d6d475fe60fc0eec99241780b6/Election%20Index%20Example.png)

- One way to reuse this script for another election is if the ballot ID, county, and candidate columns are in a different order for another election data to be analyzed, be sure that the index number placed for these variables match the column in which you want the data from so that the same code can be reused.

- Likewise, the second way to reuse this script could be for a presidential election. However, in order to declare which state a candidate won, there would have to be both an analysis of who won which county and then an additional analysis to sum up which candidate won the majority of the vote in that state in order to reflect the complexity of the electoral college.

- Overall, this script can be reapplied to many different election scenarioes such as a school student body president election (in this case, the code pertaining to information about the counties is unnecessary) or a presidential election in which more code would needed to be added in order to account for how the electoral college operates.
