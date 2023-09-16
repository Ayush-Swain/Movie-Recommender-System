# Movie-Recommender-System
An Interactive Jupyter Notebook where You can get two kinds of recommendations for the movie you input:-
1: Movies with similar names
2: Movies recommended by users similar to You.

# Instructions
You can run the Jupyter Notebook in your own environment and go through the project.
To run the notebook, You need to install dependencies mentioned in the handy requirements.txt file.
The interactive environment is created by using ipywidgets.
Go ahead, use it to get a few recommendations for your favourite movies
# **************************************************
Or-else You can go through a brief of the project in the next few lines with a couple of images. 

The First objective is achieved by making use of TF-IDF Vectorization.
A Process in which the most common words are ignored and the words which play more significance in the title of the movies are compared to get the desired result. It done by finding the cosine_similarity between the vectors of the input title and the titles in the dataset.

![recommendations based on the words used in the title](https://github.com/Ayush-Swain/Movie-Recommender-System/assets/90006132/d7e82296-e679-4c83-a2d6-2851a85ff02a)

The Second Objective is achieved By first finding all the users who have watched the input movie and have rated it > 4. Then I have found out which others movies these users have watched and rated > 4. To solve the issues of the most universally liked movies, we compare the ratings of the movies in our similarity bucket with their overall ratings by all users in the dataset and only pick movies with the highest ratio (Implies better recommendations).

![recommendations based on user popularity](https://github.com/Ayush-Swain/Movie-Recommender-System/assets/90006132/32ae96c0-6480-4446-ae20-d1685d944110)

To get the info about datasheet refer to the Dataset Readme file!! 
# Thanks
