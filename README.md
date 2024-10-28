# Colina-Ainsley-Neal-C.-2ECE-A-Incentives

The code uses pandas to show the rows and columns,and matploitlib and seaborn for visualization 

GUIDE QUESTIONS:

You are expected to answer the following questions using your analysis:

Overview of Dataset

How many rows and columns does the dataset contain?

-The dataset contains 953 rows and 23 columns

What are the data types of each column? Are there any missing values?

-The track_name,artist(s)_name,key, and mode are strings while the rest are int or numeric values.Yes, there are many missing values mostly associated with the track_name,and artist(s)_name because some of the letter it contains are ñ and other unique characters resulting in missing values.

Basic Descriptive Statistics

What are the mean, median, and standard deviation of the streams column?

-The mean is:514,044,878.88
-The median is:290,530,915
-The Standard deviation is:566,933,763.94

What is the distribution of released_year and artist_count? Are there any noticeable trends or outliers?

-The distribution of released_year: the year with the most releases is 2022,second is 2023,third is 2021.While the artist count is low.

Top Performers

Which track has the highest number of streams? Display the top 5 most streamed tracks.

-The top 5 highest streamed tracks are:
*Blinding lights
*Shape of you
*Someone you loved
*Dance Monkey
*Sunflower-Spiderman into the spiderverse

Who are the top 5 most frequent artists based on the number of tracks in the dataset?

-The top 5 most frequent artist on the 2023 csv are:
*Taylor swift-33
*The Weekend-22
*SZA-19
*Bad Bunny-19
*Harry Styles-17

Temporal Trends

Analyze the trends in the number of tracks released over time. Plot the number of tracks released per year.

-The year 2022 has the most number of tracks released over time and after that the spike decreases in 2023.

Does the number of tracks released per month follow any noticeable patterns? Which month sees the most releases?

-Yes, it is mostly increasing,decreasing and it hits its lowest in August and continues to increase in November and decrease again in December.The month with the most releases is January with 133.

Genre and Music Characteristics

Examine the correlation between streams and musical attributes like bpm, danceability_%, and energy_%. Which attributes seem to influence streams the most?

-The attribute that seems to influence the most is energy.

Is there a correlation between danceability_% and energy_%? How about valence_% and acousticness_%?
Danceability and energy

- If the correlation coefficient is close to 1, it indicates a strong positive correlation, meaning that as danceability increases, energy tends to increase as well.If the coefficient is close to -1, it indicates a strong negative correlation, meaning that as danceability increases, energy tends to decrease.A coefficient close to 0 suggests little to no correlation between the two variables.

Valence and Acousticness

-It is similar as Danceability and energy
 Platform Popularity

How do the numbers of tracks in spotify_playlists, spotify_charts, and apple_playlists compare? Which platform seems to favor the most popular tracks?

- The numbers of tracks in spotify_playlists, spotify_charts, and apple_playlists shows that spotify_charts has the most with:620078155.03 streams,2nd is apple_playlist with:517359959.25 streams, and last is spotify playlist with 514585409.77 streams

Advanced Analysis

Based on the stream's data, can you identify any patterns among tracks with the same key or mode (Major vs. Minor)?

-Yes, the average stream most likely wants the key with a major rather than a minor. The major has 8/11 more average streams than a minor with 3/11 average streams

Do certain genres or artists consistently appear in more playlists or charts? Perform an analysis to compare the most frequently appearing artists in playlists or charts.

-Taylor swift has the most appearance in charts and the weekend has more appearance in playlist, this shows that the more playlist count you got the more likely you will appear frequently in the chart
