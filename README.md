# Global Suicide Rates & Socioeconomic Factors

## Project Overview

This project analyzes global suicide rates from 2000–2021 across 185 countries. The goal is to identify trends over time, compare suicide rates by sex and country, and examine the relationship between suicide rates and GDP per capita.

## Research Questions

1. How have suicide rates changed from 2000 to 2021?
2. How do suicide rates differ between males and females?
3. Which countries have the highest and lowest average suicide rates?
4. Is there a relationship between GDP per capita and suicide rates?

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Kaggle Notebooks
- Jupyter Notebook

## Analysis

### Global Trend

The population-weighted global suicide rate decreased from approximately 12.51 per 100,000 in 2000 to 9.13 per 100,000 in 2021, representing a decrease of approximately 27%.

### Suicide Rates by Sex

The reported male suicide rate was higher than the female rate in the dataset. The population-weighted rates were approximately 14.19 per 100,000 for males and 7.06 per 100,000 for females.

### Country Comparison

Lithuania had the highest average reported suicide rate among the countries analyzed at approximately 36.79 per 100,000, followed by the Russian Federation at approximately 36.57.

### GDP Analysis

The Pearson correlation between GDP per capita and reported suicide rate was approximately 0.15, indicating a weak positive linear relationship in this dataset.

## Limitations

- Some observations were missing GDP information and were excluded from the GDP analysis.
- The analysis was restricted to the `all_ages` category because the dataset contains overlapping age brackets.
- Differences in reporting practices and data availability may affect comparisons between countries.
- Correlation does not establish causation.

## Dataset

Global Suicide Rates and Socioeconomic Indicators

The analysis was conducted using a Kaggle Notebook and the associated dataset.
