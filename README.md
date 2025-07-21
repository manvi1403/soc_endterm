# soc_endterm
The filter_data.ipynb notebook is responsible for extracting and processing important textual features from the dataset. The movie_recommen.ipynb notebook then takes these processed features, converts them into vectors using CountVectorizer, and calculates similarity scores between movies using cosine similarity.

A movie name is entered through a widget. If the movie is not found in the dataset, it suggests movies with similar titles. If the movie is found, it generates recommendations based on similarity scores computed from a combined column of overview, genre, and keywords. These recommended movies are then sorted by popularity, and the system displays the top 10 recommendations along with the input movie name.
