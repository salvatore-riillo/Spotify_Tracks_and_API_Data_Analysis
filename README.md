
# Spotify Data Analysis Project (Python)

## Overview
This project involves analyzing a dataset of music tracks to derive insights and patterns. The dataset initially exists in a `.db` format containing various metadata about music tracks. The primary objective is to explore this database using SQL, enrich it with additional information from the Spotify API, and then conduct a short data analysis.

## Steps in the Project

### 1. Data Collection
- **Database Exploration**: The provided `.db` file contains initial data on music tracks. This data includes metadata like release day, song characteristics (e.g., bpm, genre), and is stored in different tables.
- **Data Enrichment**: Using the Spotify API, enrich the dataset with track names and artist names. Keys for accessing the Spotify API are included.

### 2. Data Analysis and Visualization
- **Complete Dataset Analysis**: With the enriched dataset, the task is to find 2-3 interesting takeaways. These could relate to the popularity of artists, genres, or other song characteristics.
- **Presentation of Findings**: The findings can be presented as statistically significant statements or visualizations.

## Technical Setup
- Libraries used: `sqlite3`, `pandas`, `numpy`, `json`, `requests`, `spotipy`
- External Tools: Spotify API

## Files in the Repository
- `Spotify_Tracks_and_API_Data_Analysis_Notebook.ipynb`: Main Google Colab notebook for the project
- `spotify_data.db`: Initial database file containing music track data
- `credential_spotify.json`: Mock credentials file for Spotify API

- `enriched_df.csv`': The resulting file after the API enrichment
- `song_names.json`: The resulting backup file after API songs extraction
- `artist_names.json`: The resulting backup file after API artists extraction
