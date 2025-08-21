Spotify Data Visualization & Analysis
📌 Project Overview

This project explores Spotify’s top songs dataset through data cleaning, transformation, and visualization. Using Python, Pandas, and visualization libraries, I analyzed global music trends and provided meaningful insights into song popularity, audio features, and artist performance.

The project is implemented in Jupyter Notebooks:

4_Spotify_DataViz.ipynb – Contains data exploration, cleaning, and visualization steps.

Spotify_Assignment4_Janani_Karthikeyan.ipynb – Extended analysis and assignment submission.

The dataset used: universal_top_spotify_songs.csv with over 1.6 million records and 25 features.

📂 Dataset Information

File: universal_top_spotify_songs.csv
Shape: 1,692,294 rows × 25 columns

Key Columns:

spotify_id – Unique ID of the track

name – Song title

artists – Artist(s) of the track

daily_rank, weekly_movement – Chart performance

country, snapshot_date – Country & date context

popularity, is_explicit – Popularity score & explicit flag

Audio Features:

danceability, energy, key, loudness, mode

speechiness, acousticness, instrumentalness

liveness, valence, tempo, time_signature

🛠️ Tools & Libraries

Python

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Visualization

Jupyter Notebook – Development environment

🔑 Features of the Analysis

Data Cleaning (handling missing values, formatting dates, filtering columns)

Exploratory Data Analysis (EDA) on audio features and popularity

Artist & Song Popularity Rankings

Correlation between audio features (danceability, energy, valence) and popularity

Visualization of trends in global top charts

📊 Example Insights

Distribution of explicit vs. non-explicit songs

Relationship between danceability and popularity

Top recurring artists in global charts

Temporal trends in Spotify charts

🚀 How to Run

Clone the repository or download the notebooks.

Place universal_top_spotify_songs.csv in the same directory.

Install dependencies:

pip install pandas numpy matplotlib seaborn jupyter


Open Jupyter Notebook and run either:

4_Spotify_DataViz.ipynb

Spotify_Assignment4_Janani_Karthikeyan.ipynb

👩‍💻 Author

Janani Karthikeyan
Master’s in Data Analytics Engineering, Northeastern University
