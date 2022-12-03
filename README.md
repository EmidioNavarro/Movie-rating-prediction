## What is the project?
100 words to explain what your project is about to a general audience. 

## Data

This project uses data acquired from the "IMDB 5000 Movie Dataset", which I accessed thorugh Kaggle (https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset).

The data is presented in a .csv file format and features the following instances:

- color 
- director_name 
- num_critic_for_reviews 
- duration 
- director_facebook_likes 
- actor_3_facebook_likes 
- actor_2_name 
- actor_1_facebook_likes 
- gross 
- genres 
- actor_1_name 
- movie_title 
- num_voted_users 
- cast_total_facebook_likes 
- actor_3_name 
- facenumber_in_poster 
- plot_keywords 
- movie_imdb_link 
- num_user_for_reviews 
- language 
- country 
- content_rating 
- budget 
- title_year 
- actor_2_facebook_likes 
- aspect_ratio 
- movie_facebook_likes 
- imdb_score 

## Model

I selected a k-nearest neighbors algorithm due to its high versatility, high accuracy, and, most importantly, how easy it is to interpret. 

## Hyperparameter Optimisation

To optimise the performance of the model, I used the estimator, param_grid, and, cv, hyperparameters of grid search.

## Results

To perform the evauation of the model, I used the RMSE of the model in each k iteration. The results were plotted on an elbow curve for a better interpretaion:

![plot elbow curve IMDB 5000](https://user-images.githubusercontent.com/114921311/205455038-16f90a27-b4e1-4c77-bc27-9fe08fcf7f13.png)

Here we can see that the best result was achieved in between k-7 and k-9.

## Contact details

Email: emidioxcmnavarro@gmail.com

