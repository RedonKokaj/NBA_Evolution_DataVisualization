# NBA Game Evolution: From Physical Giants to the Era of Shooters

This repository contains a Jupyter notebook (`nba_evolution_datavis.ipynb`) that graphically illustrates the transformation of NBA basketball through data. It highlights the significant shift from the physical dominance characteristic of the 1980s and 1990s to the modern, technical, and perimeter-oriented game.

## Analysis Overview

The notebook analyzes the NBA's stylistic evolution from 1980 to today, focusing on the impact and increasing prevalence of the three-point shot since its introduction in the 1979-80 season. The analysis confirms the hypothesis that NBA basketball has transformed from a physical, 2-point dominated game to a technical, perimeter-oriented game.

## Key Conclusions from the Analysis

The main conclusions drawn from this analysis are as follows:

1.  **Quantitative Transformation**:
    * The average number of 3-point attempts per team per game increased significantly from 227.4 to 3081.8.
    * The share of 3-point shots rose from 3.1% to 42.1% of all field goal attempts.

2.  **Strategic Shift**:
    * During the "Physical Era" (1980–1999), the average 3-point attempts stood at 620.0.
    * In the "Technical Era" (2010–2023), this average surged to 2197.6 attempts.
    * This represents a 254% increase in 3-point attempts between these eras.

3.  **Stephen Curry's Influence**:
    * In the "Pre-Curry" era (1980–2009), the average 3-point attempts were 820.7.
    * During the "Curry Era" (2010–2023), the average increased to 2197.6 attempts.
    * This indicates a 168% increase in 3-point attempts during Stephen Curry's influential period.

4.  **Impact on Efficiency**:
    * There is a significant positive correlation (0.657) between the share of 3-point shots and overall game efficiency.
    * Efficiency improved by 6.3% from 1980 to 2020, suggesting that modern basketball is more efficient thanks to the 3-point shot.

5.  **Future Trends**:
    * The revolution in NBA basketball continues, albeit with more stable growth rates.
    * The current NBA game is entirely transformed compared to the 1980s.

## How to Run the Notebook

To run the `nba_evolution_datavis.ipynb` notebook:

1.  Ensure you have Jupyter Notebook or JupyterLab installed.
2.  Install the necessary Python libraries, including `pandas`, `numpy`, `matplotlib.pyplot`, `plotly.graph_objects`, and `kagglehub`.
3.  The notebook downloads the dataset "sumitrodatta/nba-aba-baa-stats" from Kaggle using `kagglehub`. Make sure you have an internet connection and the necessary Kaggle API configuration if required for `kagglehub` to download datasets.
4.  Execute the cells sequentially to reproduce the analysis and visualizations.

The notebook cleans the data by filtering NBA data from 1980 onwards (when the 3-point shot was introduced) and removing missing values in key columns. It also categorizes data into decades for analysis.
