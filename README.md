# USA-Accidents-Severity-Predictions
This is the final project of the course Probability and Statistical Inference for Data Science (Stat581) at Rutgers, the State University of New Jersey, New Brunswick.

This is the notebook that contains our analysis and results. We used a dataset from kaggle which is available [here](https://www.kaggle.com/sobhanmoosavi/us-accidents) for severity predictions of accidents.

Performed feature specific preprocessing like converting string features to categorical features, removing duplicate datetime features, and extracting meaningful features from datetime feature etc.

Removed Nans from some features. Filled Nans with forward filling, mean/median value imputation etc. 

Performed EDA using different plots like countplot, histogram, heatmap of correlation etc, for various features.

Experimented with five different models (Random Forest, Neural Network, AdaBoost, GradientBoost, XGBoost) and achieved best test accuracy of 80% using XGBoost.

Experimented and found out the most relevant features which affected severity of accidents.