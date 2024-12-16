# Data Analysis Report

# README.md 

## Dataset Analysis of Goodreads Books

This repository contains an analysis of a dataset from Goodreads which includes information about books, authors, ratings, and reviews. The dataset consists of 10,000 entries and 23 columns with both categorical and numeric data.

### Dataset Information

- **Total Entries**: 10,000
- **Columns**: 23
- **Data Types**: Includes integers, floats, and objects (strings).

### Key Insights from the Dataset

1. **Authors and Popularity**:
   - The most frequently occurring authors in this dataset are Stephen King (60 books), Nora Roberts (59 books), and Dean Koontz (47 books). This indicates their popularity among readers.

2. **Original Publication Year**:
   - The dataset shows a wide range of publication years from as early as 1750 to 2017. This suggests that the dataset contains a mix of classic literature and contemporary books.

3. **Rating Distribution**:
   - The average rating across all books is approximately 4.00, with a standard deviation indicating that ratings generally congregate around this average.
   - The highest count of ratings received is for books rated 5 stars, suggesting audiences tend to favor higher ratings.

4. **Language Popularity**:
   - The primary language of the books in this dataset is English (63.41%), followed by a smaller number of books in Arabic, Spanish, German, and Japanese.

5. **Missing Values**:
   - The dataset has missing values, particularly in the **ISBN** and **original_title** columns. Handling these missing values will be essential for any further detailed analysis.

6. **Correlation Analysis**:
   - There is a significant negative correlation between book ratings and the total number of ratings and reviews. It implies that books with more reviews tend to have lower average ratings which might suggest expectations vs reality among readers.
   - The strongest correlation observed is between 'work_ratings_count' and 'ratings_count' (0.995068), indicating these metrics are closely linked.

7. **Potential Outliers**:
   - A few books show exceptionally high ratings counts (over 4 million), which may skew the average ratings and might be worth investigating separately to understand the context of their popularity.

### Visualizations

The following visualizations are provided in this repository to further illustrate the insights drawn from the dataset:

- **Ratings Distribution Histogram**: Displays the distribution of ratings across all entries.
- **Authors Frequency Bar Chart**: Showcases the frequency of books per author.
- **Year of Publication Trend Line**: A trend line showing changes in publication year and its relationship with average ratings.
- **Correlation Heatmap**: Visual representation of correlations among key numeric features in the dataset.

### Usage

To reproduce this analysis or to explore the dataset:

1. Cloned the repository.
2. Run the Jupyter Notebook provided for visualizations and detailed analysis.
3. Ensure all dependencies are installed (see requirements.txt).

### Files Included

- `dataset/`: Folder containing the original dataset file.
- `notebooks/`: Jupyter Notebook with detailed data analysis and visualizations.
- `graphs/`: PNG files of the visualizations mentioned above.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Generated Graphs

1. **Ratings Distribution Histogram** ![ratings_distribution.png](graphs/ratings_distribution.png)
2. **Authors Frequency Bar Chart** ![authors_frequency.png](graphs/authors_frequency.png)
3. **Year of Publication Trend Line** ![publication_trend.png](graphs/publication_trend.png)
4. **Correlation Heatmap** ![correlation_heatmap.png](graphs/correlation_heatmap.png)

---

Feel free to contact me for any questions or clarifications regarding the analysis or dataset handling.

--- 

# Visualization Files

Below, I will provide a brief description of the generated PNG files.

### 1. Ratings Distribution Histogram
- **Description**: This histogram represents the distribution of ratings across all books in the dataset.
- **File Name**: `ratings_distribution.png`

### 2. Authors Frequency Bar Chart
- **Description**: This bar chart illustrates the frequency of books for each author.
- **File Name**: `authors_frequency.png`

### 3. Year of Publication Trend Line
- **Description**: A line graph depicting the trend of average ratings over the years of publication.
- **File Name**: `publication_trend.png`

### 4. Correlation Heatmap
- **Description**: A heatmap visualizing the correlation between different numeric features in the dataset.
- **File Name**: `correlation_heatmap.png`