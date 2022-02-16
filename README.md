# Bigdata Project (Team - 21)
# Music Recommendation System

## Dataset and data models: 
The Million Song Dataset(http://millionsongdataset.com/) will be used in this project. It consists of two dataset, 1 million songs and 1 million users. The dataset containing 55 features which we are going to extract some of these features and create our data models as follows: 
- Songs(1M): <Track_id, title, song_id, release, artist_id, artist_name, artist_familiarity, artist_hotttnesss , year>
- Artists(44745): <artist_id>
- ArtistsSimilarity(2201916): <artist_id, artist_id>
- ArtistMBtags(24777): <artist_id, mbtags> 
- MusicBrainzTags(2321): <mbtags>
- ArtistGenre(1109381): <artist_id, genre>
- Users(1M): <user_id, song_id, played_count>

 The song dataset is accessible in two ways, by reading HDF5 hierarchical directories and SQLite database. Aforementioned data models can be created by using pandas and sqlite3 libraries with connecting to SQLite database. 

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
- How can we personalise next-track music recommendations by extracting long-term preference signals from users' long-term listening behaviour, such as favourite   songs or favourite artists?

 
 


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
 - h5py
 - pytables


