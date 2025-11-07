# Cricket-Player-Comparison-and-Head-to-Head-Analysis
This project compares cricket players using data analytics and visualization techniques.  
It focuses on two detailed case studies built with real match data from ODIs and the IPL.

## Case Studies

### 1. Sachin Tendulkar vs Virat Kohli (ODIs)
This notebook analyses batting performance using `ODI_data.csv`.

Key points:
- Normalization applied to compare players across eras  
- Strike rate and scoring patterns explored through grouped data  
- Bar charts of runs by year and by player  
- Analysis of consistency and contribution to team totals  

### 2. AB de Villiers vs Jasprit Bumrah (IPL)
This notebook analyses IPL ball-by-ball data (`ipl_ball_by_ball_data.csv`).

Key points:
- Player vs player matchup analysis between ABD and Bumrah  
- Strike rate and runs distribution across different matchups  
- Scatter plots showing performance trends  
- Visual exploration of how Bumrah restricts top batters  

## 🎯 Objectives
- Compare player performances statistically and visually  
- Understand scoring consistency and situational dominance  
- Use Python data analysis to extract cricket insights  

## Tools and Libraries
- Python  
- Pandas and NumPy for data wrangling  
- Matplotlib and Seaborn for visualization  
- Jupyter Notebook for interactive analysis  

## Datasets
- **ODI_data.csv** – Player innings-level ODI data with runs, balls faced, boundaries and dates  
  https://drive.google.com/file/d/1bnV0nMSnh6539iaPPxH8ffEbllamgCVI/view?usp=sharing

- **ipl_ball_by_ball_data.csv** – IPL ball-by-ball data with batsman, bowler, runs, wickets and match info  
  https://drive.google.com/file/d/1m2mEOvVDinwEEpXOGAdjDrrSPAzF2ulj/view?usp=sharing

(Datasets are not included in the repository due to size limits. Place them in a local `data` folder before running the notebooks.)

## How to Use
1. Download both notebooks and datasets  
2. Place the datasets in a folder named `data`  
3. Open the notebooks in Jupyter  
4. Run all cells to generate visual comparisons  

## Insights
- Normalization enables fair comparison of players from different eras (Sachin vs Virat)  
- ABD’s strike rate patterns visualized against various IPL bowlers  
- Bumrah stands out as one of the toughest bowlers to score against in the IPL  
