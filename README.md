# Bigdata Project (Team - 21)
## Music Recommendation System

Dataset: http://millionsongdataset.com/
 - MillionSongSubset
 - TRIPLETS FOR 1M USERS
 
# Data preprocessing: 
 - Main characteristics and relative features to our questions: 
 - Pruning the dataset.(removing empty rows)
 - Removing musics from the user dataset which are not in the dataset

# Research Questions: (Recommending music)

 1- How to address cold start problem in collaborative filtering techniques?  
 2- How to find similar users from dataset in collaborative filtering techniques?
 3- How to recommend music to new users in Content-based algorithm? 
 4- 
 
 
 
 
- What genre, song, artist or album would a user prefer to be recommended?
- How can we use the data set to identify users with similar musical preferences?
- What are the qualities that consumers want to see in their playlists?
- What is the best way to extract item features from a data set?
- How can metadata features be linked with patterns in users' listening behaviour?
- What is content-based filtering, and why should we use it?
- What is collaborative filtering, and why should we use it?
- How can we personalise next-track music recommendations by extracting long-term preference signals from users' long-term listening behaviour, such as favourite   songs, favourite artists, or favourite themes?

 
 


The metric to measure the accuracy: 
 - Mean average precision at k (MAP@K)
 - 
 - 

The class of models to be applied to the dataset:
 -





# Algorithms:
  - Content-Based filtering: recommend music based on user profile 
  - Collaborative filtering: Recommend music based on similar users 

# Libraries: 
 - pyspark 
 - pandas
 - numPy
 - sqlite3
 
# Features to be extracted:  
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

