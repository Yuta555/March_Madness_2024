# March_Madness_2024
Just for fun. Quick prediction. 

- Used data only from [Kaggle](https://www.kaggle.com/competitions/march-machine-learning-mania-2024/overview).
- This is a binary classification model that takes some factors for two teams and outputs the winning probability of stronger seed's team.
- Took the following features into account in the final model:
    - StrengthDiff: the difference of seeds between two teams. 
    - ConfStrengthDiff: Grouping the conferences into 4 categories (0 - 3) and calculate the difference between the numbers for two teams.
    - EffMarginDiff: the difference of the average Effect Margin in the regular season between two teams.
- Examined the effects of upset-win/lose rate and non-home winning rate in the regular season, but did not include them in the final model because those appeared not to have significant importance.
- It is possible that coach records and the distance from the team's city to the game location would affect the model performance, but I did not have time to try them.

