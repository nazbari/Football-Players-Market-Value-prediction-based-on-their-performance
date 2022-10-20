# BrainStation Capstone Project

BrainStation Data Science Bootcamp

### Capstone Project –
### Predicting Football Players Market Value based on their performance

Author: Nazhad Bari

Email: barinaz2490@gmail.com


Project Description:

My Capstone project is on Predicting the Football Players Market Value based on their on-field performance and finding the factors that determines this value. The transfer market in Football world is considered one of the most competitive and expensive transactional activities in the world. Football club Chelsea spent around € 200 million in 2021. Top clubs spend large sums of money in the hopes of winning matches, Cups and the hearts of millions of fans. So clubs need to be very careful when they do a transaction in the transfer market. This project focuses on predicting the player market value and the factors that affect this value.

Data has been collected for all players from Europe’s top 5 leagues for 10 years from 2011 to 2021. The leagues are - English Premier League, Italian Serie A, Spanish La Liga, German Bundesliga and French Ligue 1. The datasets have been acquired from 2 different websites:
• Transfermarkt dataset - containing player information and their Transfer Market Value.
• fbref datasets - containing player on-field performance standard statistics data (10 datasets from the years 2011 to 2021 joined together to create one dataset).
The two datasets have been joined together to create one complete dataset that contains 3 different types of data:
• Player information like their name, age, nation, on-field position, current team, previous team, Football league, year the market value was recorded, transfer fee amount, market value, etc.
• Player performance statistics like goals scored, assists made, non-penalty goals, matches played, etc. It also contains per 90 minutes performance statistics that represent the statistics based on per game.
• Player potential performance statistics like expected goals, expected assists, etc.

The target variable of this project is the “Market Value amount in EUR” converted to millions. A player's Market Value is an estimate of the amount for which a team can sell the player's contract to another team.

In the two notebooks, I have combined the datasets, cleaned and performed exploratory data analysis, wrangling and then preprocessed and performed Machine Learning modeling on the data in order to get a data driven understanding about the Market Values.



I have submitted the following files in a zipped folder as part of the Final Capstone Submission:

1. ReadMe.txt 
	- this Read Me txt file containing information about each part of the submission.

2. Nazhad_Bari_Capstone_Project_Final_Report.pdf 
	- Final Capstone project Report in pdf format.

3. Nazhad Bari_Capstone Project - Notebook-I (Cleaning, EDA, Modeling).ipynb 
	- Jupyter Notebook containing the codes with comments of data loading, merging, cleaning, EDA, Machine Learning modeling and findings.

4. Nazhad Bari_Capstone Project - Notebook-II (Random Forest and Boosting).ipynb
	- Jupyter Notebook containing codes with comments of more powerful modeling on the dataset like Random Forest, AdaBoost, Gradient Boost and XGBoost.

5. Data Folder:
	i) transfers.csv 
		- the Transfermarkt dataset containing player information and Market Value. This has been downloaded from https://github.com/d2ski/football-transfers-data
	ii) stats folder 
		- contains 10 datasets about player information for 10 years from 2011 to 2021. They have been downloaded from https://fbref.com/en/ 
		The datasets are:
			- fbref-2021.csv
			- fbref-2020.csv
			- fbref-2019.csv
			- fbref-2018.csv
			- fbref-2017.csv
			- fbref-2016.csv
			- fbref-2015.csv
			- fbref-2014.csv
			- fbref-2013.csv
			- fbref-2012.csv
			- fbref-2011.csv
	iii) market_val_stats.csv 
		- the final complete and cleaned dataset containing player information, market value, player standard performance statistics and player potential performance statistics.
