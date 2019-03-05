# nfl_playcall_decision_trees
Jupyter Julia notebook to create decision trees predicting whether given play was run or pass

Based on the following dataset from Kaggle...
https://www.kaggle.com/maxhorowitz/nflplaybyplay2009to2016

Goal was to get estimate of predictablility of a teams playcalling based on how predictive a limited decision tree
was (in this case, maximum depth of 3). 

Data Cleaning file was used to wanted information from the 700mb csv file into a more usable format and then to save
it to a feather file.

Decision Tree file shows initial experimentation with the Julia DecisionTree package. Output is hard to read as the code cell
output is not truncated in Github. End of the file has a list of teams from most to least predicatble over every season from 2009
to 2018, as well as decision trees using that data for both the LA Rams and the DAL Cowboys.

Decision Trees by Season file, on the other hand, has season information as well so that individual seasons can be compared (as 
opposed to an aggregation of all 10 seasons). This information is used to to rank the predictablity by season of a run/pass play 
for the HOU Texans and DAL Cowboys, as well as a decision tree for the most predictable Cowboys season (2015).
