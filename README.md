# SpotiData Project 
## Why do we listen to the music we listen to? An analysis of trends on Spotify

### Project 1 Team: Jovan, Sofia & Diana
### University of Birmingham / Data Analysis Bootcamp

We have worked with the Spotify API to analyse:

The most streamed songs of all time: [Initial Dataset](/Resources/Most-Streamed-Songs-All-Time.csv). [Source](https://chartmasters.org/spotify-most-streamed-songs/).

The Top-100 songs of each year of the last 20 years (2000-2021): [Initial Dataset](/Resources/MusicCharts.csv). [Source](https://chart2000.com/about.htm#google_vignette).

The most streamed artists: [Initial Dataset](/Resources/artist_data.csv). [Source](https://chartmasters.org/most-streamed-artists-ever-on-spotify/).


## Spotify API

Through Spotify audio analysis API we have obtained information such as:

· Acousticness
· Danceability
· Duration
· Energy
· Instrumentalness
· Liveness
· Loudness
· Speechiness
· Tempo
· Valence

You can find the Spotify Audio Analysis API Documentation and audio features definitions [here](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features).


## Data Analysis

Some of the questions we asked ourselves and have answered through data analysis are:

* What similarities are there in the most popular music?
* Is there any correlation between popularity and danceability / energy / tempo / etc?
* From which year are the most streamed songs on spotify?
* Do we like less danceable music or more danceable? (danceability)
* Do we like vocal or instrumentalness music? (instrumentalness)
* Does the music we like sound more positive or more negative? (valence)

* What differences/similarities are there in the most popular music through time (from 2000 to 2021)?
* How has the danceability, the tempo, the energy changed over the last few years?
* Were there any of these variables that changed a significant amount?

* Of the 1000 most popular artists, how many songs did they make on average? 
* How many of them became popular? 
* What is the most popular genre?


## Files

* You can find in the .ipynb file all the analysis with pandas, numpy and matplotlib, as well as the information requests to the Spotify API.
* In [Resources](/Resources) are the datasets.
* In [Figures](/Figures) are the plots made with matplotlib.
