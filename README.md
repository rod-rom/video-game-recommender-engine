# Video Game Recommendation System

In the trend of increasing number of newly released games every year, the gamers need help with finding the games of their own interest rather than searching through a giant catalog of games that don't interest the user. Therefore, this project presents a recommeder system providing similar games based on users' interest.

## Datasets
Two datasets were used for the recommender systems.

1. [Steam store games dataset](https://www.kaggle.com/datasets/nikdavis/steam-store-games)
    - Used for content based filtering

2. [Steam video games dataset](https://www.kaggle.com/datasets/tamber/steam-video-games)
    - Used for collaborative filtering

## Methodology
### Content Based Filtering
Content Based filtering is when you use items to recommend other items simillar to what a user may like based on previous actions or explicit feedback.
### Collaborative Filtering
Collaborative filtering relies on the preferences of similar users to offer recommendations to a particular users. Since the amount of data was limited I decided to implement item-item collaborative filtering.