# International Mathematical Olympiad (IMO) Data Analysis: 2015–2024

This project analyzes **10 years of IMO data** to understand factors contributing to sustained national success in the competition. Using country- and individual-level datasets, we examine trends in team performance, contestant experience, and problem-specific scores. The analysis combines **data wrangling, visualization, and statistical insights** to uncover patterns that differentiate top-performing nations.

## Background

The International Mathematical Olympiad (IMO) is the most prestigious global mathematics competition for pre-university students. Each country fields a team of six students, and rankings are based on combined team scores. This project focuses on evaluating **how team experience and problem-specific performance influence country rankings**, with a particular focus on the top-performing countries over the 2015–2024 period.

## Sample Visualizations

### Ranking Trends of Top Countries (2015–2024)
![Ranking trends of top IMO countries](images/imo-country-rank-trends.png)

### Team Experience vs Ranking
![Experience vs ranking scatter plot](images/country-experience-vs-performance.png)

### Problem-Specific Performance
![Problem difficulty comparison](images/problem-scores-vs-rank.png)

## Key Features

- **Data Wrangling & Cleaning:**  
  - Processed country- and individual-level datasets.  
  - Handled missing values and removed unused columns (e.g., `p7`).  
  - Engineered features such as `total_score`, `cumulative_score`, and contestant experience.  
  - Designed the analysis workflow from raw datasets to insights on top-country performance, including how to identify evaluate the "top5" countries etc.

- **Exploratory Analysis & Visualization:**  
  - **Line Charts:** Tracked yearly ranking trends of top countries.  
  - **Scatter Plots:** Evaluated the effect of average team experience on rankings (no significant correlation found).  
  - **Comparative Bar Charts:** Analyzed problem-specific performance; identified hardest problems (P3 & P6) as key differentiators for top-ranked nations.

- **Statistical Insights:**  
  - Contestant experience alone does not predict national success.  
  - Mastery of the most challenging problems strongly correlates with higher country rankings (i.e the countries that score the highest for the toughest questions will likely rank higher) 

- **Collaboration & Reporting:**  
  - Developed as a team of 5 students.  
  - Shared responsibilities across data cleaning, visualization, analysis, and report synthesis.  
  - Delivered polished visualizations and a coherent report using R Markdown.


## Tech Stack & Skills

- **Languages & Tools:** R, R Markdown, dplyr, ggplot2, tidyverse  
- **Skills Demonstrated:** Data wrangling, feature engineering, statistical analysis, visualization, teamwork, and rmd report writing.

## Dataset

The dataset used in this project was curated by [Havisha Khurana](https://github.com/havishakhurana) for TidyTuesday. It contains information on IMO participants, including country, gender, and scores. The data can be accessed here:

- [IMO Data (TidyTuesday, 2024-09-24)](https://github.com/rfordatascience/tidytuesday/blob/main/data/2024/2024-09-24/readme.md)


