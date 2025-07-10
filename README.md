# ⚽ Premier League Points Predictor

## 🎯 Project Goal  
Build a **machine learning model** to **predict the final points tally and ranking** of Premier League teams for the **2024/2025 season and beyond** using **Linear Regression**.

![premier-league-logo-symbol-with-name-black-design-england-football-european-countries-football-teams-illustration-free-vector](https://github.com/user-attachments/assets/00b49ac7-1d44-490e-bc8e-6374757e7102)



## 📂 Datasets  
The dataset includes multiple `.csv` files, each representing different seasons and variables. The files are organized into folders by variable type and source.



## 📊 Main Variables Used  
The model will primarily use historical data from the **last 8 seasons** of the Premier League.

- ✅ Wins  
- ❌ Losses  
- 🤝 Draws  
- 🎯 Goals Scored  
- 🛡️ Goals Conceded  
- ➖ Goal Difference  
- 📈 Expected Goals (xG)  
- 📉 Expected Goals Against (xGA)



## 🔍 Additional Variables Under Consideration  
These features may improve predictive performance with further research:

- 🚑 Injury records  
- 🕹️ Ball possession %  
- 🧠 Chances created (Open Play / Set Pieces)  
- 🛑 Chances conceded  
- 🧼 Clean sheets  
- 🧑‍💼 Manager stats from previous teams



## 🧹 Data Pre-Processing  
For teams **relegated** in certain seasons:

- Normalize lower-division performance by adjusting for Premier League difficulty that season  
- Compare with similarly ranked teams across years  
- Use **domestic cup** match data vs PL teams as proxy to assess performance level



## 🌐 Data Sources  

- [Premier League Official Site](https://www.premierleague.com)  
  - [Stats Hub](https://www.premierleague.com/stats)  
  - [Tables Hub](https://www.premierleague.com/tables)  
- [Sofascore](https://www.sofascore.com)  
- [Opta Analyst](https://www.google.com/search?client=safari&rls=en&q=opta+analyst&ie=UTF-8&oe=UTF-8)  
- [Fbref](https://fbref.com/en/comps/Big5/keepersadv/players/Big-5-European-Leagues-Stats)  
- [Understat](https://understat.com)
