# Pymaceuticals - Data Analysis

## Overview

The purpose of this project is to analyze the effects of various drug treatments on tumor growth in mice. By examining different drug regimens and their outcomes over time, the analysis provides insights into which treatments are most effective in reducing tumor size and which factors may correlate with tumor growth.

## Project Structure

- **Mouse Metadata**: Contains details about the mice used in the study, such as their IDs, sex, and age.
- **Study Results**: Includes data on the treatment regimens, timepoints, and tumor volume measurements for each mouse.
- **Data Processing and Analysis**: The code processes the mouse metadata and study results, cleaning and merging the data for analysis. It then generates summary statistics, visualizations (such as bar, pie, and box plots), and conducts statistical tests to evaluate the effectiveness of each drug regimen.

## Key Steps

1. **Data Cleaning**: Duplicate data for one mouse (ID: g989) was removed to ensure accuracy in the analysis.
2. **Statistical Analysis**: Summary statistics were calculated, including mean tumor volume, standard deviation, and standard error of the mean for each drug regimen.
3. **Visualization**: Various plots were created, including:
   - Bar plots showing the total observations for each drug regimen.
   - Pie charts displaying the gender distribution of the mice.
   - Box plots revealing tumor volume distributions and potential outliers.
   - Line and scatter plots analyzing tumor growth over time for individual mice and across the Capomulin regimen.

## Results

- **Capomulin** showed the lowest average tumor volume (40.68 mm³) among the treatments, indicating its effectiveness.
- A **strong positive correlation** (r = 0.95) was observed between mouse weight and tumor volume in the Capomulin regimen, suggesting that heavier mice tend to have larger tumors.
- **Infubinol** exhibited a potential outlier in its tumor data, while other regimens showed no outliers.

## Conclusion

This analysis provides valuable insights into how different drug treatments affect tumor growth. Capomulin appears to be the most effective treatment, while further exploration into the relationship between weight and tumor volume may offer additional insights into treatment efficacy.