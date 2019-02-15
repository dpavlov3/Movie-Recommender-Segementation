### Executive Summary: 
MovieLens datasets were used in order to build out a content based recommender and collaborative based movie recommenders. Id addtion to recommenders I focused exploratory data analysis in order to get a better understanding into genres, user ratings, movie complexity, and how these features change over time. Finally, principal component analysis was used to take a deeper dive to segment genres, decades, and genomes and was able to explain 50% of all features variabilities into eight distinct categories.


### Data Collection: 
Data was gathered from [MovieLens](https://grouplens.org/datasets/movielens/), 10M and 20M dataset was used for feature based recommender and collaborative based recommenders. The data for collaborative based recommender was decreased to 3.1M review due to limitation of the computing power, selecting users who's user_id number was evenly divisible 3 in order to get the best sample of population.

Full data description can be found [here](http://files.grouplens.org/datasets/movielens/ml-20m-README.html).


### Methodology & Notebooks Overview: 
* Part 1 - Content Based Recommender - Exploration and Cleaning
* Part 2 - Content Based Recommender - Cleaning II 
* Part 3 - Content Based Recommender - EDA
* Part 4 - Content Based Recommender - Recommender
    * Pairwise Distance - Cosine
* Part 5 - Content Based Recommender - Segmentation
    * Princincipal Component Analysis
* Part 6 - Collaborative Based Recommender - Cleaning Data III
* Part 7 - Collaborative Based Recommender - Items Based
    * Pairwise Distance - Cosine
* Part 8 - Collaborative Based Recommender - User Based

_Note: All statistical analysis was performed on a t2.2xlarge AWS instance._