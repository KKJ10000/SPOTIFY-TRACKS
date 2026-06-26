# SPOTIFY-TRACKS
Exploratory Data Analysis (EDA) of Spotify tracks using Python, Pandas, NumPy, Matplotlib, and Seaborn. Includes data cleaning, feature engineering, visualization, and music trend analysis.
# 🎵 Spotify Tracks Data Analysis

An end-to-end **Exploratory Data Analysis (EDA)** project on Spotify tracks using **Python, Pandas, NumPy, Matplotlib, and Seaborn**. This project demonstrates data cleaning, feature engineering, visualization, and statistical analysis of music datasets.

---

## 📌 Project Overview

This project explores a Spotify tracks dataset to uncover insights into:

- 🎤 Most frequent artists
- 🎼 Genre popularity
- 🔥 Song popularity
- 💃 Danceability and energy
- 🎧 Audio feature relationships
- 📊 Correlation between musical features

The workflow follows a complete data analysis pipeline—from loading raw data to exporting a cleaned dataset.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset

**File Used**

```
spotify_tracks.csv
```

The dataset contains information such as:

- Genre
- Artist Name
- Track Name
- Popularity
- Danceability
- Energy
- Loudness
- Tempo
- Valence
- Acousticness
- Instrumentalness
- Speechiness
- Liveness
- Duration
- Time Signature

---

# 📊 Project Workflow

## 1️⃣ Data Loading

- Import required libraries
- Load Spotify dataset using Pandas

---

## 2️⃣ Data Inspection

- Dataset information
- First few records
- Statistical summary
- Missing value detection

---

## 3️⃣ Data Cleaning

- Fill missing artist names
- Fill missing track names
- Remove rows with missing audio features

---

## 4️⃣ Feature Engineering

Created new features including:

### 🎵 Main Artist

Extracts the first artist from collaborations.

Example:

```
Drake, Future
```

becomes

```
Drake
```

---

### 💃 Dance Category

Categorizes songs based on danceability.

| Danceability | Category |
|--------------|----------|
| < 0.30 | Low |
| 0.30 – 0.59 | Medium |
| ≥ 0.60 | High |

---

### 🎉 Party Score

A custom feature combining:

```
PartyScore =
(Energy + Danceability) / 2
```

Higher values indicate songs that are both energetic and danceable.

---

## 5️⃣ Exploratory Data Analysis

The project answers questions such as:

- Who are the most common artists?
- Which genres appear most frequently?
- How many songs are highly popular?
- Which genres have the highest average popularity?
- What is the relationship between Energy and Danceability?
- Which audio features are strongly correlated?

---

## 📈 Visualizations

The project generates multiple visualizations including:

### 🎤 Top 10 Artists

Bar chart showing artists with the highest number of tracks.

---

### 📈 Popularity Trend

Average popularity by release year (if available).

---

### 🎵 Energy vs Danceability

Scatter plot showing the relationship between these two audio features.

---

### 🔍 Missing Data Heatmap

Visual representation of missing values across the dataset.

---

### 📊 Correlation Heatmap

Correlation matrix for audio features including:

- Popularity
- Danceability
- Energy
- Loudness
- Tempo
- Valence

---

## 📁 Output Files

The project saves:

```
spotify_cleaned.csv
spotify_artists.png
spotify_popularity_trend.png
spotify_energy_dance.png
spotify_missing.png
spotify_correlation.png
```

---

## 📚 Skills Demonstrated

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Filtering
- GroupBy Operations
- String Processing
- Custom Functions
- Data Visualization
- Correlation Analysis
- Exporting Processed Data

---

## 🚀 Future Improvements

- Music recommendation system
- Song popularity prediction using Machine Learning
- Genre classification
- Artist similarity analysis
- Interactive dashboard using Streamlit
- Spotify API integration
- Time-series analysis of music trends

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Spotify-Tracks-Analysis.git
```

Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

Run

```bash
python spotify_analysis.py
```

---

## 📸 Sample Visualizations

The repository generates charts similar to:

- Top Artists
- Popular Genres
- Energy vs Danceability
- Missing Data Heatmap
- Feature Correlation Heatmap

---

## 👨‍💻 Author

**Kshitij Kumar Jha**

B.Tech Robotics & Automation  
Machine Learning • Data Science • AI • Robotics

GitHub: https://github.com/KKJ10000

LinkedIn: https://www.linkedin.com/in/kshitij-kumar-jha-329416241

---

## ⭐ If you found this project useful, consider giving it a star!
