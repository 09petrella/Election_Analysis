# Election Audit Python Analysis

## Overview of Project 

### Purpose
Our purpose for this project is to assist the Colorado Board of Elections by working with election results to build an automated script using Python programming language. The script is used for reporting key election results from the tabulated vote data collected over the voting period. The key results from the election are typically determined by using Excel, but our goal is to automate the process to save time and increase the Board of Election's efficiency in the reporting process for this election along with future races. Once this scrip is proven to be successful, it can be enhanced with minor changes to be used in any election. 

## Election-Audit Results

### Election Outcomes
- There was a total of 369,711 votes cast in this congressional election. 
- As shown in the Python script's output below, the following results is the vote breakdown between county in the precinct. 
  - Jefferson County had 38,855 votes cast for 10.5% of the total vote results.
  - Denver County had 306,055 votes cast for 82.8% of the total vote results.
  - Arapahoe County had 24,801 votes cast for 6.7% of the total vote results. 
- Denver County had the largest number of votes cast in this election at 306,055. 
- As shown in the script's output below, the following results is the vote breakdown between each candidate. 
  - Charles Casper Stockham had 85,213 votes for 23.0% of the total votes in the election.
  - Diana DeGette had 272,892 votes for 73.8% of the total votes in the election.
  - Raymon Anthony Doane had 11,606 votes for 3.1% of the total votes in the election. 
- Diana Degette has won this election at 272,892 votes which was 73.8% of the total vote count. 
![Election Analysis Results]

## Election-Audit Summary

### Expanding Python Election Script
With a few further enhancements the script used in this election can be repurposed to assist reporting any election's result which will help the election process become more efficient with faster results on even larger volumes of total vote data. One of the modifications to the script that can be changed quickly to fit the needs for any election while using this same code structure is to adjust the variable names created for specifically the counties. Depending on each election, the python list and dictionary created to track the election's votes can have its variable name easily modified to fit the needs for any election. In terms of the code itself, the key for providing the accurate results are the data structures themselves. Another minor modification from the script that can be adjusted for any election is it prints out and writes the results onto the .txt document in our case. Along with the adjustment for the variables, the print statement for the script can be easily modified to fit the results output for each election.  



