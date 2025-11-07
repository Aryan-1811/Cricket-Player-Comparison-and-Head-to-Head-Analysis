# Cricket-Player-Comparison-and-Head-to-Head-Analysis
A data-driven look at player performance using ODI and IPL delivery-level data.  
This repo contains two focused case studies:
1) **Sachin Tendulkar vs Virat Kohli** - ODI batting comparison with normalization, strike rate, conversion to 50s/100s, and team contribution.
2) **AB de Villiers vs Jasprit Bumrah** - IPL batter–bowler matchup using ball-by-ball outcomes and visual exploration.

---

## Notebooks
- `Case_Study_Virat_vs_Sachin_.ipynb`  
  Uses `ODI_data.csv`. Includes:
  - Normalization across eras/contexts
  - Strike rate and scoring frequency
  - Matches per 50 and per 100
  - Team contribution ratios
  - Visualizations summarizing consistency and impact

- `Case_Study_ABD_vs_Bumrah.ipynb`  
  Uses IPL ball-by-ball data. Includes:
  - Delivery-level filtering for ABD vs Bumrah
  - Scatter and summary plots (e.g., strike rate vs runs off bat)
  - Exploratory matchup insights

---

## Data
- `ODI_data.csv` - ODI records with columns such as player, runs, balls, minutes, fours, sixes, opposition, ground, date, country, not out, result.
- `ipl_ball_by_ball_data.csv` - IPL delivery-level data with match metadata, innings, ball index, batter, bowler, runs, extras, dismissals, etc.

---

## Methods and metrics
- **Normalization** to compare across eras and contexts
- **Strike rate** and **scoring frequency**
- **Conversion** to fifties and hundreds (matches per 50/100)
- **Team contribution** ratios
- **Delivery-level matchup** exploration for ABD vs Bumrah (runs off bat, dismissals, dot-ball pressure)
- **Visualizations** using Matplotlib for quick comparisons

---

## Environment
Install the core libraries:
```bash
pip install pandas numpy matplotlib jupyter
