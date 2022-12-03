## Motivation

The creation of this dataset is attributed to Yueming Zhang. The motivation behind the development of this work is explained in the project report:

"Based on the massive movie information, it would be interesting to understand what are the important factors that make a movie more successful than others. So, we would like to analyze what kind of movies are more successful, in other words, get higher IMDB score. We also want to show the results of this analysis in an intuitive way by visualizing outcome using ggplot2 in R.

 
## Composition

The dataset was downloaded from Kaggle. It contains 28 variables for 5043 movies, spanning across 100 years in 66 countries. There are 2399 unique director names, and thousands of actors/actresses. “imdb_score” is the response variable while the other 27 variables are possible predictors.

**Instances:**

Instance - valid - invalid

- color - 5024 - 19
- director_name - 4939 - 104
- num_critic_for_reviews - 4993 - 50
- duration - 5028 - 15
- director_facebook_likes - 4939 - 104
- actor_3_facebook_likes - 5020 - 23
- actor_2_name - 5030 - 13
- actor_1_facebook_likes - 5036 - 7
- gross - 4159 - 884
- genres - 5043 - 0
- actor_1_name - 5036 - 7
- movie_title - 5043 - 0
- num_voted_users - 5043 - 0
- cast_total_facebook_likes - 5043 - 0
- actor_3_name - 5020 - 23
- facenumber_in_poster - 5030 - 13
- plot_keywords - 4890 - 53
- movie_imdb_link - 5043 - 0
- num_user_for_reviews - 5022 - 21
- language - 5031 - 12
- country - 5038 - 5
- content_rating - 4740 - 303
- budget - 4551 - 492
- title_year - 4935 - 108
- actor_2_facebook_likes - 5030 - 13
- aspect_ratio - 4714 - 329
- movie_facebook_likes - 5043 - 0
- imdb_score - 5043 - 0

As can be observed from the above list, some variables have missing values.

The data does not include any confidential information.

## Collection process

The data was acquired from two public sources; IMDB and Facebook.

## Uses

The dataset can be used by researchers looking to advance their understanding of how multiple variables can affect the way films are critically received by a global audience.

There seems to be an dubious hierarchisation of actors in the following instances: "actor_1_facebook_likes", "actor_2_facebook_likes", "actor_3_facebook_likes", "actor_1_name", "actor_2_name", "actor_3_name". It is not clear what the numbers mean here, whether they are ordering the actors by popularity (as perceived by them), if alphabetically, or if by another method. 

## Distribution

The dataset has no copyright or intellectual property license associated to it.

## Maintenance

There is no mention of maintenance at source.
