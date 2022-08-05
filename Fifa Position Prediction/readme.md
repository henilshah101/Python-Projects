Objective: The goal was to be able to accurately predict the positions(GoalKeeper, Forward, Midfielder etc.) of the player based on rest of the relevant features

Data Summary:
The Fifa Dataset consists of 18207 rows and 89 columns, each row corresponds to a unique player so we have 18207 players and each column corresponds to a unique feature of the player. Some features are descriptive (Name, Age etc.) and some are performance scores of their skills (dribbling, shooting etc.).

Process:
I start with data exploration steps and derive useful information and patterns relevant for feature engineering, handled the missing values by elimination and imputation. Performed feature engineering to select the top features that were useful for the prediction of player positions. The exploration steps are very elaborate as this project helped me hone the visualization skills. Algorithms used to compare results were CART, Random Forest, Gradient Boosting, XGBoost. Achived a testing accuracy of 93%. 

Presentation : https://docs.google.com/presentation/d/1rK_jn8--xOUU_zid7mB18_7zPit50gtKcVv-5DhdkK0/edit#slide=id.p
Data Source : https://www.kaggle.com/datasets/karangadiya/fifa19
