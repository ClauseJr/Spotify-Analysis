# Spotify Music Analytics Project

## Executive Summary

### Overview Findings
This project provides an exploratory and descriptive analysis of Spotify music data using interactive dashboards built in Power BI, with data preparation and structuring performed in Excel. The objective is to uncover patterns in artist performance, song characteristics, popularity trends, and audio feature distributions over time.

The analysis is designed to support data-driven storytelling, combining visual clarity with analytical depth to better understand music consumption and artist dynamics on Spotify.


The interactive Power BI dashboard enables us to:
  -  Analyze Spotify songs and artists using descriptive statistics and visual analytics
  -  Identify trends in song popularity, energy, danceability, and listener mood
  -  Examine artist-level performance and contribution to overall streaming metrics
  -  Understand temporal patterns in song releases and popularity over time
  -  Develop an interactive dashboard suitable for decision-making and storytelling

### Data Sources
The data spans a wide time range (1905–2024), allowing both historical and modern trend analysis.
The primary dataset of this analysis is from [kaggle.com](https://www.kaggle.com/), containing over 1000 records.

Get the whole dataset here [spotify_data](https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset/data)

---
## Tools Used
a. Excel:
Excel was used as the initial data preparation tool to:
  -  Clean and standardize column formats (dates, numerical fields)
  -  Handle missing and inconsistent values
  -  Create derived fields such as duration in minutes and categorical groupings
  -  Validate data integrity before visualization

This step ensured the dataset was structured and analysis-ready before ingestion into Power BI.
     
b. Power BI:
Within Power BI:
  -  Relationships were established between songs, artists, and categorical dimensions
  -  Measures were created using DAX to calculate:
      -  Total and average popularity
      -  Song counts and distinct artist counts
      -  Aggregated audio feature values

Filters and slicers were implemented for dynamic analysis by year, artist, and song
    
---

##  Dashboard Analysis

###  1. Main (Overview) Dashboard

This dashboard provides a high-level summary of the Spotify dataset, focusing on overall performance indicators.

Key KPIs:

  -  Total Songs Analyzed: 1,404
  -  Total Artists: 1,158
  -  Average Song Duration: 3.58 minutes
  -  Average Popularity Score: 75.81

Analytical Insights:
  -  A significant proportion of songs fall into high energy and high danceability categories
  -  Listener mood distribution shows dominance of neutral and happy moods
  -  Electronic and mixed production styles lead in acousticness distribution
  -  Fridays have the highest number of song releases
  -  Popularity fluctuates across months, indicating seasonal trends
  -  This dashboard functions as an executive summary, offering quick insight into overall streaming behavior.

###  2. Artist Dashboard

The artist dashboard focuses on artist-level analysis, highlighting contribution and performance differences.

Key Insights:
  -  Artists vary significantly in song volume, popularity, and audio feature intensity
  -  Top artists dominate cumulative popularity despite differences in song counts
  -  Energy and tempo profiles differ widely across artists, influencing engagement
  -  Subgenre and playlist exposure play a major role in artist visibility
  -  This view supports comparative analysis and identification of high-impact artists.

###  3. Songs Dashboard

The songs dashboard provides a granular, track-level perspective.

Key Features:
  -  Detailed song table including popularity, duration, energy, danceability, and valence
  -  Analysis of songs by weekday and month of release
  -  Popularity breakdown by albums, playlists, and subgenres
  -  Identification of tracks and collections driving engagement
  -  This dashboard enables deep-dive exploration of individual songs and catalog trends.

---

##  Key Findings

  -  High-energy and danceable songs consistently perform better in terms of popularity
  -  Artist popularity is influenced by both consistency and strategic playlist placement
  -  Release timing, particularly Fridays, correlates with higher song volume and visibility
  -  Audio features such as energy, tempo, and valence are strong indicators of listener engagement
  -  Spotify streaming trends reflect evolving audience preferences over time

---
##  Limitations & Caveats
  -  The dataset excludes information on editorial playlists, paid promotions, or external marketing efforts that significantly impact streaming performance.
  -  The dataset does not include listener age, location, or behavioral context, limiting the ability to perform audience segmentation or regional performance analysis.
  -  The dataset is based on spotify analysis, and it might not be the real spotify data.

---
    
##  Conclusion

This project demonstrates the practical application of Excel and Power BI in transforming raw Spotify data into meaningful analytical insights. By combining data preparation, modeling, and interactive visualization, the analysis delivers a comprehensive view of music streaming behavior.

---
## References

1.	SQL for Data Engineering [Data with Baraa](https://www.youtube.com/watch?v=SSKVgrwhzus)
2.	Data Analytics with [Chandoo](https://www.youtube.com/results?search_query=chandoo)











