# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### NAME HERE
Fares Ayadi

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: Add your explanation
the first submission clearly directed me to the importance of feature enginneering
### What was the top ranked model that performed?
TODO: Add your explanation
The top-ranked model in terms of performance was the one where the time data was parsed and all features, including the time-related features, were fully normalized. This model demonstrated superior performance compared to other models, indicating that incorporating normalized time data was beneficial for predicting the target variable.

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: Add your explanation
The EDA (Exploratory Data Analysis) was necessary to explore possible correlations between bike usage and weather conditions. One of the conclusions drawn from the analysis is that the winter season witnesses the least number of bike rentals, which can be attributed to decreased temperatures. The other graphs also provide insights into this relationship.

### How much better did your model preform after adding additional features and why do you think that is?
TODO: Add your explanation
 the difference in accuracy and the resulting score was highly significant (from 1.8 Kaggle score to 0.4). This improvement was clearly understood when we applied one-hot encoding and scaled the features. These preprocessing steps helped to streamline the algorithm's job and ultimately led to a substantial boost in performance.
## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: Add your explanation
my model presented good imporvment when diffrent hyper parameters were tried for the second( add features) and the first (initial) while the hpo showed a small decrease in the score
### If you were given more time with this dataset, where do you think you would spend more time?
TODO: Add your explanation
if i was guven more time i will spend it trying new algorithms in order to find better scores
### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|best quality|high quality|optimize for deployment||1.86412|
|add_features|best quality|high quality|optimize for deployment|0.81534|
|hpo|best quality|high quality|optimize for deployment|0.50121|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: Add your explanation
the best kaggle score i  got after carefull oone hot encoding and feature engineering was 0.46836