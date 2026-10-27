# 🎵 Spotify Data Cleaning

Data cleaning and preparation of a 10K-track Spotify dataset using Python (Pandas, NumPy).

## Cleaning Steps
- Inspected structure, duplicates, and missing values.
- Filled missing categorical values (artist, genre, language, album type) with "Unknown" labels.
- Filled missing numerical values with the median.
- Detected outliers using the IQR method.
- Fixed impossible values:
  - Track duration under 30 seconds treated as errors.
  - Popularity above 100 and danceability above 1 treated as errors.
  - Negative and placeholder stream counts (1.5e11) replaced with the median.
- Capped duration outliers and added a `duration_sec` column.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly

## Files
- `Spotify_Data_Cleaning.ipynb`: full analysis notebook
- `spotify_data_10k.xlsx`: dataset

## Author
**Abdelrahman Magdy**
[LinkedIn](https://www.linkedin.com/in/abdelrahman-magdy-dev/) | [GitHub](https://github.com/codeabdo)
