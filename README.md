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
   - The track that has the highest number of streams is the song Blinding Lights by The Weeknd. This are the top 5 most streamed tracks.
