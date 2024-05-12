# Data-Analysis-and-Visualization Capstone Project
# Movie Ratings Analysis

## Overview
This project analyzes movie ratings data to investigate whether there's a bias in how Fandango rates movies, particularly in comparison to other movie rating platforms. The analysis is based on data from two main sources: Fandango's own ratings and ratings from other popular platforms like Rotten Tomatoes, Metacritic, and IMDB.

The main goal of this analysis is to determine if Fandango's ratings tend to be higher than those of other platforms and if there's a noticeable discrepancy between the ratings displayed to users and the actual ratings from user reviews.

## Data Sources
The analysis uses two main datasets:
- **fandango_scrape.csv**: Contains movie ratings data scraped from Fandango's website, including the number of stars, the actual rating, and the number of votes.
- **all_sites_scores.csv**: Contains aggregated movie ratings from multiple platforms including Rotten Tomatoes, Metacritic, and IMDB.

## Analysis Steps
1. **Exploratory Data Analysis (EDA)**:
   - Explore the Fandango ratings dataset to understand its structure and characteristics.
   - Investigate the relationship between movie ratings and the number of votes.
   - Calculate correlations between different rating metrics.

2. **Comparison with Other Sites**:
   - Compare Fandango ratings with ratings from Rotten Tomatoes, Metacritic, and IMDB.
   - Analyze differences between critics' ratings and user ratings for each platform.
   - Identify movies with the largest differences in ratings between critics and users.

3. **Normalization and Comparison**:
   - Normalize ratings from different platforms to facilitate comparison.
   - Visualize the distribution of normalized ratings.
   - Compare Fandango's ratings with normalized ratings from other platforms.

4. **Identifying Worst Movies**:
   - Determine the top 10 lowest-rated movies based on Rotten Tomatoes critics' ratings.
   - Examine the normalized scores across all platforms for these movies.

## Results
- Fandango's ratings tend to be higher than those of other platforms.
- There's a discrepancy between Fandango's displayed ratings and the actual ratings from user reviews.
- Some movies have significantly different ratings between critics and users across different platforms.

## Files
- `fandango_scrape.csv`: Dataset containing Fandango movie ratings.
- `all_sites_scores.csv`: Dataset containing movie ratings from Rotten Tomatoes, Metacritic, and IMDB.
- `00-Capstone-Project.ipynb`: Jupyter Notebook containing the Python code for the analysis.
- `README.md`: This file.

## Dependencies
The analysis was conducted using the following Python libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Usage
To replicate the analysis, you can run the provided Jupyter Notebook `00-Capstone-Project.ipynb` and ensure you have the necessary datasets (`fandango_scrape.csv` and `all_sites_scores.csv`) available in your working directory.

## Author
Nikhil Khot


