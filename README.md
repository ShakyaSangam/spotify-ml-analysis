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