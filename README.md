# The Rolling Stones — Spotify Data Analysis

## Project Overview

This project analyzes Spotify data for albums by **The Rolling Stones**. The dataset contains song information, album details, Spotify identifiers, audio features, track duration, and popularity scores.

The goal is to clean and prepare the data, explore patterns in the songs, investigate factors related to popularity, apply dimensionality reduction, and use clustering to identify groups of songs with similar characteristics.

## Dataset Description

Each song has a unique Spotify ID. The dataset includes the following fields:

| Column | Description |
|---|---|
| `name` | Name of the song |
| `album` | Album containing the song |
| `release_date` | Album release date |
| `track_number` | Order of the song on the album |
| `id` | Spotify ID for the song |
| `uri` | Spotify URI for the song |
| `acousticness` | Confidence measure indicating how acoustic a track is, from 0 to 1 |
| `danceability` | How suitable a track is for dancing, from 0 to 1 |
| `energy` | Perceived intensity and activity of a track, from 0 to 1 |
| `instrumentalness` | Likelihood that a track contains no vocals |
| `liveness` | Likelihood that a track was performed live |
| `loudness` | Average loudness of the track, measured in decibels (dB) |
| `speechiness` | Measure of the presence of spoken words in a track |
| `tempo` | Estimated track tempo, measured in beats per minute (BPM) |
| `valence` | Measure of the musical positivity conveyed by a track, from 0 to 1 |
| `popularity` | Spotify popularity score, from 0 to 100 |
| `duration_ms` | Track duration in milliseconds |

## Project Objectives

### 1. Initial Data Inspection and Cleaning

- [x] Inspect the dataset and understand its structure.
- [x] Identify and handle duplicate records.
- [x] Check for missing or null values.
- [x] Identify irrelevant entries and potential outliers.
- [x] Check for incorrect or inconsistent values and correct them where appropriate.

### 2. Data Preparation

- [x] Refine the dataset based on the findings from the initial inspection.
- [x] Prepare the relevant features for exploratory analysis and machine learning.
- [x] Document any columns removed, transformed, or retained and explain why.

### 3. Exploratory Data Analysis (EDA) and Feature Engineering

- [x] Use suitable visualizations to identify two albums that could be recommended based on the number of popular songs.
- [x] Explore song audio features and identify meaningful patterns.
- [x] Investigate the relationship between song popularity and other features.
- [x] Examine how these relationships may vary across albums or release periods.
- [x] Apply feature engineering where useful and explain the decisions.
- [x] Apply dimensionality reduction and discuss its purpose, impact, and observations.

### 4. Cluster Analysis

- [x] Determine a suitable number of clusters using appropriate evaluation methods.
- [x] Apply suitable clustering algorithms to the prepared song features.
- [x] Describe and interpret each cluster using the features that distinguish it.
- [x] Summarize the findings and explain what the clusters reveal about the songs.

## Tools and Technologies

The tools used in this project can be documented here as the analysis develops. For example:

- Python
- pandas and NumPy for data preparation
- Matplotlib and Seaborn for visualizations
- scikit-learn for preprocessing, dimensionality reduction, and clustering
- Jupyter Notebook for analysis

## Key Findings

Add your final findings here after completing the analysis. Include:

- The two recommended albums and the evidence supporting the recommendation.
- Important patterns found in the audio features.
- The main observations about popularity and its relationship with other features.
- The effect of dimensionality reduction on the data.
- The selected clustering approach, number of clusters, and interpretation of each cluster.

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the analysis notebook in Jupyter Notebook or JupyterLab.
4. Update the dataset path if needed.
5. Run the notebook cells in order.

Example installation command (adjust to the libraries actually used):

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```