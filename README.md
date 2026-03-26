# Subjectivity of Music Analysis
*Project for GEN MUSIC 170 at Northwestern University - Maya Schwartz*

## Overview
This project examines the relationship between algorithmic music metrics and subjective human perception of music. Streaming platforms, such as Spotify, assign numerical values to tracks (danceability, energy, valence, acousticness, instrumentalness) to categorize and recommend songs. However, music is a deeply personal experience, shaped by social, emotional, and cultural factors.

By comparing my personal ratings for three songs, *Bohemian Rhapsody* (Queen), *Firestarter* (The Prodigy), and *So What* (Miles Davis), to Spotify's calculated metrics, this analysis highlights where algorithmic evaluations align or diverge from lived listening experiences.

## Methodology
- Used a pre-scraped Spotify dataset of 200,000 tracks from Kaggle  
- Selected five audio features: Danceability, Energy, Valence, Acousticness, Instrumentalness  
- Rated three songs personally on these features  
- Visualized differences using interactive radar plots to compare subjective vs. algorithmic ratings  
- Discussed the implications for algorithmic recommendations and musical subjectivity  

## Key Findings
- Certain songs, like *Firestarter*, showed notable discrepancies in danceability and instrumentalness  
- Subjective perception of music can diverge from numeric metrics, reflecting emotional, cultural, and personal listening contexts  
- Raises questions about how platforms quantify taste, the autonomy of listener choice, and limits of algorithmic personalization  

## Data Sources
- [Ultimate Spotify Tracks Dataset on Kaggle](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db/data)  
- Spotify API Documentation for audio features: [Spotify Web API Reference](https://developer.spotify.com/documentation/web-api/reference/get-audio-features)  

## Files
- `spotify_analysis_code.ipynb` – Python script containing analysis code and radar plot visualizations  
- `spotify_analysis_report.html` – Full write-up including methodology, findings, and discussion  
