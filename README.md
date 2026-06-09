# Netflix Movie Data Analysis

# Project Overview

This project analyzes a movie dataset using Python to discover trends in genres, popularity, voting patterns, and movie release years. The goal is to transform raw movie data into meaningful insights through data cleaning, exploratory data analysis (EDA), and data visualization.

# Objectives

- Understand the structure of the movie dataset.
- Clean and prepare data for analysis.
- Explore genre distribution and popularity trends.
- Analyze voting patterns across movies.
- Identify the most and least popular movies.
- Determine movie release trends over the years.

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

# Dataset Information

The dataset contains movie-related information including:

- Title
- Genre
- Popularity
- Vote Count
- Vote Average
- Release Date

Dataset Size:

- Rows: 9,827
- Columns: 9

# Data Preprocessing

The following steps were performed:

- Checked for missing values.
- Removed duplicate records.
- Converted Release Date to datetime format.
- Extracted release year from Release Date.
- Removed unnecessary columns.
- Categorized vote averages into groups.
- Split multiple genres into separate values for analysis.


#  Exploratory Data Analysis

The following questions were explored:

1. What is the most frequent genre?

Drama was found to be the most common genre in the dataset.

2. Which genre receives the highest votes?

Movies classified as popular received the highest number of votes, with Drama leading among highly-rated genres.

3. Which movie has the highest popularity?

Spider-Man: No Way Home was identified as the most popular movie in the dataset.

4. Which movie has the lowest popularity?

The United States, Thread was identified as the least popular movie in the dataset.

5. Which year has the highest number of movie releases?

The year 2020 recorded the highest number of movie releases.


# Visualizations

The project includes visualizations such as:

- Genre Distribution
- Vote Distribution
- Popularity Analysis
- Movie Release Year Distribution


# Key Findings

- Drama is the most frequent genre.
- Popular-rated movies dominate the dataset.
- Spider-Man: No Way Home has the highest popularity score.
- 2020 had the highest movie release count.
- Genre and popularity show noticeable patterns in audience preferences.


# Future Improvements

- Build an interactive Power BI dashboard.
- Create a movie recommendation system.
- Perform advanced statistical analysis.
- Deploy the project as a web application.


# Project Structure

Netflix-Movie-Data-Analysis/
│
├── Movie_Data_Analysis_Netflix.ipynb
├── mymoviedb.csv
├── README.md
└── requirements.txt


# Author

Bhishm

Aspiring Data Analyst passionate about transforming data into actionable insights using Python, SQL, Excel, and Power BI.

