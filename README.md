# Project Overview
## Provided with information about passengers on the Titanic, create a machine learning model that can accuractely guess if they survived or not.

## Link to [Jupyter Notebook](https://github.com/hismith142/Titanic_Data_Science/blob/main/Titanic%20Survival%20Predictions.ipynb)

## Task 1: Identify Features
Using a correlation heatmap from seaborn I identified that socioecenomic status is very strongly correlated to survival, as well as age and sex to a lesser degree.

## Task 2: Distribution Normalization
Once I had identified the important features, I ensured that the distributions of said features would mirror eachother in the training and testing data.

## Task 3: Data Pipeline
I created a data pipeline that would 'impute, encode, and drop' information from the training data to format it for model creation

## Task 4: Optimizing Model
Using a grid search, I ran a RandomForestClassifier model through different combinations of parameters to identify the optimal settings for this dataset.

## Task 6: Running Model
I then ran the model through an 80/20 split from the train.csv data, and the model had roughly 81% accuracy.

## Task 6: Validating Results
Now that I was ready to officially 'grade' the model, I let it train with as much data as I had access to (the whole train.csv file). The final grade against the 'test.csv' reflected my findings.
