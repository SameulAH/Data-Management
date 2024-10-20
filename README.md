# Spotify Data Analysis Project

## Description

This project focuses on analyzing Spotify music data to gain insights into trends in the music industry. The dataset, which includes songs, albums, and artists, is enriched with attributes such as song popularity, release dates, and genres. Using data exploration, visualization, and statistical techniques, the project uncovers patterns related to song attributes, artist influence, and genre distributions from 2010 to 2022. The analysis provides valuable insights into evolving music trends and listener preferences, contributing to the growing field of music analytics.


## Key Techniques:

- **Data Collection: Spotify API is used to collect data related to songs, artists, and albums. Additionally, web scraping techniques are employed to gather song lyrics from websites like Vagalume and Letras.
- **Data Preprocessing: Data cleaning and integration of various sources to ensure consistency, completeness, and accuracy. The preprocessing includes handling missing data, standardizing formats, and removing duplicates.
- **Natural Language Processing (NLP):
    **TF-IDF (Term Frequency-Inverse Document Frequency) is used to extract keywords from song lyrics.
    **Word Clouds are generated to visualize the most important terms in the lyrics.
- **Exploratory Data Analysis (EDA): Visualization techniques, such as heatmaps and line charts, are used to analyze correlations between song attributes like danceability, energy, and popularity.
- **Statistical Analysis: Insights are derived from analyzing trends in song releases and their popularity across different timeframes.

## Pipelines Used:

### Data Collection Pipeline:

- **Spotify API Integration: Collection of song attributes like tempo, energy, danceability, and acousticness.
- **Web Scraping: Lyrics collection from Vagalume, Letras, and additional genre data from Wikipedia.
- **Data Integration: Combining Spotify API data with web-scraped data and ensuring proper alignment using unique identifiers (e.g., song title or Spotify ID).

### Data Cleaning & Preprocessing Pipeline:

- **Data Standardization: Formatting the collected data into a consistent structure.
- **Handling Missing Values: Ensuring all records have complete and accurate information by addressing missing data points.
- **Deduplication: Removing any redundant entries to maintain dataset integrity.
### Data Analysis Pipeline:

- **NLP Processing: Preprocessing lyrics (tokenization, stop word removal, lowercasing) followed by TF-IDF keyword extraction.
- **Exploratory Data Analysis (EDA): Visualizing trends using various charts such as correlation heatmaps, line charts for song release dates, and keyword word clouds.
- **Song Release Distribution: Analysis of song release trends over months and seasons to identify patterns in song popularity.
### Data Visualization Pipeline:

- **Correlation Heatmaps: Showing relationships between features like danceability, energy, and popularity.
- **Word Cloud: A visual representation of the most common keywords across songs, based on their TF-IDF scores.
- **Seasonal and Monthly Release Trends: Line charts depicting song release patterns over different times of the year.


## Key Findings:

- **Trends in Music (2010-2022): Analysis of Spotify data reveals how music preferences have evolved over time, including changes in genres, audio features, and song popularity.
- **Artist Popularity: Insights into factors influencing artist popularity, including song attributes and listener interactions.

Instructions to install and set up the project locally.

## Future Work
The dataset opens avenues for further exploration, such as building recommendation systems, genre classification, or predicting song popularity using machine learning techniques.

