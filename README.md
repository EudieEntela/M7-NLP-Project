# Natural Language Processing Project - Spotify Playlist Sentiment Analysis

In this project, using NLP, I am able to perform sentiment analysis in order to produced clusters to then try and find underlying patterns.

I work with Spotify's API in order to collect data from the current playlist of 'Top 50 Global Songs'. After that, using Genius' API, I grab the lyrics for each song on the playlist and apply sentiment analysis on the lyrics to give each song a sentiment score between -1 and 1 (Negative, Neutral or Positive scores).

From the results, I build a KMeans model, find the best number of clusters with the elbow method, and apply it for a final model. I am able to then visualize the clusters based on Sentiment Score and Song Popularity.

From this project, I am able to see patterns like 80% of the top songs have a positive sentiment score based on lyrics. Having the songs be in the top 50 currently does not really help with the popularity score having it being all very high. It would be interesting to add on to this project with more song data including songs with various popularity scores in order to see a a good distribution using this model.
