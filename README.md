# spotify-music-analysis
A comprehensive Exploratory Data Analysis (EDA) of the Spotify Dataset using Python. Analyzes over 580k tracks and 1.1M artists to uncover trends in song popularity, audio features (danceability, energy), and artist insights using Pandas, Matplotlib, and Seaborn.
# Spotify Music Data Analysis Project

This project performs an in-depth Exploratory Data Analysis (EDA) on a Spotify dataset containing information about tracks and artists. Using Python and data science libraries, the project uncovers insights into what makes a song popular, correlations between audio features, and trends over time.

## 📊 Project Overview
The analysis is conducted in a Jupyter Notebook (`Untitled6.ipynb`) and processes two main datasets:
- **Tracks:** ~586,000 songs with 20 attributes (popularity, duration, tempo, energy, etc.).
- **Artists:** ~1.1 million artists with follower counts and genres.

## 🚀 Key Features
* **Data Cleaning:** Handling missing values and formatting release dates for time-series analysis.
* **Popularity Analysis:** Identifying the most popular tracks and artists in the dataset (e.g., Justin Bieber, Olivia Rodrigo).
* **Correlation Heatmaps:** Visualizing the relationship between features like `Loudness` and `Energy`.
* **Audio Feature Distribution:** Examining how `Danceability`, `Acousticness`, and `Valence` vary across songs.
* **Duration Trends:** Converting and analyzing track lengths from milliseconds to seconds.

## 🛠️ Technologies Used
* **Python**
* **Pandas:** Data manipulation and cleaning.
* **NumPy:** Numerical operations.
* **Matplotlib & Seaborn:** Data visualization and heatmaps.

## 📈 Key Insights from the Data
* **Correlation:** A strong positive correlation was observed between `Loudness` and `Energy`.
* **Top Hits:** The dataset highlights global hits like "Peaches" by Justin Bieber and "drivers license" by Olivia Rodrigo as peak popularity examples.
* **Statistical Summary:** Most tracks have a mean popularity score of approximately 27.5, with audio features like danceability averaging 0.56.

## 📂 Dataset
The project utilizes the following CSV files (not included in this repo due to size, available via Kaggle):
- `tracks.csv`
- `artists.csv`

## ⚙️ How to Run
1. Clone this repository.
2. Ensure you have Python installed along with `pandas`, `seaborn`, and `matplotlib`.
3. Place the `tracks.csv` and `artists.csv` files in the project directory.
4. Run the Jupyter Notebook `Untitled6.ipynb`.
