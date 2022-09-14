# Election_Analysis

## Overview of Election Audit:
Tom and Seth asked us to create an Election Audit that should help them with the following outcomes:
1. Total number of votes casted
2. The percentage of votes for each candidate and 
3. The winner of the election based on the popular vote

## Background:

The Election Results are calculated using 3 primary resources:

1. Mail in Ballots (Physically counted)
2. Punch Cards (read through card reader)
3. DRE (direct recording electronic counting)

All votes are counted and sent to the central office. Once counted the results are gathered in a csv file.

## Purpose:
Our job was to generate a vote count report to certify the US congressional race by using Python and Visual Studio. The Results were generated through a csv file and the results were extracted on to a text file. 

## Election Audit Results:
![electionResults](https://user-images.githubusercontent.com/111619125/190239603-2ac33587-12f6-4735-a7be-b0dad3d27955.png)

As the above picture shows:
* There were Total of 369,711 votes casted
* The three candidates were:

1.Charles Casper Stockham
2.Diana DeGette
3.Raymon Anthony Doane

With "Diana Degette" being the Winner with 73.8% of votes

* The number of counties were 3:

1.Jefferson
2.Denver
3.Arapahoe

With "Denver" being the largest county turnover.

## Election Audit Summary:

Coding with Python was easy and quick to grasp all the results for a large and numerous data. Due to fast execution and reusing of the coade, it makes it less time consuming to deal with a large number of data.This code helped us with the following findings:

-candidates names,

-counties,

-count votes for each candidate and calculate vote %,

-count turnout per county and calculate their %,

-candidate winner base on the highest vote count and %,

-county with the highest turnout.

## What's Next:

* With fewer alterations we can use the same code on different projects such as: congressional district elections, senatorial districts, local elections, and more.

* As python script can find unique candidates names and county names we can use it for a much larger dataset by adding more counties and cadidates.

* Also, we can add more If statements and compare the data in a different way."for example, we can find which county voted for which candidate" or "which candidate performed poor in which county".

* Moreover we can add a "datetime" dependency that can calculate the votes in real time.




