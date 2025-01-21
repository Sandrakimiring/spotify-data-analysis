# spotify-data-analysis
# Spotify Data Analysis

This project involves analyzing Spotify music data using various Python libraries such as `pandas`, `matplotlib`, and `seaborn`. The analysis includes exploring different aspects of songs, such as energy, valence, instrumentalness, and other musical attributes, to identify trends and patterns in popular tracks and artists.

## Project Overview

In this project, the following tasks were carried out:
- Data exploration and cleaning
- Analysis of top energetic tracks
- Identifying the most popular artists based on song data
- Visualizations to showcase trends in music data, such as energy, valence, and more
- Detailed visualizations for artists, energetic tracks, and other musical attributes

## Dataset

The dataset used for this analysis contains information about various tracks from Spotify, including attributes like:
- Song Title
- Artist
- Energy
- Valence
- Acousticness
- Instrumentalness
- Duration (in milliseconds)
- And more...

The dataset is loaded from CSV files and processed using `pandas` for data manipulation and `matplotlib` / `seaborn` for visualization.

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating static, animated, and interactive visualizations.
- `seaborn`: For statistical data visualization based on `matplotlib`.

## Analysis and Visualizations

### 1. Top Energetic Tracks
We identified the top 10 energetic tracks by analyzing the `energy` attribute of each song. These tracks were visualized to show the highest-energy songs.

### 2. Most Popular Artists
By counting the number of occurrences of each artist in the dataset, we were able to find out which artists are the most popular, based on the songs included in the dataset.

### 3. Most Common Durations
This analysis shows the most common song durations in the dataset to give insights into song lengths.

### 4. Top Tracks by Valence
We also explored the `valence` attribute of songs, which represents the musical mood, and identified the top 10 tracks with the highest valence.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Sandrakimiring/spotify-data-analysis.git
