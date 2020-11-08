# Overview of Election Audit 
The purpose of this analysis is to obtain the results of the county election results for the state of Colorado. The Board requested the following information:
 1)	**Total Votes**
 2)	**Percentage and total votes per county**
 3)	**Largest County Turnout**
 4)	**Percentage and total votes per candidate**
 5)	**Name, vote count and percentage of the candidate winner**

## Resources 
-**Data Source:** election_results.csv.

-**Software:** Python 3.6.1, Visual Studio Code 1.51.0.

# Election Audit Results 

The analysis of the election show that:

1)	**The total count** was retrieve by reading through the document using the `(file reader)` and looping `for`   through each row and the **result was 369,711**

2) **The summary of vote count and percentage per county** was retrieve by looping `for` an retrieving the county_vote and calculating the percentage with the formula `country_ percentage= (votes_c) / (total_votes)*100.` This provided the following [results:](Resources/Country count.png) 
  
3)	**The county with the larges number of votes was** `Devender` and this result was obtain by implementing a conditional `if` to obtain the `winnning_country` and `county_count`

4)	**The summary of count and percentage of votes per candidate** was retrieve by looping `for` and retrieving the  `votes` per candidate , then calculating the percentage per each candidate with the formula `vote_percentage= (votes) / (total_votes)*100.` [The final results were:](Resources/summary per candidate.png)

5)	**The winner of the election was Diana DeGette**. The process to obtains that result was by applying a conditional statement `if` to retrieve the  `winning_count`**272,892** and ` winning_percentage`**73.8%**

In the following image is the summary of the election [audtit results](Resources/Elections summary.png)


# Election Audit Summary
The election audit script was written with the intention for repurposing for future elections since its language is easy to read and the only requirement is a csv  file with the key components  ` place, votes and candidate.` 
