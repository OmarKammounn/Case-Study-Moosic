# Moosic Playlist Automation Project

**Project Summary:**

The Moosic Playlist Automation Project was a part of the Data Science bootcamp and aimed to automate the creation of curated music playlists using data science techniques. The project involved analyzing audio features of songs collected from the Spotify API and utilizing clustering algorithms to group similar songs into playlists. The ultimate goal was to enhance the playlist creation process and offer users personalized music experiences.

**Project Context:**

Moosic was a growing startup that specialized in curating playlists with a personal touch for music enthusiasts. As the company scaled, the manual process of playlist creation by music experts became a bottleneck. To address this, Moosic aimed to leverage data science to automate the playlist creation process, adding efficiency and diversity to their offerings.

**Project Steps:**

1. **Data Collection:**
   - Retrieved audio features data for songs from the Spotify API.
   - Utilized the data to capture musical characteristics like tempo, energy, and danceability.
   - Employed Python libraries such as spotipy to interact with the Spotify API.

2. **Data Exploration:**
   - Understood the meaning of various audio features and their relevance to music characteristics.
   - Examined the distribution and potential outliers of each audio feature to gain insights.

3. **Data Scaling:**
   - Applied scaling techniques like MinMaxScaler, StandardScaler, and RobustScaler to ensure fair comparison across different audio features.
   - Transformed the audio features data to have a consistent scale, avoiding biases in clustering.

4. **Clustering Analysis:**
   - Utilized the K-Means clustering algorithm to group songs with similar audio features.
   - Explored different numbers of clusters and evaluated cluster quality using metrics like silhouette coefficient and inertia.

5. **Playlist Creation:**
   - Analyzed the resulting clusters and observed patterns among songs with similar audio features.
   - Examined the distribution of features within clusters and selected representative songs for each playlist.

6. **Model Refinement:**
   - Refined the number of clusters using techniques like the elbow method and silhouette coefficient.
   - Chose the optimal number of clusters that best captured the diversity of songs.

**Libraries Used:**

- spotipy
- pandas
- scikit-learn (MinMaxScaler, KMeans, silhouette_score)
- Matplotlib (for data visualization)

**Project Completion:**

The Moosic Playlist Automation Project was successfully completed during the Data Science bootcamp. The project demonstrated the application of data science techniques to automate and enhance the playlist creation process. By leveraging audio features and clustering algorithms, Moosic aimed to provide users with more personalized and diverse music playlists.
