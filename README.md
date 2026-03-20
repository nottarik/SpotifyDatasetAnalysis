# 📊 Spotify 2023 Data Analysis Project

A statistical deep dive into the **Most Streamed Spotify Songs 2023** dataset. This project utilizes Python to explore global musical trends, artist dominance, and the intricate relationship between audio characteristics and commercial success.

---

## 🚀 Project Overview
This analysis was conducted in **Google Colab** as part of a statistical analysis course. The primary goal was to validate hypotheses regarding music popularity and investigate how various audio features correlate with global streams across **Spotify, Apple Music, and Deezer**.

## 🛠 Tech Stack
* **Language:** Python
* **Libraries:**
    * `Pandas` & `NumPy`: Data manipulation and cleaning
    * `Matplotlib` & `Seaborn`: Static data visualization
    * `Plotly`: Interactive charts and geographic mapping
    * `Statsmodels`: Statistical testing and correlation analysis
    * `Sequelize`: (Conceptualized for database integration in related web-apps)

---

## 📋 Key Research Questions & Hypotheses

### 1. Market Dominance
* **Top Songs:** Identification of the most-streamed tracks of 2023 (e.g., Taylor Swift's "Anti-Hero").
* **Top Artists:** Analysis of artists with the highest volume of hits.
* **Probability Analysis:** Calculating the likelihood of a specific song appearing in charts given a specific artist.

### 2. Audio Features & Popularity
* **The "Vibe" Factor:** Does the musical **Mode** (Major vs. Minor) or **BPM** significantly impact stream counts?
* **Correlation Matrix:** Analyzing the relationship between **Danceability**, **Valence** (positivity), and **Energy**.
* **Hypothesis:** *"Songs with high danceability rankings perform consistently better across all platforms (Apple, Spotify, Deezer)."*

### 3. Temporal Trends
* **Release Timing:** Investigation into which months and days see the highest volume of releases.
* **Hypothesis:** *"Melancholic songs (Minor key) are more frequently released in winter months (Dec, Jan, Feb)."*
* **Hypothesis:** *"The specific release day of the month affects a song's long-term popularity."*

### 4. Cross-Platform Comparison
* **Platform Sync:** Comparing song performance across streaming services to determine if "hits" are universal or platform-specific.

---

## 📈 Key Visualizations
The project includes several advanced visualizations to support the data narrative:
* **Distribution Plots:** Histograms showing the spread of BPM, Acousticness, and Speechiness.
* **Correlation Heatmaps:** Visualizing how musical traits interact with one another.
* **Time-Series Analysis:** Line graphs showing the evolution of song characteristics over decades.
* **Boxplots:** Analyzing outliers and stream distributions based on musical mode.

## 🧪 Statistical Highlights
* **Pearson Correlation:** Used to measure the linear relationship between artist song counts and total streams.
* **Probability Theory:** Applied to calculate the chances of high-danceability tracks reaching top charts.
* **Standard Deviation:** Analysis of how many songs fall within $2\sigma$ of the expected stream value to identify true outliers.

---

## 📂 Dataset
The analysis uses the `spotify-2023.csv` dataset, which includes 24 columns covering:
* Track metadata (Name, Artist, Release Date)
* Platform-specific chart data (Spotify, Apple, Deezer, Shazam)
* Audio descriptors (BPM, Key, Mode, Danceability, etc.)
