# Google Play Store Apps – Statistical Analysis

## Overview

This project investigates the characteristics, user engagement and market distribution of Android applications using the Google Play Store Apps dataset sourced from Kaggle.

The analysis applies descriptive and inferential statistical methods to examine app ratings, reviews, installation counts, file sizes, application categories, monetisation types and content ratings. The findings provide insights into user satisfaction, app popularity and market distribution.

## Dataset

- **Source:** Kaggle – Google Play Store Apps
- **Original Dataset:** 10,842 records and 13 variables
- **Cleaned Dataset:** 7,019 records and 9 variables
- **App Categories:** 33

### Data Preprocessing

- Removed duplicate records.
- Removed missing and invalid values.
- Eliminated variables that were not relevant to the research objectives.
- Standardised application file sizes into megabytes (MB).
- Converted installation counts into numerical values.
- Identified variable types and measurement scales.

## Research Objectives

- Analyse the distribution of application ratings.
- Examine the relationship between user reviews and installation counts.
- Investigate differences in application file sizes across categories.
- Identify the most populated application categories.
- Compare free and paid application distributions and ratings.
- Analyse content ratings and target audience distributions.

## Technologies Used

| Technology | Purpose |
|---|---|
| R | Statistical programming and hypothesis testing |
| Microsoft Excel | Dataset preparation and storage |
| ggplot2 | Statistical data visualisation |
| dplyr | Data manipulation and aggregation |
| scales | Percentage formatting and visualisation |
| Kaggle | Dataset source |

## Statistical Methodology

### Descriptive Statistics

- Mean, median and quartiles
- Standard deviation and interquartile range
- Skewness and distribution analysis
- Frequency and percentage distributions
- Outlier identification

### Inferential Statistics

| Statistical Method | Application |
|---|---|
| One-way ANOVA | Compare app ratings, reviews and file sizes across categories |
| Welch's two-sample t-test | Compare average ratings between free and paid apps |
| Pearson correlation | Examine the relationship between log-transformed reviews and installs |
| Chi-square goodness-of-fit test | Examine app distribution across categories |
| Chi-square test of independence | Investigate associations between app category, app type and content rating |

### Data Visualisation

- Histograms
- Boxplots
- Scatterplots
- Bar charts
- Pie charts

## Key Findings

| Metric | Result |
|---|---|
| Mean app rating | 4.161 |
| Median app rating | 4.300 |
| Mean app size | 21.74 MB |
| Median app size | 13.00 MB |
| Free applications | 92.29% |
| Paid applications | 7.71% |
| Correlation between log-transformed reviews and installs | 0.950 |
| Most populated category | Family |
| Most common content rating | Everyone |

The statistical analysis reported the following findings:

- Average app ratings differ significantly across application categories.
- Paid applications have higher average ratings than free applications in the analysed dataset.
- Log-transformed reviews and installs demonstrate a strong positive correlation.
- Application file sizes and review counts differ significantly across categories.
- Free applications dominate the analysed dataset.
- App type and content rating distributions are associated with application categories.

## Business Implications

The findings provide insights for application developers, businesses and market analysts regarding:

- Application market competition
- User satisfaction and engagement
- Application monetisation strategies
- Product positioning
- File size considerations
- Target audience segmentation

## Individual Contributions – Yew Kai Qian

- Analysed dataset characteristics and variable classifications.
- Conducted inferential statistical analysis using R.
- Performed one-way ANOVA to evaluate differences across application categories.
- Conducted Welch's two-sample t-tests to compare free and paid application ratings.
- Performed Pearson correlation analysis to investigate the relationship between reviews and installs.
- Interpreted statistical outputs, p-values and hypothesis testing results.
- Contributed to the interpretation and conclusion of the statistical analysis.

## Repository Structure

| File | Description |
|---|---|
| `UCCM2433_Group_4_GooglePlayAppStore.xlsx` | Project dataset workbook |
| `Report.pdf` | Statistical analysis report, methodology, visualisations, findings and supporting R code |

## Project Documentation

Refer to the [Project Report](Report.pdf) for detailed documentation, including:

- Research objectives
- Data description and preprocessing
- Descriptive statistical analysis
- Inferential statistical analysis
- Statistical visualisations
- Hypothesis testing results
- Business implications
- Supporting R code
- Individual contributions

## Contributors

- Chin Wei Bin
- Liew Jia Min
- Yeap Chi Ling
- Yew Kai Qian

## Project Background

This project was developed collaboratively by four undergraduate students at Universiti Tunku Abdul Rahman (UTAR).

- **Course:** UCCM2433 – Fundamentals of Statistics
- **Trimester:** June 2025
- **Project Type:** Academic Group Project
- **Domain:** Statistical Analysis and Data Analytics

## Limitations

- The findings reflect the historical dataset rather than current Google Play Store market conditions.
- Installation counts represent reported installation thresholds rather than exact download totals.
- Correlation does not establish causation.
- Some chi-square tests produced approximation warnings due to low expected frequencies.
- Further assumption testing and post-hoc analysis could strengthen the statistical conclusions.
