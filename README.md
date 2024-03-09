# Google Data Analytics Capstone
By Amber Halvorsen\
Last updated: 03/08/2024
### Music Composition affect the Public Outlook

**Business Task**: Can spotify metrics be able to predict how popluar song will be?

**Data Analysis Process**:\
Ask\
I thought about the metrics that spotify had provided in dataset would actually help them predict what song will do better. I sent out to see if the key(mode) and/or spotify metrics could be used for good measurement in the poplularity of a song or artist.\
Prepare & Process\
I found that if a song or artist name had characters that were not in the english language would return as randomize characters. I first had to fix all the track names and artist names affected. A quarter of the songs on the dataset did not have the key and mode in which I found/replaced on the excel csv file created after downloading dataset. I used SQL is concate the released date(month/date/year) and to sort everything by streams in descending order. I used the same query to get the bottom 100 songs. Lastly I used SQL to create a table that the Avg Bpm for the Top 5, 10, 25, 50, and 100 streamed songs on Spotify. See Below \
Analyze\
In my analysis, I found what patterns the top5 & bottom5 had with spotify metrics using Tableau. I also found the avg pattern for the bottom 100 stream songs. Lastly I found the most common key(mode) and what the avg bpm. I also added a visualization that shows the top 12 streamed artist on spotify for 2023.\
Share & Act\
I found that there is a trend that current popluar songs have high bpm/faster paced. The major insight that was found for the most of spotify metrics that the top streamed songs and bottom had very similar patterns. Except for acousticness in which the bottom 100 songs had around 50% accoustic sounds in their song. Where as the top barely had any accoustics. I would suggest for spotify to use these visualization as a way to notice trends in music. It would also  create a machine learning platform that will adapt based on how metrics change to what is suggest the person should listen to next.

**Key Terms**:\
track_name: Name of the song\
artist(s)_name: Name of the artist(s) of the song\
artist_count: Number of artists contributing to the song\
released_year: Year when the song was released\
released_month: Month when the song was released\
released_day: Day of the month when the song was released\
in_spotify_playlists: Number of Spotify playlists the song is included in\
in_spotify_charts: Presence and rank of the song on Spotify charts\
streams: Total number of streams on Spotify\
bpm: Beats per minute, a measure of song tempo\
key: Key of the song\
mode: Mode of the song (major or minor)\
Spotify Metrics:\
danceability_%: Percentage indicating how suitable the song is for dancing\
valence_%: Positivity of the song's musical content\
energy_%: Perceived energy level of the song\
acousticness_%: Amount of acoustic sound in the song
instrumentalness_%: Amount of instrumental content in the song\
liveness_%: Presence of live performance elements\
speechiness_%: Amount of spoken words in the song

#### Dataset 
Url Link to Dataset: [Click](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023) \
*Released by NIDULA ELGIRIYEWITHANA*

#### SQL Code
Updated Datase(Organizing): [Click](https://console.cloud.google.com/bigquery?sq=158839804616:04f8c4fa9cc2494ebf371fe98a56d249) \
Avg Bpm for Top Streamed Songs: [Click](https://console.cloud.google.com/bigquery?sq=158839804616:694689c615ad417ebcf77349d3195972)

#### Visualization
Tableau Visualization Link: [Click](https://public.tableau.com/app/profile/amber.halvorsen/viz/MusicCompositionaffectthePublicOutlook/MusicCompositionEffectonPopularityofSongs-1)


