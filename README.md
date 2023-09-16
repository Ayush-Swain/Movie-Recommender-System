# Movie-Recommender-System
An Interactive Jupyter Notebook where You can get two kind of recommendations for the movie you input:-
1: Movies with similar names
2: Movies recommended by users similar to You.

The First objective is done by making use of TF-IDF Vectorization.
A Process in which the most common words are ignores and the words which play more significance in the title of the movies are compared to get the desired result. It done by finding the cosine_similarity between the vectors of the input title and the titles in the list.
