# MOVIE-RECOMMENDATION-SYSTEM

## Content-Based-Recommender
Content-based filtering methods are based on a description of the item and a profile of the user's preferences. In this system, keywords are used to describe the items, and a user profile is built to indicate the type of item this user likes. In other words, these algorithms try to recommend items similar to those that a user liked in the past or is examining in the present.

![mih10uhu1464fx1kr0by](https://user-images.githubusercontent.com/88396377/144169577-01fae562-0c82-4a42-bbb9-ec0657db8e75.jpg)

The Movie Database, also known as TMDB, is a database that contains detailed information on over 500,000 movies. The Movies dataframe has links to the movie posters in it, but the vast majority of them are outdated and no longer work. In order to find the poster links, the tmdbsimple library, which acts as a Python wrapper for the TMDB API was used. The ID of the movie is all that it takes to obtain that movie's updated information. The TMDB website has a simple structure to its URLs, therefore getting the link to each movie's page involves taking the base site link and adding the id of the movie, a dash, and the movie title.
