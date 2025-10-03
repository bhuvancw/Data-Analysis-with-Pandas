Disney+ Shows and Movies Analysis

This project explores and analyzes Disney+ shows and movies dataset using Python.
The analysis focuses on data cleaning, exploratory data analysis (EDA), visualizations, and insights into trends, ratings, and correlations.

📂 Dataset

The dataset used: disney_plus_shows.csv

Contains metadata of Disney+ movies and shows.

Includes attributes like:

title, plot, genre, director, runtime, released_at, imdb_rating, imdb_votes, awards, country, etc.

🔧 Tools & Libraries

Python

Pandas / NumPy → Data cleaning & manipulation

Matplotlib / Seaborn → Visualizations

WordCloud → Text visualization for plots and genres

📊 Key Analysis & Visualizations

✔ Data Cleaning & Imputation

Handled missing values using median/mode imputation.

Filled categorical nulls with defaults like "Unknown" or "Not available".

✔ Exploratory Data Analysis (EDA)

Trend of releases over the years.

Top genres and directors.

Distribution of IMDb ratings.

Country-wise content production.

✔ Visualizations

📈 Line plot: Releases over time.

📊 Boxplot: IMDb ratings of Movies vs. TV Shows.

🔗 Correlation heatmap: Runtime, IMDb Rating, and IMDb Votes.

🏆 Awards vs IMDb Rating comparison.

☁ WordCloud: Most common words in plots and genres.

🔴 Scatterplot: Runtime vs IMDb Ratings (Are longer movies better rated?).

📌 Insights

The USA dominates production, followed by the UK and Canada.

Most movies cluster between 5–8 IMDb rating, with few extremes.

Longer runtime doesn’t always mean better ratings — correlation is weak.

Award-winning movies tend to have slightly higher ratings.

Comedy, Drama, and Family are among the most frequent genres.
