\# MLB Physical Attributes vs Performance Analysis



\## Project Overview

This project analyzes the relationship between physical attributes (height, weight, sprint speed) and performance in Major League Baseball (MLB).



The goal is to determine whether player size impacts performance, or if skill-based metrics are more important predictors of success.



\---



\## Data Sources

\- Statcast (Sprint Speed, Exit Velocity)

\- MLB Stats API (Team records, player metadata)

\- FanGraphs (Batting statistics, WAR, wRC+)



All data is pulled programmatically from public sources.



\---



\## Methodology



\### 1. Player-Level Analysis

\- Merged physical and performance data

\- Built regression models to predict performance (WAR)

\- Compared baseline (physical only) vs expanded (skill + discipline)



\### 2. Temporal Analysis

\- Evaluated trends in height and sprint speed from 2019–2024

\- Compared how player size and athleticism have evolved over time



\### 3. Team-Level Analysis

\- Aggregated player attributes at the team level

\- Analyzed correlation between:

&#x20; - average team height

&#x20; - average team weight

&#x20; - average team sprint speed

&#x20; - team win percentage



\---



\## Key Findings



\- Physical size (height, weight) has little to no predictive power for performance

\- Skill-based metrics (barrel %, strikeout rate, walk rate) are much stronger predictors

\- Sprint speed is increasing over time, while height remains stable

\- At the team level, physical attributes show no meaningful correlation with winning



\---



\## Files in This Repository



\- `\*.ipynb` — main analysis notebooks

\- `\*.png` — generated charts and visualizations

\- `\*.csv` — processed datasets used for modeling



\---



\## How to Run



1\. Clone the repository

2\. Install dependencies:

&#x20;  ```bash

&#x20;  pip install pandas numpy matplotlib scikit-learn pybaseball requests

