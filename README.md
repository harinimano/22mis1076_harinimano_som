Music Dataset Analysis

Abstract
This project analyzes a music dataset containing various features of tracks, including danceability, energy, loudness, and more. The primary objective is to explore relationships between these audio features, visualize trends over time, and gain insights into the characteristics of popular music. By employing data visualization techniques, we aim to uncover patterns that may inform future music recommendations or production.

Input
The input data for this project is a CSV file named tracks_features.csv, which contains the following columns:

id: Unique identifier for each track.
name: Title of the track.
album: Album to which the track belongs.
album_id: Unique identifier for the album.
artists: List of artists involved in the track.
artist_ids: Unique identifiers for the artists.
track_number: Position of the track in the album.
disc_number: Disc number of the album.
explicit: Indicates if the track has explicit content.
danceability: Measure of how suitable a track is for dancing.
energy: Measure of intensity and activity in a track.
key: Musical key of the track.
loudness: Overall loudness of a track in decibels.
mode: Modality of the track (major or minor).
speechiness: Presence of spoken words in a track.
acousticness: Measure of acoustic sound.
instrumentalness: Likelihood of the track being instrumental.
liveness: Presence of an audience in the recording.
valence: Measure of musical positiveness.
tempo: Speed of the track in beats per minute (BPM).
duration_ms: Length of the track in milliseconds.
time_signature: Notation of the track's time signature.
year: Release year of the track.
release_date: Exact release date of the track.

Output
The output of this project includes various visualizations derived from the analysis of the dataset:

Average Danceability by Top 50 Artists:
This horizontal bar chart depicts the average danceability of tracks for the top 50 artists in the dataset. It allows us to identify which artists produce tracks that are most suitable for dancing, providing insights into popular trends in the music industry.

Average Loudness Over Year:
This line graph shows the average loudness of tracks over the years. The trend highlights how the loudness of music has evolved over time, which may reflect changes in production techniques and listener preferences.

Distribution of Musical Keys:
The pie chart visualizes the distribution of musical keys present in the dataset. It illustrates the most commonly used keys in the tracks, offering insight into the harmonic choices made by artists.

Correlation Heatmap of Audio Features:
This heatmap displays the correlation between various audio features, such as danceability, energy, tempo, and loudness. The matrix helps identify relationships between features, which can inform further analysis or predictive modeling.
