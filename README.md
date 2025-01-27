# Netflix-Movie-Data-Analysis-EDA
This project involves performing exploratory data analysis (EDA) on a dataset containing information about Netflix movies and TV shows. The goal of this analysis is to uncover trends, patterns, and insights that can help understand Netflix’s content better, including the distribution of genres, release years, ratings, and other features.


## Overview:

The primary objective of this project is to perform EDA on a dataset containing information about Netflix movies and TV shows. We analyze:

- We have a `dataframe` consisting of 9827 rows and 9 columns.
- Our `dataset` looks a bit tidy with no NaNs nor duplicated values.
- `Release_date` column needs to be casted into datetime and to extract only the year value.
- `Overview`, `Original_language` and `Poster_URL` wouldn't be so useful during analysis, so we'll drop them.
- There is noticable outliers in `Popularity` column.
- `Vote_Average` better be better be categorized for proper analysis.
- `Genre` column has comma separated values and while spaces that needs to be handled and casted into category.

The goal is to uncover any hidden patterns, correlations, and trends within the data. This analysis can help gain a deeper understanding of the types of content available on Netflix and the distribution of certain features across the dataset.


## Dataset:

The dataset used in this project is sourced from Netflix Movies and TV Shows. The dataset includes details of movies and TV shows available on Netflix, such as:

- **Title**: The name of the movie or TV show.
- **Genre**: The genre(s) of the content.
- **Release Date**: The year in which the movie or TV show was released.
- **Rating/Popularity**: Viewer rating (IMDB, Rotten Tomatoes, etc.).
- **Duration**: Duration in minutes for movies and number of seasons for TV shows.
- **Language**: The language of the content.


## Required Libraries:

- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**


## Analysis:

In this section, we provide an overview of the types of analyses performed during the exploratory data analysis (EDA):

- **Data Cleaning**: Removing missing values, converting data types, handling duplicates, etc.

- **Univariate Analysis**: Exploring the distribution of individual features like release year, rating/popularity, and genre.

- **Visualizations**: Using libraries like Matplotlib and Seaborn to visualize key insights, trends, and distributions.


## Conclusions:

Based on the EDA, you will find insights such as:

- **What is the most frequent `Genre` in the dataset?**
- **What `Genre` has highest votes?**
- **What movie got the highest `Popularity` ? what's its `Genre`?**
- **What movie got the lowest `Popularity` ? what's its `Genre`?**
- **Which year has the most filmed movies?**


## Acknowledgments:

The data science and open-source community for developing libraries like Pandas, Matplotlib, and Seaborn.


-----------
Thank You.
