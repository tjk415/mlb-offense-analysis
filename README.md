# MLB Offense to Winning Analysis: What Offensive Stats Actually Win Games?
**Author:** Thomas Kirvin

Analyzed 300 MLB team-seasons (2016–2025) to identify which 
offensive statistics best predict winning percentage.

## Key Findings
- OBP predicts wins far better than batting average
- wRC+ is the single strongest predictor of team success
- Strikeouts are surprisingly weak as a negative indicator
- Offense does not tell the full story. Pitching and defense are also important factors.

## Tools
Python, pandas, NumPy, matplotlib, seaborn

## Data Sources
- **Batting data:** Team batting statistics from 
  [FanGraphs](https://www.fangraphs.com/leaders/major-league) 
  (2016–2025, team-level)
- **Standings data:** Team win-loss records from 
  [Baseball Reference](https://www.baseball-reference.com/leagues/majors/) 
  (2016–2025)

Both datasets were manually compiled into Google Sheets and 
loaded into Google Colab for analysis.
