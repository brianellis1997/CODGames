# CODGames
Mini Project STAT 380

Tasks

1. Read the dataset into R.
•	We have not covered methods for reading an .xlsx file into R. 
•	Yes, you could save as .csv but that risks potential data loss. 
•	It would be better to search for a method (R function) that allows you to open .xlsx files in R.

2. Begin to explore the dataset. Explore 6 variables of your choice. (You should explore at least one categorical and at least one quantitative variable.)
•	For each, you should identify the variable, the type of variable (categorical, quantitative, etc.), information about the types of values the variable can take, and the amount of missing data within the variable. 
•	For each variable, report some summary statistics and make a visualization.
o	If a variable is categorical, make a table of possible values and include counts or proportions. Then, make an appropriate plot to show the distribution of values.
o	If a variable is quantitative, include some basic summary stats like the mean, median, standard deviation, min, max, etc. and make an appropriate plot to show the distribution of values.
•	For each variable, you should write a few sentences to describe what you have learned about the variable. Remember, the goal is not to make the plot/calculate the summaries. The goal is to use plots and summaries to gain knowledge from the data.

3. Begin a list of questions that you have about the dataset. Suppose you are working on a project and your manager gives you this dataset. Write 3 questions that you would ask your manager.
•	You have not been given any information about what the variables represent. So, if you are unsure about the meaning of any of the variables, write your questions.
•	You have not been given any information about how the data were collected. If you have questions about the data collection, write them down.
•	If you have any other questions, write them down.
•	NOTE: Even if you are familiar with the game and think that you understand the meaning of the variables, you are still expected to write 3 potential questions that you could ask.

4. Asking a question that can be answered using the dataset and data visualization.
•	Part 1 – You will answer my question: Is the player’s performance, as quantified by the amount of experience points gained (TotalXP variable) changing over time?
o	To answer this, you should find a way to extract the month from the Date variable (we have not covered working with dates in STAT 380)
o	The lubridate package is useful for working with dates
o	Once you have the months, create side-by-side boxplots showing the TotalXP based on the Month, where the months are named (i.e., month should be June, not the number 6). The months should be in chronological order, not alphabetical order
o	Based on the plot, answer the question. If you have knowledge about these types of games, you can also mention other variables that could affect TotalXP but were not included in the question.
•	Part 2 – You will write your own question, create a data visualization that can help answer your question, and write an answer to your question. The question/visualization should explore the relationship between at least 2 of the variables in the dataset. Be sure you include both the question and the answer to your question based on the visualization you have created.

