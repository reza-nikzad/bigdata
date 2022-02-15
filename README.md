# bigdata-project-team21
Music-recommendation-system

Dataset: http://millionsongdataset.com/tasteprofile/
 - MillionSongSubset
 - TRIPLETS FOR 1M USERS
 
Data preprocessing: 
 - Main characteristics and relative features to our questions: 
 - Pruning the dataset.(removing empty rows)
 - Removing musics from the user dataset which are not in the dataset

Questions: (Recommending music)
 1- What type of genre a user would like to be recommended? 
  user -> find users with similar plaied music to the user -> recommend most common music between users  
 2- What type of album_name a user would like to be recommended? 
 3- What type of artist_name a user would like to be recommended?
 4- What is the most similar user between other users and recommond all the song of that user? 
 5- 
 
 
 
 
 What genre, song, artist or album would a user prefer to be recommended?
How can we use the data set to identify users with similar musical preferences?
What are the qualities that consumers want to see in their playlists?
What is the best way to extract item features from a data set?
How can metadata features be linked with patterns in users' listening behaviour?
What is content-based filtering, and why should we use it?
What is collaborative filtering, and why should we use it?
How can we personalise next-track music recommendations by extracting long-term preference signals from users' long-term listening behaviour, such as favourite songs, favourite artists, or favourite themes?

 
 


The metric to measure the accuracy: 
 - Mean average precision at k (MAP@K)
 - 
 - 

The class of models to be applied to the dataset:
 -





Algorithms:
  - Content-Based filtering: recommend music based on user profile 
  - Collaborative filtering: Recommend music based on similar users 

Libraries: 
 - pyspark 
 - panda
 - numPy
 - 
 
Features to be extracted:  
  get_artist_hotttnesss , get_artist_id, get_artist_name, get_artist_location, get_year
  get_title, get_similar_artists, get_danceability, get_energy, get_loudness, get_tempo
  get_time_signature, get_segments_timbre

  get_num_songs, get_artist_id, get_song_id, get_title, get_track_id, get_key
  we need albumName and albumId

