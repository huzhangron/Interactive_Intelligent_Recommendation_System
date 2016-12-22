The data used in this project was obtained from the MovieLens data set
(http://movielens.org). This dataset consists in a set of 5-star rating given by users on
movies aired for the last 20 years. The purpose is to build a movie recommendation
system to the most active users.

To simplify the dataset used in this project is a subset of the original dataset1 for the last
6 years. Users were selected at random for inclusion. Each user is represented by an id,
and no other information about the users is provided.
You will find in moodle three datasets:
. train.csv:
. test.csv
. movies.csv

The datasets train.csv and test.csv contain the rates given by the users. Each line
of both files after the header row represents one rating of one movie by one user,
and has the following format:
 userId, movieId, rating, timestamp
Ratings are made on a 5-star scale, with half-star increments (0.5 stars - 5.0

The file movies.csv contains the movie information. Each line of this file after the
header row represents one movie, and has the following format:
 movieId, title, genres
Genres are a pipe-separated list, and are selected from the following types:
Action, Adventure, Animation, Children's, Comedy, Crime, Documentary,
Drama, Fantasy, Film-Noir, Horror, Musical, Mystery, Romance, Sci-Fi, Thriller,
War, Western and (no genres listed).
