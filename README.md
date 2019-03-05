# nfl_playcall_decision_trees
Jupyter Julia notebook to create decision trees predicting whether given play was run or pass

Based on the following dataset from Kaggle...
https://www.kaggle.com/maxhorowitz/nflplaybyplay2009to2016

Goal was to get estimate of predictablility of a teams playcalling based on how predictive a limited decision tree <br>
was (in this case, maximum depth of 3). 

Data Cleaning shows the process of getting wanted information from the 700mb csv file into a more usable format, and then saving
it to a feather file.
