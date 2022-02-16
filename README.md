# Bigdata Project (Team - 21)
# Music Recommendation System

## Dataset: http://millionsongdataset.com/
 - MillionSongSubset
 - TRIPLETS FOR 1M USERS
 
## Model Classes:
 - User Model.
 - Songs MetaData Model.
 
## Data preprocessing: 
 - Main characteristics and relative features to our questions. 
 - Pruning the dataset(Removing empty rows).
 - Removing musics from the user dataset which are not in the dataset.

## Research Questions: (Recommending music)

- What genre, song, artist or album would a user prefer to be recommended?
- How can we use the data set to identify users with similar musical preferences?
- What are the qualities that consumers want to see in their playlists?
- What is the best way to extract item features from a data set?
- How can metadata features be linked with patterns in users' listening behaviour?
- What is content-based filtering, and why should we use it?
- What is collaborative filtering, and why should we use it?
- How can we personalise next-track music recommendations by extracting long-term preference signals from users' long-term listening behaviour, such as favourite   songs, favourite artists, or favourite themes?

 
 


## Metrics to measure the accuracy: 
Prediction accuracy is generally independent of the user interface and can be estimated offline by implementing different supervised machine learning evaluation metrics. In this part, the different algorithms could be evaluated and compared. The metrics give insight into how relevant the list of recommended items is. K is chosen as the top number of recommended documents.

 - Precision(P@k): the percentage of relevant documents among the top-k documents.
 - Recall@k : the percentage of the relevant documents that are succesfully recommended.
 - Average precision(Ap@K) 
 - Mean average precision(MAP@K)
 - Personalization (average cosine similarity): gives the dissimilarity between users' lists of recommendations


 






## Algorithms:
  - Content-Based filtering: recommend music based on user profile 
  - Collaborative filtering: Recommend music based on similar users 

The two algorithms we will use and compare are the Content-Based Filtering and the Collaborative Filtering. We will use the Content-Based Filtering to recommend music based on a user’s profile. For instance, we will recommend music with the same artist, album, genre and so on, such that we recommend music that has similar content. We will also use the Collaborative Filtering to recommend music based on similar users. For instance, recommending music from a user’s music history. Both of these algorithms will allow us to compare and analyze measure of success. 

## Libraries: 
 - pyspark 
 - pandas
 - numPy
 - sqlite3
 - sklearn
 - matplotlib 
 - seaborn
 
### Features to be extracted:  
  artist_hotttnesss ,
  artist_id, 
  artist_name, 
  artist_location, 
  year
  title, 
  similar_artists, 
  danceability, 
  energy, 
  loudness, 
  tempo,
  time_signature, 
  segments_timbre

  num_songs, 
  artist_id,
  song_id, 
  title, 
  track_id, 
  key,
  albumName, 
  albumId.

