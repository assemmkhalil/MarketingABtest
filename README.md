# A/B Test for Marketing Campaign

## Overview:
This project is focused on conducting a comprehensive analysis of a marketing campaign's effectiveness using statistical methods. The objective was to evaluate the A/B testing results and decide which marketing strategy works the best, with sales amount as the key metric to decide upon.

## About the Data:
[Data Source](https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test) <br>
A fast-food chain plans to add a new item to its menu. However, they are still undecided between three possible marketing campaigns for promoting the new product. In order to determine which promotion has the greatest effect on sales, the new item is introduced at locations in several randomly selected markets. A different promotion is used at each location, and the weekly sales of the new item are recorded for the first four weeks.

## Methodology:
1. Exploratory Data Analysis (EDA)
- Univariate EDA: Initial exploration of individual variables to understand their distributions and basic statistics.
- Bivariate EDA: Exploring relationships between pairs of variables to identify potential patterns or correlations.
2. Hypothesis Testing
- Testing normality using Shapiro-Wilk test: Check if the data follows a normal distribution.
- Testing homoscedasticity using Levene test: Assess if the variances of different groups are equal.
- Testing differences of means using Kruskal-Wallis test: Compare three or more independent groups that are not normally distributed.
- Post-Hoc analysis using Dunn’s test: Conducted after significant results from the Kruskal-Wallis test to identify specific group differences.

## Main Findings:
We can expect sales to increase more, in all markets, if we used promotion 1, promotion 3 or both, than if we used promotion 2.
