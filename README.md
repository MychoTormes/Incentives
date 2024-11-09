# TORMES-2ECE-D Incentives
The code uses Python Data Analysis (Pandas) and Matplotlib (data Wrangling and Manipulation).
### Overview of Dataset:
#### How many rows and columns does the dataset contain?
   - The Most Streamed Spotify Songs 2023 dataset contains 953 rows and 24 columns filled with data about the music tracks and its artists who sang it.
#### What are the data types of each column? Are there any missing values?
   -  In the dataset of 953 rows and 24 columns, the cloumns track_name, artist(s)_name, key, and mode are the data type of string, and most of the others are numerical in integer data type. There are two columns that has missing values that are columns in_shazam_charts and key.

  
### Basic Descriptive Statistics:
#### What are the mean, median, and standard deviation of the streams column?
   - As doing the data manipulation including the use of .describe(), the data shows the calculations of the streams column which the mean is at the value of 5.13887 x 10^8, standard deviation of 5.666116 x 10^8, and the value of median is 290,228,626.
#### What is the distribution of released_year and artist_count? Are there any noticeable trends or outliers?
   - The distribution of released_year and artist_count are both bidomal distribution in the data of each artists and tracks, it tells that the two scores that are equal in frequency and have the highest frequency. In describing the population of each data, the artist_count is positivily skewed while the released_year is negativily skewed in its distribution. The outliers are noticeable in the columns artist_count and released_year, the data from 4 artists to 8 artists in one song are the outliers of the artist_count while years 1930 to 2018 are outliers for the released_year.

### Top Performers:
#### Which track has the highest number of streams? Display the top 5 most streamed tracks.
   - The track that has the highest number of streams is the song Blinding Lights by The Weeknd. This are the top 5 most streamed tracks. ![My logo](https://github.com/MychoTormes/Incentives/blob/a2612b5a7831ef23b46a012a372ec3882d508d55/top5%20tracks.png)
#### Who are the top 5 most frequent artists based on the number of tracks in the dataset?
   - The top 5 most frequent artists based on the number of tracks are Harry Styles at top 5, SZA at top 4, Bad Bunny at top 3, The Wekend at top 2, and top 1 most frequent artist among the artists in the list is Taylor Swift.

### Temporal Trends:
#### Analyze the trends in the number of tracks released over time. Plot the number of tracks released per year.
   - The trend in number of tracks released in the year 2022 is the highest among the years listed. The more previous years are more less of tracks released in this analysis and it shows the distribution of negative skewed. ![My logo](https://github.com/MychoTormes/Incentives/blob/360d8837e6f6695cccd3d21c75637edee82cada5/plotyear.png)
#### Does the number of tracks released per month follow any noticeable patterns? Which month sees the most releases?
   - The number of tracks released per month does not folow any noticeable patterns for the pattern is somewhat does not resemble anything noticeable and it is interesting. The most that sees the most released is the month of January which has the count of 134 releases.

### Genre and Music Characteristics:
#### Examine the correlation between streams and musical attributes like bpm, danceability_%, and energy_%. Which attributes seem to influence streams the most?
   - The DataFrame of correlation between streams and musical attributes has the identity matrix at the relation of the two same attributes and streams. The attributes that has the most influence to streams are the speechiness_% and the danceability_% of the tracks which it is a trend in today's time.
#### Is there a correlation between danceability_% and energy_%? How about valence_% and acousticness_%?
   - The correlation between danceability_% and energy_% has a strong positive correlation of 0.198095. The valence_% and acousticness_% is in the negative correlation of -0.081907 showed in the dataset.

### Platform Popularity:
#### How do the numbers of tracks in spotify_playlists, spotify_charts, and apple_playlists compare? Which platform seems to favor the most popular tracks?
   - The number of tracks in spotify_playlists, spotify_charts, and apple_playlists are different because there are some tracks that did not exist in some other platforms so there will be the highset number of track in all of the platforms. The platform spotify_playlists has the most popular tracks in all of the platforms stored, it shows that the spotify is the most favored platform to many.

### Advanced Analysis:
#### Based on the streams data, can you identify any patterns among tracks with the same key or mode (Major vs. Minor)?
   - In key, pattern showed amogn tracks with the same key is binomal which it has the highest frequncy among the key in the track. The mode shows that Major has the most mode in the tracks which means the tracks is mostly has the same mode of Major.
#### Do certain genres or artists consistently appear in more playlists or charts? Perform an analysis to compare the most frequently appearing artists in playlists or charts.
   - Yes, the artists consistently apear in more playlists and charts as the graph is created in the code. In my analysis, The distribution of the graph is in the pattern of negativily skewed and most of the artists appear in all of the playlist and charts mentioned in the dataset showed that they really advertising their track largely in any platforms.

## Files
   - This is the code that helped to analyze the spotify 2023 dataset.

         Exploratory Data Analysis.ipynb 

## Reference

         spotify2023.csv

#### This code is created and analyzed by Mycho Tormes
