# Movie-Analysis

A capstone project investigating the relationship between language used in movie subtitles and IMDB ratings. This project aims to build a predictive model and identify linguistic factors that contribute to highly-rated films.

## Project Goals

1. **Prediction:** Develop a model to predict a movie's potential IMDB rating based on linguistic features extracted from its subtitles.
2. **Linguistic Insights:** Uncover words, phrases, sentiment trends, and other language patterns that are strongly associated with positive audience reception.

## Dataset

* **Source:** OpenSubtitles.org, IMDb database (<https://datasets.imdbws.com/>)
* **Features:**
  * Movie title
  * IMDB Rating
  * Box office data
  * Subtitles (segmented into smaller chunks for analysis)
  * Linguistic features derived from subtitles (word frequencies, sentiment scores, complexity metrics, etc.)

## Methodology

1. **Data Acquisition and Preprocessing:**
    * Retrieve movie subtitles from OpenSubtitles.
    * Collect movie metadata (rating, box office) from IMDb.
    * Clean and normalize subtitle text.
    * Match subtitle files to corresponding movie entries.
2. **Feature Engineering:**
    * Calculate linguistic features for subtitle segments.
    * Explore aggregating features at the movie level.
3. **Modeling:**
    * Experiment with regression models to predict IMDB ratings.
    * Consider time-series analysis of linguistic features over a movie's duration.
4. **Evaluation:**
    * Employ suitable metrics (e.g., accuracy, mean squared error).
    * Implement cross-validation techniques for robustness.
5. **Visualization:**
    * Word clouds to compare word usage between high- and low-rated movies.
    * Sentiment analysis plots over movie timelines.
    * Correlation heatmaps to visualize relationships between linguistic features and ratings.

## Tools and Technologies

* **Python**
* **Pandas, NumPy**
* **NLTK, spaCy**
* **Scikit-learn**
* **Matplotlib, Seaborn (or Plotly/Dash)**
* **Beautiful Soup**

## Project Status

* **In progress**
