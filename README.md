# Netflix_movies_analysis
An analysis of a movie dataset exploring trends in movie popularity, vote averages, and genre distribution. The project includes data cleaning, categorizing vote averages, and visualizations using Python libraries like Pandas, Matplotlib, and Seaborn to provide insights into movie release patterns.

# Movie Analysis Project

This project involves an in-depth analysis of a movie dataset, focusing on trends related to movie popularity, vote averages, and genre distribution. The analysis is done using Python with libraries such as Pandas, Matplotlib, and Seaborn.

## Project Overview

The dataset used in this project contains various details about movies, including:

- **Release Date**
- **Title**
- **Overview**
- **Popularity**
- **Vote Count**
- **Vote Average**
- **Original Language**
- **Genre**

The analysis explores the following:

1. **Genre Distribution**: Identifying the most frequent genres of movies.
2. **Vote Average Categorization**: Categorizing movies based on vote averages.
3. **Movie Popularity**: Finding the movie with the highest and lowest popularity.
4. **Yearly Movie Trends**: Analyzing the number of movies released each year.

## Project Goals

- Clean and preprocess the dataset (handle missing values, outliers, etc.).
- Extract meaningful insights such as:
  - Most frequent genres.
  - The distribution of vote averages.
  - The movies with the highest and lowest popularity.
- Visualize the data using charts and graphs.

## Installation

To run the project locally, you need to have Python 3.x and the following libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install these dependencies using `pip`:

pip install pandas numpy matplotlib seaborn

# Usage
Clone the repository:

git clone https://github.com/adildafedar/Netflix_movies_analysis.git

cd movie-analysis

Place the dataset file (mymoviedb.csv) in the project folder.

Run the Jupyter Notebook or Python script to execute the analysis.

# Data Preprocessing
The Release_Date column was converted to datetime format and the year was extracted.

The Genre column was split by commas and exploded into individual rows.

The Vote_Average column was categorized into four categories: not_popular, below_avg, average, and popular.
# Visualizations
The project includes various visualizations to better understand the data, such as:

A bar chart showing the distribution of movie genres.

A count plot displaying the distribution of movies based on vote averages.

A histogram visualizing the number of movies released per year.
# Conclusion
Most Frequent Genre: Drama is the most frequent genre in the dataset.

Highest Votes in Vote Average: The dataset shows that 25.5% of movies have an average vote of "popular".

Most Popular Movie: "Spider-Man: No Way Home" has the highest popularity, with genres Action, Adventure, and Science Fiction.

Least Popular Movie: "The United States vs. Billie Holiday" and "Threads" have the lowest popularity.

# Acknowledgments

Thanks to the Python community for creating the libraries used in this analysis.

