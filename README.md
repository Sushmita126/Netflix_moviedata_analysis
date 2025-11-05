# Netflix_moviedata_analysis
This project analyzes the iScale Netflix movie dataset to uncover insights about genres, popularity, and yearly trends.
The goal is to identify which genres are most frequent and popular, which movies have the highest and lowest popularity, and which year saw the most film production.
The project demonstrates the end-to-end data analysis workflow — from data cleaning and EDA in Python

Dataset Information
Source: iScale Netflix Movie Dataset
Rows: 9,827 (expanded to 25,552 after cleaning and exploding genres)
Columns: 9 → reduced to 6 (after removing unnecessary ones)
Key Features:
title
genre
popularity
vote_average
vote_count
release_year

Project Steps
1. Data Cleaning
Removed duplicate and missing values Converted release_date into release_year (integer) Dropped irrelevant columns (overview, original_language, etc.) Split multiple genres into individual rows using explode()
Categorized vote averages into popularity levels (not_popular, average, etc.)

2. Exploratory Data Analysis (EDA)
Analyzed frequency distribution of movie genresChecked popularity vs votes correlation Identified top and bottom performing movies Explored yearly trends in film productio

Created a summary report and presentation (Gamma) highlighting key insights
