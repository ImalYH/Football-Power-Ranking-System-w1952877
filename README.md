# Football-Power-Ranking-System-w1952877
-My goal is to develop a Football Power Ranking System to predict the result of matches in the Premier League through machine learning.
Using historical data the project applies machine learning through CatBoost to make Premier League football match score predictions. The model computes precise score predictions by taking into account current team forms alongside home field advantage and past match histories between teams.

-Features

1.The model determines the anticipated outcome of match scores.
2.The model implements CatBoost as its gradient boosting model.
3.Analyzes historical match data (2016-2024).
4.The system incorporates examinations of home field benefits together with referee effects and team statistical patterns.

-Dataset

The Premier League matches from 2016 to 2024 constitute the dataset.

-The predictive model implements CatBoost Regressor as its core machine learning algorithm.

Iterations: 500 decision trees
Depth: 6 (Balanced complexity)
The learning rate was set at 0.1 to achieve both faster training speed and higher accuracy performance.
Loss Function: MAE (Mean Absolute Error)

Two separate models are trained
The Home Goal Predictor function predicts the number of goals that the home team will score.
This system generates predictions for away team goals.




