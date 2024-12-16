# Data Analysis Report

# README.md

## Dataset Analysis and Visualization

### Overview
This document outlines the analysis of a dataset containing 2652 entries with 8 columns. The dataset appears to be related to media titles categorized by language, type, ratings (overall, quality, repeatability), and associated creators. 

### Data Description
The dataset has the following columns:
- **date**: The release date of the title (with some missing values).
- **language**: The language of the title.
- **type**: Type of media (e.g., movie, series).
- **title**: The title of the work.
- **by**: Creator or author of the work (with missing values).
- **overall**: Overall rating of the title (integer).
- **quality**: Quality rating of the title (integer).
- **repeatability**: Repeatability rating of the title (integer).

### Summary Statistics
#### Numeric Columns
- **Overall Ratings**: Range from 1 to 5, with a mean of approximately 3.05.
- **Quality Ratings**: Mean of approximately 3.21, with similar range; a bit higher than overall ratings.
- **Repeatability Ratings**: Lower mean of around 1.49 with a max of 3, indicating titles typically aren't highly rated for repeat viewing.

#### Categorical Columns
- **Dates**: A few dates have a notably higher number of entries, notably 21-May-06 (8 entries).
- **Languages**: Predominantly in English (1306 entries), followed by Tamil (718) and Telugu (338).
- **Types**: The majority of entries are movies (2211), with fewer entries for TV series, fiction, and non-fiction.
- **Titles**: "Kanda Naal Mudhal" has the highest number of entries (9), indicating it might be a popular choice or frequently referenced title.

### Insights & Trends
- The average ratings suggest general satisfaction with the titles, but the variability indicated by standard deviations points towards a mix of very high and low ratings.
- The high correlation between overall and quality ratings (approximately 0.83) implies that a title rated well in terms of quality likely received a good overall rating as well.
- The low repeatability mean and lower correlation with quality & overall ratings indicate potential difficulties in keeping audiences engaged long-term.

### Potential Outliers
- There are missing values in the `by` column (262 entries), which could affect analysis and trends regarding authorship.
- The `date` column has missing values too (99 entries); filling in these values could provide more insights into time trends.
- Investigating entries with unusually high or low ratings could reveal titles that significantly deviate from the expected ratings pattern.

### Visualization
To visualize the trends and insights found during the analysis, PNG files of the following charts are included:
1. **Summary Statistics of Numeric Columns**: Bar graph comparing the distributions of overall, quality, and repeatability ratings.
2. **Categorical Distribution**: Pie charts displaying the distribution of languages, types, and a bar graph showing the most popular titles.
3. **Correlation Heatmap**: A heatmap displaying the correlation matrix for numeric ratings.

### Files
- `summary_statistics.png`: A visual representation of summary statistics for the numeric columns.
- `categorical_distribution.png`: Categorical distribution of languages, types, and titles.
- `correlation_matrix.png`: Heatmap showing correlations between overall, quality, and repeatability ratings.

---

# Generated Visualizations

### 1. Summary Statistics of Numeric Columns
![summary_statistics](summary_statistics.png)

### 2. Categorical Distribution
![categorical_distribution](categorical_distribution.png)

### 3. Correlation Heatmap
![correlation_matrix](correlation_matrix.png)

---

This analysis provides insights into trends in media titles, including ratings and categorical breakdowns, highlighting areas for potential focus such as missing data remediation and detailed outlier investigation.
