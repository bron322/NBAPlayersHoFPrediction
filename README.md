# SC1015-Mini-Project

MEMBERS: Lim Jing Jie, Daryl Loh, James Lim

## Problem Statement
Basketball is one of the most popular sports in today's world. For players, one of the their ultimate goals will be to make it into the Hall of Fame. However, determining whether a player will make it to the Hall of Fame is a complex process that involves a few important factors such as their game statistics and their impact on the game. One potential factor that could play a vital role in determining Hall of Fame status is a player's rookie season performance in the NBA. This statement aims to explore whether a player's first year performance in the NBA is a good predictor of their future Hall of Fame induction.

## Practical Motivation
If we figure out important factors contributing to a player's likelihood getting into Hall of Fame, it will be beneficial for players, coaches and even NBA fans. If a player's first-year performance in the NBA is found to be a reliable predictor of their future Hall of Fame induction, it could help teams and coaches make better decisions when selecting and training new players. It can also benefit fans with a way to access a player's potential future success and help them appreciate the player's skills and abilities more. Lastly, for players themselves, understanding the importance of their rookie season can motivate them to strive for the best in achieving their goal of making it into the Hall of Fame.

## About our dataset
* Name: The name of the rookie. (String)
* Year Drafted: The year the rookie was drafted. (Integer)
* GP: The number of games played by the rookie. (Integer)
* MIN: The number of minutes played by the rookie. (Integer)
* PTS: The number of points scored by the rookie. (Integer)
* FGM: The number of field goals made by the rookie. (Integer)
* FGA: The number of field goals attempted by the rookie. (Integer)
* FG%: The field goal percentage of the rookie. (Float)
* 3P Made: The number of three pointers made by the rookie. (Integer)
* 3PA: The number of three pointers attempted by the rookie. (Integer)
* 3P%: The three point percentage of the rookie. (Float)
* FTM: The number of free throws made by the rookie. (Integer)
* FTA: The number of free throws attempted by the rookie. (Integer)
* FT%: The free throw percentage of the rookie. (Float)
* OREB: The number of offensive rebounds by the rookie. (Integer)
* DREB: The number of defensive rebounds by the rookie. (Integer)
* OREB: The number of offensive rebounds by the rookie. (Integer)
* AST: The number of assists by the rookie. (Integer)
* STL: The number of steals by the rookie. (Integer)
* BLK: The number of blocks by the rookie. (Integer)
* TOV: The number of turnovers by the rookie. (Integer)
* EFF: The efficiency rating of the rookie. (Float)

## Models we used
* Logistic Regression
* Random Forest Classifier
* K-Nearest Neighbor
* XGBoost

## Methods we used to resolve the imbalanced dataset
* Undersampling
* Oversampling
* SMOTE

## What did we learn from this project
* We learn to use models outside of our syllabus to predict the outcomes
* We learn different methods to resolve our imbalanced dataset
* We learn to collab with each other using GitHub

## Conclusion

## References
* https://towardsdatascience.com/logistic-regression-using-python-sklearn-numpy-mnist-handwriting-recognition-matplotlib-a6b31e2b166a
* https://www.datacamp.com/tutorial/random-forests-classifier-python
* https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/
* https://www.datacamp.com/tutorial/k-nearest-neighbor-classification-scikit-learn
* https://www.datacamp.com/tutorial/xgboost-in-python
