Data Science Project: Planning Stage (Individual)
In this class, you will complete a full Data Science project from beginning to end, and produce a report communicating your methods and conclusions in a Jupyter Notebook. The Jupyter Notebook will perform the entire analysis: the code cells will download a dataset, reproducibly and sensibly wrangle and clean, summarize and visualize the data, as well as appropriately answer a predictive question. Markdown cells will be used throughout the document to narrate the analysis and communicate the question asked, methods used and the conclusion reached.

Problem: Predicting Usage of a Video Game Research Server
This year we have a unique opportunity: we have a real data science project with real stakeholders who are looking for answers to a few questions about their data.

In particular, a research group in Computer Science at UBC, led by Frank Wood, is collecting data about how people play video games. They have set up a MineCraft serverLinks to an external site., and players' actions are recorded as they navigate through the world. But running this project is not simple: they need to target their recruitment efforts, and make sure they have enough resources (e.g., software licenses, server hardware) to handle the number of players they attract. There are three broad questions of interest. 

Question 1: What player characteristics and behaviours are most predictive of subscribing to a game-related newsletter, and how do these features differ between various player types?

Question 2: We would like to know which "kinds" of players are most likely to contribute a large amount of data so that we can target those players in our recruiting efforts.

Question 3: We are interested in demand forecasting, namely, what time windows are most likely to have large number of simultaneous players. This is because we need to ensure that the number of licenses on hand is sufficiently large to accommodate all parallel players with high probability. 

In your project, you will select one of these broad questions and use it to formulate a specific question using some of the variables in the dataset.  Your project should answer your specific question. 

The Data
The data consist of two files:

players.csv Download players.csv: A list of all unique players, including data about each player.

sessions.csv Download sessions.csv: A list of individual play sessions by each player, including data about the session.

Grade Breakdown
The group project is worth 10% of your final grade overall, with the following breakdown:

Team Contract: 0% (you will receive 0% on the whole project if you do not complete this with your group)
Individual Planning Report: 3%
Final Project Report: 7%
Individual Planning Report

Each student is expected to prepare a 1 page (max 500 words, where code does not count toward the word count) written proposal that describes the data they are working on, demonstrates an understanding of all variables and potential issues in the data, and identifies both the broad question they would like to address and the specific question they have formulated. The proposal should be done in a Jupyter notebook, and then submitted in two formats:

as an .html file (File -> Download As -> HTML)
as an .ipynb file. This file must be fully reproducible. It must run completely from top to bottom without any additional files.
It's important to note that this first step in the project will be completed individually. Every student needs to write and submit their own assignment. We aim to ensure that all students in the group are well-prepared and able to contribute effectively to the final report.

In your planning report you need to cover the following: 

(1) Data Description:
Provide a full descriptive summary of the dataset, including information such as the number of observations, summary statistics (report values to 2 decimal places), number of variables, name and type of variables, what the variables mean, any issues you see in the data, any other potential issues related to things you cannot directly see, how the data were collected, etc. Make sure to use bullet point lists or tables to summarize the variables in an easy-to-understand format.

Note that the selected dataset(s) will probably contain more variables than you need. In fact, exploring how the different variables in the dataset affect your model may be a crucial part of the project. You need to summarize the full data regardless of which variables you may choose to use later on.

(2) Questions:
Clearly state one broad question that you will address, and the specific question that you have formulated. Your question should involve one response variable of interest and one or more explanatory variables, and should be stated as a question. One common question format is: “Can [explanatory variable(s)] predict [response variable] in [dataset]?”, but you are free to format your question as you choose so long as it is clear. Describe clearly how the data will help you address the question of interest. You may need to describe how you plan to wrangle your data to get it into a form where you can apply one of the predictive methods from this class.

(3) Exploratory Data Analysis and Visualization
In this assignment, you will:

Demonstrate that the dataset can be loaded into R.
Do the minimum necessary wrangling to turn your data into a tidy format. Do not do any additional wrangling here; that will happen later during the group project phase.
Compute the mean value for each quantitative variable in the players.csv data set. Report the mean values in a table format.
Make a few exploratory visualizations of the data to help you understand it.
Use our visualization best practices to make high-quality plots (make sure to include labels, titles, units of measurement, etc)
Explain any insights you gain from these plots that are relevant to address your question
Note: do not perform any predictive analysis here. We are asking for an exploration of the relevant variables to demonstrate that you understand them well before performing any additional modelling, and to identify potential problems you anticipate encountering.

(4) Methods and Plan
Propose one method to address your question of interest using the selected dataset and explain why it was chosen. Do not perform any modelling or present results at this stage. We are looking for high-level planning regarding model choice and justifying that choice.

In your explanation, respond to the following questions:

Why is this method appropriate?
Which assumptions are required, if any, to apply the method selected?
What are the potential limitations or weaknesses of the method selected?
How are you going to compare and select the model?
How are you going to process the data to apply the model? For example: Are you splitting the data? How? How many splits? What proportions will you use for the splits? At what stage will you split? Will there be a validation set? Will you use cross validation?
(5) GitHub Repository

Provide the link to your GitHub repository for the project. You must have at least five commits with a description of the work that has been done towards completion of the individual report in the commit history of this repository. 