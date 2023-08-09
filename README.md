# Moosic Playlist Automation Project

**Project Summary:**

The Moosic Playlist Automation Project was a component of the Data Science bootcamp and aimed to automate the creation of curated music playlists using techniques from data science. The creation of the project involved the analysis of audio features of songs obtained from the Spotify API and the utilization of clustering algorithms to form playlists with similar songs. The primary objective was to improve the process of playlist creation and deliver personalized music experiences to users.

**Project Context:**

Moosic, a burgeoning startup, specialized in crafting playlists with a personalized touch for aficionados of music. As the company expanded, the manual approach of playlist creation by music experts presented limitations. In response, Moosic sought to harness data science to automate the playlist creation process, thereby enhancing their offerings with greater efficiency and diversity.

**Project Steps:**

1. **Data Collection:**
   - Data pertaining to audio features for songs was retrieved from the Spotify API.
   - The data facilitated the capture of musical attributes like tempo, energy, and danceability.
   - The interaction with the Spotify API was facilitated using Python libraries, including spotipy.

2. **Data Exploration:**
   - The significance of diverse audio features and their pertinence to musical traits was comprehended.
   - An exploration of the distribution of each audio feature was conducted, identifying potential outliers to derive insights.

3. **Data Scaling:**
   - Scaling techniques such as MinMaxScaler, StandardScaler, and RobustScaler were applied to ensure equitable comparisons across distinct audio features.
   - The transformation of audio features data enabled the establishment of a uniform scale, circumventing biases in clustering.

4. **Clustering Analysis:**
   - The K-Means clustering algorithm was employed to cluster songs sharing akin audio features.
   - Various cluster quantities were explored and the quality of clusters was evaluated using metrics such as silhouette coefficient and inertia.

5. **Playlist Creation:**
   - Analysis of resulting clusters revealed patterns among songs possessing similar audio features.
   - The distribution of features within clusters was examined, enabling the selection of representative songs for each playlist.

6. **Model Refinement:**
   - The number of clusters was honed employing techniques like the elbow method and silhouette coefficient.
   - The optimal number of clusters, which optimally encapsulated song diversity, was chosen.

**Libraries Utilized:**

- spotipy
- pandas
- scikit-learn (MinMaxScaler, KMeans, silhouette_score)
- Matplotlib (for data visualization)

**Project Conclusion:**

The completion of the Moosic Playlist Automation Project occurred successfully during the Data Science bootcamp. The project illuminated the practical application of data science techniques for automating and enhancing the playlist creation process. Through the amalgamation of audio features and clustering algorithms, Moosic aspired to furnish users with playlists that are both personalized and eclectic.
