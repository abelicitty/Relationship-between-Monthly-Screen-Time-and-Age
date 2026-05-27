# Relationship-between-Monthly-Screen-Time-and-Age
# Correlation Analysis: Human-Computer Interaction & System Efficiency

This repository contains an exploratory data analysis (EDA) project centered on statistical correlation modeling. The objective is to investigate potential relationships between user demographics, digital behaviors, computer proficiency, and system efficiency metrics using Pearson correlation coefficients and linear regression visualizations.

## Project Overview
In human-computer interaction (HCI), understanding how user traits affect or relate to system productivity is crucial. This project leverages Python data science libraries to compute exact correlation statistics and generate linear regression trends across multiple variables, helping to confirm or debunk intuitive hypotheses about screen time, age, and technological competence.

## Dataset Profile
The includes the following features:
- **Age**: The chronological age of the participant.
- **Years_Using_PC**: User experience level with personal computers.
- **Monthly_Screen_Time_Hours**: Total duration spent on screens per month.
- **Tech_Familiarity_Score**: A metric indicating the user's self-assessed or tested comfort level with technology.
- **System_Efficiency**: A performance output or productivity metric.

## Statistical Analysis & Findings

The project evaluates linear relationships by calculating the Pearson correlation coefficient. The results reveal mostly weak or negligible linear relationships among the tested dimensions:

1. **Years Using PC vs. Tech Familiarity Score**
   - **Correlation Coefficient ($r$):** $-0.0119$
   - **Insight:** There is a negligible negative correlation, suggesting that a higher number of years using a PC does not inherently imply a higher technical familiarity score within this dataset.

2. **Age vs. System Efficiency**
   - **Correlation Coefficient ($r$):** $0.1370$
   - **Insight:** A very weak positive relationship exists, indicating that age does not heavily degrade or improve system efficiency metrics.

3. **Monthly Screen Time (Hours) vs. System Efficiency**
   - **Correlation Coefficient ($r$):** $0.0156$
   - **Insight:** Practically no linear correlation exists between monthly screen hours and overall system efficiency.

## Visualizations Included
The script builds two levels of diagnostic charts for each variable pair using `matplotlib` and `seaborn`:
- **Scatter Plots:** To observe individual data distribution and density.
- **Linear Regression Plots (`sns.regplot`):** Overlaying a line of best fit accompanied by a 95% confidence interval band to visually capture the trend line slopes.

## Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** `pandas`
- **Data Visualization:** `matplotlib`, `seaborn`
