# 🏏 T20 World Cup 2022 Data Analysis Project

This project presents an end-to-end data analysis of the T20 World Cup 2022, leveraging Python, pandas, and Power BI to extract meaningful insights and visualizations. The primary objective was to determine the **Best 11 Players Team** based on their performance metrics. 

## 🌟 Key Steps in the Project

1. **Data Collection**: Gathered comprehensive T20 World Cup 2022 data.
2. **Data Cleaning and Transformation**: Utilized pandas to clean and transform raw data for accurate analysis.
3. **Exploratory Data Analysis (EDA)**: Conducted EDA to identify key performance indicators and trends.
4. **Team Selection Criteria**: Developed criteria for selecting the best 11 players based on statistical performance.
5. **Dashboard Creation**: Designed interactive dashboards in Power BI to visualize player statistics, match outcomes, and team performances.

The final deliverable is a robust and visually appealing Power BI dashboard that provides deep insights into player performances and helps in forming an optimal team. This project showcases my skills in data manipulation, analysis, and visualization, and offers valuable insights into the T20 World Cup 2022.

## 📂 Dataset Overview

### **1. `dim_players.csv`**: Player Information
- **Player Name**: The name of the cricketer.
- **Team**: The country the cricketer represents.
- **Image**: A URL link to the cricketer's profile image.
- **Batting Hand**: The hand the cricketer uses for batting.
- **Bowling Style**: The cricketer's bowling style.
- **Playing Role**: The primary role of the cricketer (e.g., Bowler, Batter, Allrounder, Wicketkeeper Batter).
- **Player Description**: A brief description of the cricketer's background, skills, and achievements.

### **2. `dim_match_summary.csv`**: Match Summary
- **team1**: Represents the first team participating in the match.
- **team2**: Represents the second team participating in the match.
- **winner**: Represents the winning team of the match.
- **margin**: The winning margin (runs, wickets, etc.).
- **ground**: The location or stadium where the match was played.
- **matchDate**: The date on which the match was played.
- **match_id**: A unique identifier for the match.

### **3. `fact_batting_summary.csv`**: Batting Statistics
- **match**: The match ID for the T20I game.
- **teamInnings**: The team and innings (e.g., "Namibia,1" means Namibia's first innings).
- **battingPos**: The batting position of the player.
- **batsmanName**: The name of the batsman.
- **runs**: The number of runs scored by the batsman.
- **balls**: The number of balls faced by the batsman.
- **4s**: The number of fours hit by the batsman.
- **6s**: The number of sixes hit by the batsman.
- **SR**: The strike rate of the batsman (runs per 100 balls faced).
- **out/not_out**: Whether the batsman was out or not out.
- **match_id**: The unique identifier for the T20I match.

### **4. `fact_bowling_summary.csv`**: Bowling Statistics
- **match**: The match ID for the T20I game.
- **bowlingTeam**: The team that is bowling.
- **bowlerName**: The name of the bowler.
- **overs**: The number of overs bowled by the bowler.
- **maiden**: The number of maiden overs bowled.
- **runs**: The number of runs conceded by the bowler.
- **wickets**: The number of wickets taken by the bowler.
- **economy**: The economy rate of the bowler (runs conceded per over).
- **0s**: The number of dot balls bowled by the bowler.
- **4s**: The number of fours conceded by the bowler.
- **6s**: The number of sixes conceded by the bowler.
- **wides**: The number of wides bowled by the bowler.
- **noBalls**: The number of no-balls bowled by the bowler.
- **match_id**: The unique identifier for the T20I match.

## 🛠️ Tools and Technologies Used

- **Jupyter Notebook**: Performed data cleaning and transformation of raw data for accurate analysis. Conducted EDA to identify key performance indicators and trends.
- **Power BI**: Designed interactive dashboards to visualize player statistics, match outcomes, and team performances.

## 📊 Data Model

![Data Model](https://github.com/RenukaSutone/T20-Worldcup-end-to-end-Data-Analysis/assets/76682535/01f5fb0e-d196-4907-b9a1-f31131983b52)

## 📸 Screenshots

### **1. Power Hitters Analysis**
This dashboard page provides detailed information about the power hitters. It includes metrics such as bowling average, strike rate, dot ball percentage, and economy rate for these players. Additionally, you can view a scatter plot showing the relationship between economy rate and bowling strike rate for different players.

![Power Hitters](https://github.com/RenukaSutone/T20-Worldcup-end-to-end-Data-Analysis/assets/76682535/cdff49d8-62e0-4d2d-b27a-728d94714a30)

### **2. Individual Player Performance**
This page provides a detailed analysis of a player's performance throughout the tournament.

![Player Performance](https://github.com/RenukaSutone/T20-Worldcup-end-to-end-Data-Analysis/assets/76682535/05c1f18c-f8a3-4053-82c9-a9fc711c5054)

### **3. Combined Player Performance**
You can also view the combined performance of two players.

![Combined Performance](https://github.com/RenukaSutone/T20-Worldcup-end-to-end-Data-Analysis/assets/76682535/39e9e128-bbb1-4857-b31c-87508f42b8e3)

### **4. Anchors Analysis**
This dashboard page provides detailed information about the Anchors. It includes metrics such as bowling average, strike rate, Boundary%, and Average balls faced rate for these players. Additionally, you can view a scatter plot showing the relationship between strike rate and batting average for different players.

![Anchors Analysis](https://github.com/RenukaSutone/T20-Worldcup-end-to-end-Data-Analysis/assets/76682535/59d8d91c-ce12-485e-b89d-a60f6324ad89)

### **5. Finishers Analysis**
This dashboard page provides detailed information about the Finishers. It includes metrics such as batting average, batting strike rate, average balls faced, and bowling strike rate for these players. Additionally, you can view a scatter plot showing the relationship between batting average and strike rate for different players.

![Finishers Analysis](https://github.com/RenukaSutone/T20-Worldcup-end-to-end-Data-Analysis/assets/76682535/6cbf9839-c6e0-4680-8ed6-d6765a2b79e9)

### **6. All Rounders Analysis**
Detailed information about the all-rounders' performance.

![All Rounders](https://github.com/RenukaSutone/T20-Worldcup-end-to-end-Data-Analysis/assets/76682535/cb4e14d6-9487-4cd7-aa70-bd3afc843717)

### **7. Specialist Fast Bowlers Analysis**
This dashboard page provides detailed information about the specialist fast bowlers.

![Fast Bowlers](https://github.com/RenukaSutone/T20-Worldcup-end-to-end-Data-Analysis/assets/76682535/37fcb92e-a3ce-4467-8b90-2e0d8a489714)

### **8. Final 11 Players**
This dashboard page provides detailed information about the Final 11 players selected based on statistical performance.

![Final 11 Players](https://github.com/RenukaSutone/T20-Worldcup-end-to-end-Data-Analysis/assets/76682535/df46fda7-90df-49f8-9ea4-0a77c85a46ac)

## 🎯 Conclusion

This project not only demonstrates my ability to work with large datasets and perform detailed analyses but also showcases my skills in data visualization and storytelling through Power BI. The insights derived from this analysis can be pivotal in understanding player performances and making strategic decisions.

---









