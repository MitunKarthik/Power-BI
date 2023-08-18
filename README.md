# PowerBI--IPL_Analysis
In this project, I have performed an in-depth analysis of the Indian Premier League (IPL) cricket tournament using the Power BI tool. 
My goal is to provide valuable insights and visualizations that help cricket enthusiasts, analysts, and fans to better understand the tournament's data.

# Project Overview
The Indian Premier League (IPL) is one of the most popular T20 cricket tournaments globally, featuring top players from around the world. This project aims to 
explore and analyze various aspects of IPL using Power BI's powerful data visualization capabilities. The project covers:

Data Collection: The dataset used was taken from Kaggle which includes match statistics, player performances, team details, ball by ball data and more.
The dataset contains two csv files "matches" and "ball-by-ball". Each csv file contains one table.
After downloading the data upload it to SQL and connect it to Power BI 
The link to data : https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020.


Data Transformation: Upon importing the data into Power BI, various transformations were applied using the Power Query Editor. These transformations included 
actions like eliminating and introducing new columns, as well as adjusting data types. These steps were taken to optimize the data for effective data 
visualization purposes.

Data Modelling: Following the data transformation process, the data underwent modeling by establishing connections between tables through joins within the 
Model View of Power BI.

Data Visualization: The process of Data Visualization encompassed the creation of new measures utilizing DAX functions, incorporating slicers, and integrating 
charts to facilitate the exploration of intriguing data insights. 
This particular Dashboard gives the follwing insights : 

Slicers have been implemented to enable the following functionalities:
1. Selecting the desired year's statistics for display.
2. Choosing specific batsmen and bowlers to visualize their respective statistics.

I had added filters and formulated measures using DAX function to extract the subsequent statistics:
1. The champion of the specific season.
2. The player awarded the Orange Cap for that particular season.
3. The player awarded the Purple Cap for that specific season.
4. The total number of 6's recorded in the tournament.
5. The total number of 4's recorded in the tournament.
6. Batting statistics comprising the Batsman's Runs Scored, 6's and 4's struck by the batsman, and the Batsman's Strike Rate.
7. Bowling statistics encompassing the Bowler's Wickets taken, Economy Rate, Average, and Bowling Strike Rate.

Doughnut charts have been integrated to provide visualizations for the following insights:
1. The count of matches won categorized by the Toss Decision (Batting First/Bowling First).
2. The distribution of matches won based on the final result.

Column charts have been employed to facilitate visualization of the subsequent information:
1. Matches won by Venue categorized by the result of the matches.
2. The aggregate count of matches won by each team during the specific season.

   

