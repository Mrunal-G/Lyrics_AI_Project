# Lyrics_Sentiment_Analysis

**Dataset**: Song Lyrics dataset of different artists labeled using Spotify valence audio feature :

-  https://www.kaggle.com/datasets/edenbd/150k-lyrics-labeled-with-spotify-valence

From this dataset we will take a sample of extreme positive and negative song lyrics.

The goal of the project is to predict the overall positive and negative feelings aroused by a song using Spotify valence audio feature as a label to train our model based on the binary (extreme positive and negative) valence.

The Spotify API describes the valence label as a measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track.

Tracks with high valence arouses positive feelings such as happiness, cheerfulness, etc, while tracks with low valence arouses negative feelings such as sadness, depression, etc.

For the extreme cases, that is the cases where the song demonstrates a high measure of negative (<= 0.33) or a high measure of positive feelings (>= 0.67), the labels have been converted into 0’s and 1’s and used to perform supervised NLP sentiment analysis.