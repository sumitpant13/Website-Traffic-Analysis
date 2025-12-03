# Music Streaming Traffic Analysis — Listener Behavior & Engagement Insights

## Project Overview
This project analyzes over 226,000 streaming interaction records captured from listeners across multiple countries. The objective is to study user engagement patterns (clicks, pageviews, previews), track popularity, artist performance, geographic distribution of traffic, and temporal trends in user activity. The workflow includes data cleaning, preprocessing, descriptive analysis, frequency analysis, and visualization.

## Dataset Summary
The dataset contains 226,278 rows and 9 columns. It consists of interaction-level data including event type, timestamp, user country/city, and song-related metadata such as artist, album, and track.  
Columns: event, date, country, city, artist, album, track, isrc, linkid.

## Data Cleaning and Preparation
- Converted date column to datetime format  
- Handled missing values  
- Removed over 102,000 duplicate interaction entries for dataset integrity  
- Ensured consistency and reliability of feature types  
- Standardized values for accurate aggregation and grouping

## Exploratory Data Analysis
Performed:
- Frequency counts  
- Statistical summaries  
- Aggregation by event type  
- Most active countries and cities  
- Artists and tracks with highest engagement  
- Time series analysis of activity over dates  
- Artist-wise event category breakdown

## Key Observations
- Pageview is the most common event type, followed by click and preview.  
- Saudi Arabia, India, and the United States generate the most listener events.  
- Jeddah and Riyadh are the most active streaming locations.  
- “Tesher” and the track “Jalebi Baby” dominate engagement counts.  
- Although the dataset contains thousands of unique tracks and artists, engagement is heavily concentrated around a small set of popular content.  
- After duplicate removal, engagement patterns became clearer and more meaningful.

## Tools & Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.

## Business Applications
- Identifying top-performing songs and artists for marketing  
- Country-wise and city-wise demand analytics  
- Listener behavior profiling  
- Trend analysis for streaming performance  
- Data-driven artist promotion strategy  
- Foundation for recommendation engines

## Repository Structure
traffic.csv  
analysis.ipynb  
README.md

## Author
Sumit Pant  
Email: sumitpant2004@gmail.com  
GitHub: https://github.com/sumitpant13  
LinkedIn: https://linkedin.com/in/sumitpant13
