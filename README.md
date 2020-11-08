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

1)	**The total count** was retrieve by reading through the document using the `(file reader)` and looping `for`   through each row. 

2) **The summary of vote count and percentage per county** was retrieve by looping `for` an retrieving the county_vote and calculating the percentage with the formula `country_ percentage= (votes_c) / (total_votes)*100.` This provided the following results: 
<Screen Shot> 
  
3)	**The county with the larges number of votes was** `Devender` and this result was obtain by implementing a conditional `if` 

4)	**The summary of count and percentage of votes per candidate** was retrieve by looping `for` and retrieving the  `votes` per candidate , then calculating the percentage per each candidate with the formula `vote_percentage= (votes) / (total_votes)*100.` The final results were the following: 

<screen shoot> 

5)	**To obtain the winner of the election** we used the conditional statement `if` retrieve the  `winning_count` and ` winning_percentage`obtaining the following results:  

<Screen shoot> 

# Election Audit Summary
The election audit script was written with the intention for repurposing for future elections since its language is easy to read and the only requirement is a csv  file with the key components  ` place, votes and candidate.` 
