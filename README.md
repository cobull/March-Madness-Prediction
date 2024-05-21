# March-Madness-Prediction

### Description

An analysis of the predictive capabilities of Decision Trees and Random Forests when applied to predicting the number of wins each tournament team will acheive during the 2024 March Madness tournament. The Decision Tree and Random Forest models were trained on a dataset containing nine years worth of regular season college basketball statistics (2014-2023, excluding 2020), and annotated with the number of wins each team acheived during their respective year's tournament. The test dataset contained regular season college basketball statistics for the 2024 season and the number of wins each team acheived during the 2024 March Madness tournement. The features included statistics such as seed, win-loss percentage, points per game, fouls, three point shooting percentage, etc. The labels were the number of wins each team acheived during the respective March Madness tournament. Grid searches were performed to find the best combination of hyperparameters. The two best Decision Tree models and two best Random Forest models were evaluated on the test set, and each model performed better than chance.

### Dependencies

Python 3.12.2
Pandas 2.2.1
Scikit-learn 1.3.0
Numpy 1.26.4
Matplotlib 3.8.0
Joblib 1.2.0
Graphviz 2.50.0

### Important

Please note the file directory structure in the second code cell of each notebook.
