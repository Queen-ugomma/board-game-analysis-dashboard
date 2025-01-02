# board-game-analysis-dashboard

**Table of Contents**
Project Overview
Problem Statement / Objective
Datasource and Structure
Tools and Methodology
Process
Key Insights and Findings
Recommendations
Conclusion

**Project Overview**
This project analyzes over 15,000 board games to uncover trends in popularity, complexity, and player demographics. The goal is to provide actionable insights for stakeholders in the board game industry or enthusiasts seeking better game recommendations. The dataset was analyzed using Power BI for data cleaning, transformation, and visualization.

**Problem Statement / Objective**
The primary objective was to address the following questions:

What are the most popular board games based on ratings?
How does complexity influence playtime?
Which demographics (e.g., age range, player count) are targeted by different games?

**Datasource and Structure**
**Datasource:**
The dataset contains information on board games, including details such as name, ratings, complexity, player count, and playtime.
**Dataset Structure:**
Attributes Used:
Game Title
Year Published
Average Rating
Playtime
Complexity Rating
Recommended Age
Minimum and Maximum Players

**Tools and Methodology**
Tools:
Power BI: For data cleaning, transformation, and visualization.
DAX: For creating calculated columns and measures.

**Methodology:**
Data Cleaning: Removed null, empty, and duplicate values; renamed columns; and added conditional columns for age range, year range, and player range.
Data Transformation: Added a DAX column for complexity levels and a DAX table for calculating KPIs like average rating, average playtime, and total games.
Process

**Data Cleaning:**
Removed null, empty, and duplicate values.
Eliminated unnecessary columns.
Renamed columns for clarity.
Added conditional columns:
Age Range
Year Range
Player Range
Created a calculated DAX column for Complexity Level.

**Data Transformation:**

**Calculated DAX measures:**
Total Games: Distinct count of game titles.
Average Rating: Mean of game ratings.
Average Playtime: Mean playtime in hours.

**Visualization:**
Page 1 (Overview):
KPIs: Total Games, Average Playtime, Average Rating.
Visuals: Playtime by Complexity, Player Range Distribution, Top 10 Game Ratings.
Filters: Year Range, Age Range, Player Range.
Page 2 (Detailed Insights):
KPIs repeated for context.
Visuals: Total Games by Year Range, Ratings by Age Range.
Parameter: Top N Games filter for dynamic exploration.

**Key Insights and Findings**
**Player Preferences:**
Most games are designed for 3-5 players, accounting for 47.63% of the dataset.
Games for 1-2 players and 6-10 players follow closely.

**Complexity and Playtime:**

Complex games have the longest average playtime (1,097 hours), while simple games have shorter playtimes (~37.59 hours).
Game Popularity:

The highest-rated games include "Star Trek" and "Wings of Infinity," with average ratings exceeding 9.

**Demographics:**

Games for the 11-15 years age group have the highest average ratings (677).

**Recommendations**
Focus on creating games for 3-5 player groups, as they dominate the market.
Develop games targeting 11-15 years, as this age group has shown the highest engagement and satisfaction.
Balance complexity with shorter playtime to appeal to a broader audience.

**Conclusion**
This analysis demonstrates the value of data-driven insights in understanding trends in the board game industry. By leveraging Power BI, this project identifies key patterns in game popularity, complexity, and player demographics, offering actionable recommendations for game developers and enthusiasts alike.
