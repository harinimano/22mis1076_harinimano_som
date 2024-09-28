Music Dataset Analysis

Abstract
This project analyzes a music dataset containing various features of tracks, including danceability, energy, loudness, and more. The primary objective is to explore relationships between these audio features, visualize trends over time, and gain insights into the characteristics of popular music. By employing data visualization techniques and self oraganising maps, we aim to uncover patterns that may inform future music recommendations or production.

About the Dataset
The input data for this project is a CSV file named tracks_features.csv, which contains the following columns:

Column Name    	Description
id            	Unique identifier for each track.
name          	Title of the track.
album          	Album to which the track belongs.
album_id       	Unique identifier for the album.
artists        	List of artists involved in the track.
artist_ids	    Unique identifiers for the artists.
track_number  	Position of the track in the album.
disc_number    	Disc number of the album.
explicit	      Indicates if the track has explicit content.
danceability	  Measure of how suitable a track is for dancing.
energy        	Measure of intensity and activity in a track.
key	            Musical key of the track.
loudness      	Overall loudness of a track in decibels.
mode          	Modality of the track (major or minor).
speechiness	    Presence of spoken words in a track.
acousticness  	Measure of acoustic sound.
instrumentalness	Likelihood of the track being instrumental.
liveness	      Presence of an audience in the recording.
valence        	Measure of musical positiveness.
tempo          	Speed of the track in beats per minute (BPM).
duration_ms    	Length of the track in milliseconds.
time_signature	Notation of the track's time signature.
year	          Release year of the track.
release_date	  Exact release date of the track.


Output
The output of this project includes various visualizations derived from the analysis of the dataset:

Average Danceability by Top 50 Artists:
A horizontal bar chart depicting the average danceability of tracks for the top 50 artists in the dataset, identifying which artists produce tracks most suitable for dancing.

Average Loudness Over Year: 
A line graph showing the average loudness of tracks over the years, reflecting how the loudness of music has evolved over time.

Distribution of Musical Keys: 
A pie chart visualizing the distribution of musical keys present in the dataset, illustrating the most commonly used keys in the tracks.

Correlation Heatmap of Audio Features: 
A heatmap displaying the correlation between various audio features (danceability, energy, tempo, loudness) to identify relationships that may inform further analysis or predictive modeling.

How to Execute

Software Requirements
Python 3.x

Required Libraries:
pandas
matplotlib
seaborn
numpy

Hardware Requirements
Minimum of 4 GB RAM
At least 2 GB of available disk space


Steps to Execute
Clone the repository or download the files.
Navigate to the project directory.
Install the required libraries if not already installed:
bash
Copy code
pip install pandas matplotlib seaborn numpy
Open the Google collab (som_nn.ipynb) and run the cells sequentially to generate visualizations and analysis.
