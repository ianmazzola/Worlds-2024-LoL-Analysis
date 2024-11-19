# League of Legends Worlds 2024 Analysis

## Overview

This project analyzes data from the 2024 League of Legends World Championship to uncover key insights into player performance and team strategies. By focusing on early game metrics and role-specific data, the analysis highlights critical factors that influence the win rate of players and teams.

## The Questions

1. **How do early game metrics (GD@15, XPD@15, CSD@15) influence the outcome of a match?**
2. **Which roles have the greatest impact on early game success?**
3. **Are there significant differences in performance based on Flash keybind preferences (D or F)?**
4. **What insights can outliers provide about exceptional or poor player performances?**

## Tools I Used

This analysis leverages Python and key data analysis libraries:
- **pandas**: Data manipulation and cleaning.
- **numpy**: Numerical operations and calculations.
- **matplotlib** and **seaborn**: Visualization tools for presenting insights.
- **Jupyter Notebook**: Environment for interactive data analysis.

## Data Preparation and Cleanup

The dataset required several preprocessing steps, including:
- Removing duplicates and null values.
- Handling outliers in metrics like KDA, GD@15, and CSD@15.
- Grouping and aggregating data by player roles and teams to identify trends.

Key columns analyzed:
- **KDA (Kill-Death-Assist ratio)**
- **GD@15 (Gold Difference at 15 minutes)**
- **CSD@15 (Creep Score Difference at 15 minutes)**
- **XPD@15 (Experience Difference at 15 minutes)**

## The Analysis

### Role-Based Performance
- **Top Lane**: Early game performance is strongly correlated with win rate. Gold and creep score differences at 15 minutes are crucial.
- **ADC**: Early game metrics have the lowest correlation with win rate, emphasizing late-game impact and team coordination.
- **Support**: Traditional metrics like CSD@15 have low or negative correlations, suggesting that vision and team impact metrics are more relevant.
- **Mid Lane**: Similar to top laners, early game metrics like GD@15 strongly impact success, but roaming and objective control also play key roles.
- **Jungle**: Gold and experience efficiency at 15 minutes are critical, while creep score differences are less relevant.

### Flash Keybind Preferences
The analysis explored how Flash keybind preferences (D vs F) relate to performance metrics and win rate. Players with Flash on **D** tend to perform slightly better in early game metrics, but no definitive advantage was observed.

## Insights and Results

- Players with exceptional KDA (>7.4) were standout performers, such as T1 botlane players, Keria and Gumayusi.
- Top lane and jungle roles are heavily influenced by early game metrics, reinforcing the importance of strong early game strategies.
- Supports exhibit unique performance trends, where traditional metrics fail to capture their full impact on the game.
- T1 Faker had a GD@15 of 741, exceeding the upper limit of 708, reinforcing his position as one of the best players.
- MDK Supa had an XPD@15 of 749, showcasing an outstanding performance in the early stages of the game.

## Conclusion

This analysis reveals how early game performance metrics shape the outcomes of matches in professional League of Legends. Insights from this project can inform strategic decisions for players and teams, such as prioritizing early game dominance in key roles.
