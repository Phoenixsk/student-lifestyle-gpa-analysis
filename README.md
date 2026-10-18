# Student Lifestyle & Academic Performance Analysis
**Course Project:** UW INFO 201 (Foundational Skills for Data Science)  
**Authors:** Phoenix John Khamvongsa, Veer Shukla, Alvin Bui

## 📊 Project Overview
This project examines how non-academic lifestyle factors—specifically sleep quality, physical habits, and mental health tracking vectors—influence undergraduate academic performance (GPA). Utilizing data aggregated from over 9,000 self-reported student surveys on Kaggle, our team cleaned, normalized, and engineered feature indexes to uncover behavioral optimizations.

## 🛠️ Tech Stack & Methodology
* **Language & Environment:** R, RStudio
* **Libraries:** Tidyverse (`dplyr`, `ggplot2`, `read_delim`, `bind_rows`)
* **Statistical Methods:** LOESS Regression Curve-Fitting, Linear Regression Modeling (`lm`), Feature Scaling & Data Normalization

## 💡 Key Analytical Insights
* **Sleep Thresholds:** Peak academic performance was isolated precisely at 8 hours of sleep per day. Both insufficient and excessive sleep windows showed strong negative correlations with overall GPA due to reduced active study windows.
* **Stress Optimization:** Rather than a direct negative linear relationship, regression curves revealed a parabolic distribution. An optimal stress index score of **2.5** correlated with the highest student performance, indicating that moderate academic pressure acts as a positive driver.
* **Physical Habits:** Daily physical exercise demonstrated the strongest positive linear correlation with higher GPAs. Conversely, extensive social interaction hours showed a slight negative correlation, potentially indicating a tradeoff with structured study time.

## 📂 Repository Contents
* `Final-Project-with-code-chunk-3.html`: The fully rendered interactive data report, including charts and statistical visualizations.
* `Final Project with code chunk.Rmd`: The raw R Markdown source code pipelines detailing our data wrangling, cleaning steps, and modeling configurations.
