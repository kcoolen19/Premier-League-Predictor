 # PROJECT DETAILS

# PROJECT GOAL:
Build a ML model to predict the points tally and ranking of the football teams in the Premier League for the current 2024/2025 season and beyond using Linear Regression. <br />

# Datasets
The data from different seasons for the relevant variables is stored in .csv files. There will be different folders used to classify the information of the relevant variables.

# Variables:
The points tally of the Premier League teams from the past 8 seasons will be primarily used in getting to train and test the datasets. <br />

Main variables:
- Number of wins
- Number of losses
- Number of draws
- Goals scored
- Goals conceded
- Goal Difference
- Expected Goals Scored(xG)
- Expected Goals Conceded(xGA)

Other potential variables researched: 
- Injuries to players
- Ball Possession in the game
- Chances created
    - Open Play
    - Set Pieces
- Chances conceded
- Clean Sheets
- Manager's statistics with previous teams

# Data Pre-Processing
Some teams will be missing their points tally in the league due to relegation to the lower division of English football hierarchy. Their points tally in the lower division league will be used as a reference normalized to the following factors:
- The difficulty of the Premier League in the year they were absent
- Analyze and predict their points based on teams that finish close to them in different seasons
- Use matches in domestic cup competitions against Premier League opposition as outside reference to compare their levels and use that as factor to predict points.

# Data Collection sources
- Premier League website: https://www.premierleague.com <br />
      - Stats Hub: https://www.premierleague.com/stats <br />
      - Tables Hub: https://www.premierleague.com/tables
- Sofascore: https://www.sofascore.com
- Opta Analyst: https://www.google.com/search?client=safari&rls=en&q=opta+analyst&ie=UTF-8&oe=UTF-8
- Fbref: https://fbref.com/en/comps/Big5/keepersadv/players/Big-5-European-Leagues-Stats
