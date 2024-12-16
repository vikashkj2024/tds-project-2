# Data Analysis Report

# README.md

## Dataset Analysis Report

### Overview
This document outlines the analysis conducted on a dataset comprising 2,652 entries across 8 columns. The dataset contains various attributes including date, language, type, title, and ratings (overall, quality, repeatability).

### Dataset Columns
- **date**: The date of entry (non-null entries: 2553).
- **language**: The language in which the content is available (all entries present).
- **type**: The type of content (e.g., movie, TV series, etc.) (all entries present).
- **title**: The title of the content (all entries present).
- **by**: The creator or author (non-null entries: 2390).
- **overall**: Overall rating (integer).
- **quality**: Quality rating (integer).
- **repeatability**: Repeatability rating (integer).

### Summary Statistics
- **Overall Ratings**: Mean = 3.05, Std. Dev = 0.76, Range = [1, 5]
- **Quality Ratings**: Mean = 3.21, Std. Dev = 0.80, Range = [1, 5]
- **Repeatability Ratings**: Mean = 1.49, Std. Dev = 0.60, Range = [1, 3]

### Categorical Insights
- **Dates** with the highest number of entries are:
  - 21-May-06: 8
  - 20-May-06: 7
- **Languages**:
  - English (1306 entries), Tamil (718), Telugu (338), Hindi (251).
- **Content Types**:
  - Movie: 2211
  - Fiction: 196
  - TV series: 112

### Missing Values
- Missing values in `date`: 99 entries.
- Missing values in `by`: 262 entries.

### Correlation Analysis
- Strong positive correlation between `overall` and `quality` (0.83).
- Moderate correlation between `overall` and `repeatability` (0.51).

### Insights
1. **Language Popularity**: English is the dominant language in the dataset, followed by Tamil and Telugu.
2. **Content Type Distribution**: The dataset is heavily skewed towards movies, suggesting that this is the most common type of content represented.
3. **Quality Ratings**: The overall ratings are generally positive, indicating that users predominantly view the contents favorably.
4. **Creator Information**: A notable number of entries are credited to well-known figures; however, there is a significant number of missing data regarding authors.
   
### Trends
- There is consistent content available, especially in English.
- There seems to be a trend towards higher quality and overall ratings over time but requires visual representation for deeper insights.

### Potential Outliers
- There are some titles that received disproportionate attention (e.g., "Kanda Naal Mudhal" with 9 entries) but may not reflect the general population of the ratings.

### Visualization
Various charts and plots have been generated to visualize the trends, distributions, and correlations identified during the analysis. These visualizations are saved as PNG files and can provide a clearer understanding of the data structure and trends.

### Files Included
- `overall_quality_correlation.png`: Correlation between overall and quality ratings.
- `language_distribution.png`: Distribution of entries across different languages.
- `content_type_distribution.png`: Breakdown of the types of content in the dataset.
- `ratings_distributions.png`: Distribution of overall, quality, and repeatability ratings.

---

# Visualization Files

1. **overall_quality_correlation.png**

![Overall Quality Correlation](overall_quality_correlation.png)

2. **language_distribution.png**

![Language Distribution](language_distribution.png)

3. **content_type_distribution.png**

![Content Type Distribution](content_type_distribution.png)

4. **ratings_distributions.png**

![Ratings Distributions](ratings_distributions.png)

---

This document serves to encapsulate the findings from the dataset analysis and highlights key areas for further exploration and potential study. The visualizations help to reinforce the insights derived from the data, aiding in a clear understanding of the dataset's behavior and characteristics.