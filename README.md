# disco_song
## Dataset Used
This dataset has been used from kaggle and is a vibrant collection of 724 tracks from 101 artists, capturing the essence and evolution of disco music over the decades. 

Each record in the dataset is enriched with Spotify audio features, providing detailed insights into the musical attributes that made disco a cultural phenomenon. These features include metrics such as : Track, Artist, Album, Year Released, Duration, Time Signature, danceability, energy, tempo, Popularity etc.

Whether you're analyzing the rhythmic patterns that kept disco at the top of the charts or exploring the genre's influence on contemporary music, this dataset serves as a comprehensive resource for understanding the enduring legacy of disco.

## Project Details
🔥 Agenda : In this project we are dividing spotify tracks into different clusters based on the Tempo and their Popularity.

🔥 Method : 

🎯 First we see that data has no null values

🎯 Then we put values from 'Tempo' and 'Popularity' column into an array X.

🎯 We use K-means algorithm to divide these songs into clusters.

🎯 We plot an elbow curve to find optimal number of clusters for dividing the data point

🎯 Finally we plot a graph of Tempo vs. Popularity with data points divided into clusters where each cluster is represented by a colour

🔥 Conclusion : We were able to divide the spotify tracks into 6 clusters based on Tempo and Popularity and plot them on a graph where each cluster is represented by different colour
