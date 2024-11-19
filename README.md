
# League of Legends Worlds 2024 Analysis

## Project Overview

This project analyzes data from the League of Legends World Championship 2024 to uncover insights about player performance, early game metrics, and their impact on win rate. The analysis focuses on different roles, metrics like KDA, GD@15, XPD@15, and team strategies.

## Dataset

The dataset was cleaned and processed for this analysis. Key metrics include:
- **KDA (Kill/Death/Assist ratio)**
- **CSM (Creep Score per Minute)**
- **GD@15 (Gold Difference at 15 minutes)**
- **CSD@15 (Creep Score Difference at 15 minutes)**
- **XPD@15 (Experience Difference at 15 minutes)**

## Tools and Libraries

The following tools were used for data analysis and visualization:
- **Python**: Core programming language.
- **pandas**: Data manipulation and preprocessing.
- **numpy**: Numerical computations.
- **matplotlib** and **seaborn**: Data visualization.

## Key Observations

1. **Outliers**:
   - GENG Chovy, GENG Peyz, T1 Keria, T1 Gumayusi, and LNG Scout had a KDA greater than 7.4.
   - DK Moham and G2 Mikyx had high average death numbers, explained by their role as supports.

2. **Role-based Analysis**:
   - Early game metrics strongly impact win rate for Top and Mid players.
   - ADCs show the lowest correlation between early game metrics and win rate.

## Reproducing the Analysis

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/league-worlds-2024-analysis.git
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook to explore the analysis:
   ```bash
   jupyter notebook worlds_2024.ipynb
   ```

## Visualizations

Several visualizations were created, including:
- Scatter plots to explore correlations between KDA, CS, and GPM.
- Heatmaps for role-based correlations between metrics.
- Bar plots comparing early game performance with Flash keybind preferences.

---

## Future Improvements

- Incorporate additional metrics like champion picks and bans.
- Use advanced machine learning techniques to predict win rates.

