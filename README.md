# Election_Analysis

## Election Analysis Overview
My buddies Tom and Seth asked me to perform an election audit for the Colorado Board of Elections by completing the following assignments.

1. Discover the number of total votes cast.
2. Create a list of all candidates who received votes
3. Compute how many total votes each candidate received.
4. Determine what percentage of votes each candidate won.
5. Decide which candidate won the election based upon the popular vote they received.

## Resources Used
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Analysis Results Summary
The election analysis revealed that:
- 369,711 votes were cast.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 votes in total.
    - Diana DeGette received 73.8% of the vote and 272,892 votes in total.
    - Raymon Anthony Doane reveived 3.1% of the vote and 11,606 votes in total.
- The winner of the election was:
    - Diana DeGette who reveived 73.8% of the vote and 272,892 votes in total.

## Election-Audit Summary
This script is able to be used in any election by simply replacing the `election_results.csv` file with the new election's data. As long as the file retains the same format the script should have no issue running it. If the board would like to keep separate names for their `election_results.csv` files, modifying the file path for the `file_to_load` variable would allow them to accomplish this in a relatively simple manner. Modifying the file path for the `file_to_save` variable would allow them to change where the results are saved. 
