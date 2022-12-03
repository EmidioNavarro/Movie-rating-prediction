# Inputs:

**Instance - Number of valid samples**

- color                        - 5024
- director_name                - 4939
- num_critic_for_reviews       - 4993
- duration                     - 5028
- director_facebook_likes      - 4939
- actor_3_facebook_likes       - 5020
- actor_2_name                 - 5030
- actor_1_facebook_likes       - 5036
- gross                        - 4159
- genres                       - 5043
- actor_1_name                 - 5036
- movie_title                  - 5043
- num_voted_users              - 5043
- cast_total_facebook_likes    - 5043
- actor_3_name                 - 5020
- facenumber_in_poster         - 5030
- plot_keywords                - 4890
- movie_imdb_link              - 5043
- num_user_for_reviews         - 5022
- language                     - 5031
- country                      - 5038
- content_rating               - 4740
- budget                       - 4551
- title_year                   - 4935
- actor_2_facebook_likes       - 5030
- aspect_ratio                 - 4714
- movie_facebook_likes         - 5043

## Outputs:

- imdb_score                   - 5043

## Model architecture:

The model implements a K-nearest neighbors algorithm that is optimised with grid search.

## Performance

RMSE is used to evaluate the model's performance. The results are plotted in an elbow curve.

## Limitations

The model struggles with very large datasets and in high dimensional spaces.
