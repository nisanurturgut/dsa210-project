# Daily Spotify Listenings & Weather Analysis

## Project Overview

This project aims to analyze the relationship between my **daily Spotify listenings** and the **weather conditions** on those days (e.g., sunny, rainy, cloudy, etc.). The goal is to uncover patterns in my music preferences based on the weather, such as whether I listen to certain genres more frequently on rainy days or prefer upbeat music when it's sunny. By analyzing this data, I hope to discover if weather influences my mood and music choices.

### Key Questions:
- How do my music preferences change based on weather conditions (e.g., sunny, rainy, cloudy)?
- Are there certain genres or moods I gravitate towards depending on the weather?
- Can I identify patterns in my Spotify listening behavior related to specific weather events?

---

## Datasets

### 1. **Spotify Listenings Data**
- **Data to include:**
  - **Song Genre:** Genre of the song (e.g., Pop, Rock, Classical)
  - **Timestamp:** When the song was played (date and time)
  - **Duration:** Length of the song
  - **Play Count:** How often each song was played on a given day

### 2. **Weather Data**
- **Data to include:**
  - **Date:** The date corresponding to each listening session
  - **Weather Conditions:** Weather conditions for that date (sunny, cloudy, rainy, etc.)
  - **Temperature:** Daily temperature (optional, could be useful for analyzing mood)
  - **Humidity:** Daily humidity levels (optional)

---

## Project Plan

### 1. **Data Collection**
   - I will download my **Spotify listenings data** directly using the **Spotify**. This will include data such as the genres of songs I listen to, the timestamps, and the frequency of each song.
   - I will retrieve **weather data** for the corresponding dates of my Spotify listenings using the **WeatherAPI**. This will give me information about the weather conditions, temperature, and humidity levels for those days.

### 2. **Exploratory Data Analysis (EDA)**
   - I will preprocess and clean both datasets, ensuring that the timestamps align between my Spotify listenings and the weather data.
   - I will perform an initial analysis to explore the relationships between weather conditions and music genres:
     - Do I listen to more relaxing genres on rainy days?
     - Is there a preference for upbeat music on sunny days?
     - How does weather affect my listening time or song selection?
   
### 3. **Visualization**
   - I will create **visualizations** to explore the relationship between weather and music preferences:
     - A **bar chart** showing genre preferences on different weather days (e.g., Pop on sunny days, Classical on rainy days).
     - A **line chart** or **scatter plot** to visualize the correlation between weather conditions (like temperature or humidity) and my listening patterns (e.g., do I listen to longer playlists when it’s rainy?).
     - A **heatmap** to visualize the frequency of music genres based on the weather.
   
### 4. **Machine Learning Models**
   - If relevant, I may apply models to predict my music genre preferences based on the weather conditions.
   - For example, I could build a simple model to predict whether I will listen to an energetic or relaxing genre based on the day's weather conditions.

---
## License

This project is licensed under the MIT License.
