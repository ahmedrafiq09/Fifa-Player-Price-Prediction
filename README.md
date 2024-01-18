# Fifa-Player-Price-Prediction
The "FIFA Player Price Prediction" project is a comprehensive exploration into predicting the monetary value of football players and classifying whether a player is a goalkeeper or not. 
# Details
The project begins by framing the problem, highlighting the primary objective of predicting player values based on a diverse set of attributes and goalkeeper-specific statistics. The dataset, sourced from "player_stats.csv," is thoroughly explored and visualized using the Pandas library, revealing key player information such as height, weight, age, skills, and financial values.


The player value prediction model employs feature selection, focusing on essential attributes like height, weight, age, and talent markers. A Decision Tree Regressor is chosen for its flexibility in capturing non-linear patterns and feature interactions. The model is trained on the dataset, learning patterns to predict player values, and evaluated using metrics such as Mean Squared Error (MSE) and R-squared.
Simultaneously, a goalkeeper classification model is developed by creating a binary target variable based on goalkeeping attributes. A Decision Tree Classifier is selected for its effectiveness in binary classification tasks, and the model is trained and evaluated using accuracy and a confusion matrix.
