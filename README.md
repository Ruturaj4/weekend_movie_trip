Weekend movie trip
==============================

Blockbuster or art film?

Author: Ruturaj Kiran Vaidya

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

### Before Getting Stated

If you are only interested in looking at the notebook then go to (There are notebook rendering problems in github ecosystem, in particularly with plotly):

https://nbviewer.jupyter.org/github/Ruturaj4/weekend_movie_trip/blob/master/notebooks/1.0-rkv-weekend-movie-trip.ipynb

All the graphs are plotted using `plotly`.

### Aim
<ul>
<li>Obtain additional value using exploratory data analysis by formulating ideas on combining user ratings and tags</li>
<li>Using clustering algorithms to determine the type of movies which can be recommended to the user</li>
</ul>

### Dataset used

Movielen: https://grouplens.org/datasets/movielens

Particular dataset link: http://files.grouplens.org/datasets/movielens/ml-latest-small.zip

The dataset is divided into movies, ratings, tags and links. We don't need links (basically it contains imdb and rotten tomatoes db ids).

### Discussion

First, I imported the data sets. Second, I analysed those to get relevant values. For e.g. I removed unwanted features, I calculated mean of ratings of each movie based on user "ratings" dataset, etc. I also did some analysis on "tags" dataset and decided not to consider this during clustering. I came to this conclusion, because - the unique movies with tags are significatly lower than those without tags. Hence I think that it is reasonable not to consider this data for clustering (note that I may be wrong here). Also, I thought that splitting genres 

### License

<b>MIT</b>
