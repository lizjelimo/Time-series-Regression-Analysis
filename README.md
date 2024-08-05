# Time-series-Regression-Analysis
# Project Title: Comprehensive Sales Data Analysis for Strategic Business Decisions

## Project Overview

This project explores sales data to identify key patterns and trends. By analyzing null values, conducting univariate analysis, and performing hypothesis testing, we aim to uncover insights that can guide strategic business decisions.

---

## Table of Contents

1. [Analysis of Null Values](#analysis-of-null-values)
2. [Univariate Analysis](#univariate-analysis)
3. [Hypothesis Testing using T-Test](#hypothesis-testing-using-t-test)
4. [Analytical Questions](#analytical-questions)
5. [Model Evaluation Metrics](#model-evaluation-metrics)
6. [Conclusion](#conclusion)

---

## Analysis of Null Values

Detailed examination of null values in the dataset to ensure data integrity and appropriate handling strategies.

- *Type_x, Locale, Locale Name, Description, Transferred*:
  - *Null Count*: 2,551,824
  - *Action*: Fill with 'No event' indicating the absence of a holiday/event.

- *dcoilwtico* (Oil Prices):
  - *Null Count*: 955,152
  - *Action*: Use interpolation or forward/backward fill to address missing values.

- *Transactions*:
  - *Null Count*: 249,117
  - *Action*: Fill zeros assuming no transactions occurred on those dates.

---

## Univariate Analysis

Analysis of individual variables to understand their distribution and impact.

- *Sales*: Range from low to exceptionally high, indicative of seasonal/promotional impacts.
- *Transactions*: Vary significantly, likely reflecting fluctuations in customer traffic.
- *Oil Prices (dcoilwtico)*: Influence on consumer behavior and economic conditions due to price fluctuations.

---

## Hypothesis Testing using T-Test

Evaluating the impact of promotions on sales through statistical hypothesis testing.

- *Null Hypothesis (H0)*: No impact of promotions on sales.
- *Alternative Hypothesis (H1)*: Significant impact of promotions on sales.

---

## Analytical Questions

Insights derived from specific analytical queries:

### Question 1: Impact of Weekends on Transactions
- *Analysis*: Comparing transaction volumes on weekends vs. weekdays.
- *Findings*: Significant increase in transactions during weekends.

### Question 2: Effect of New Product Introductions
- *Analysis*: Sales before and after new product launches.
- *Findings*: Positive impact on sales, suggesting successful product introductions.

---

## Model Evaluation Metrics

Comparison of various models to predict sales:

- *MAE (Mean Absolute Error)*: Measures average magnitude of errors in predictions.
- *MSE (Mean Squared Error)*: Punishes larger errors more severely.
- *RMSE (Root Mean Squared Error)*: Error metric in the same units as the sales data.
- *RMSLE (Root Mean Squared Logarithmic Error)*: Focuses on the ratio of predicted to actual values, penalizing underestimations more than overestimations.

---

## Conclusion

This comprehensive analysis provides insights into the factors influencing sales, guiding strategic decisions to optimize business performance.