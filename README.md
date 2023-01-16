# unsupervised ML -  Clustering similar songs to playlists on spotify - WBS PROJECT 4

#### In this repository the main work is in one jupyter notebook.
#### The data Given contains songs (1000 or 5000) which are to be clustered into playlist of at most 250 and at least 50 "similar"
#### songs. The word similar is the clue of the task, as dfining similarity is part of the task. In this case the similarity
#### using different features of the songs (as given by spotify) and calculating the distance in this of songs relative to this features.
#### each feature is a dimension and we use distance functions to calculate a degree of similarity

#### you will find the notebook divided in 4 scripts
### 1. data exploration looking for similarities (euclidean) among the data and a hardcoded dimension reduction based on correlation
### 2. the data modeling with k means (unsupervised ML) using the silouette scores to find the most appropriate number of clusters
### 3. the visual cluster exploration with code
### 4. the import of clusters to real spotify playlists using spotify's own api - I relied on y youtube video which is linked in the code

### for a video runthrough through this code and the results on spotify please check the videos on the following link
https://drive.google.com/drive/folders/1MOce9T3XbDTHWBFmptRrRhjmPoc4YLBm?usp=sharing
