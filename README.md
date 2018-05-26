# EMOTION PREDICTION

This project implements the machine learning model, naive bayes classifier to predict the emotion in a statement. 

2 Jupyter notebooks are provided. The 'Sentiment Prediction.ipynb' contains the code for emotion prediction and 'Data Viz.ipynb' contains code for data visualization.

## DATASET

The dataset is available as 'dataset.csv'

The data is divided into 4 classes or emotions. The classes are

1. Happy
2. Sad
3. Angry
4. Sarcastic

This data was collected by scrapping the web for statement based on the emotion.

The dataset is pretty small and affects the accuracy of the classifier. The point of the project was to implement machine learning models to train and predict emotions. More data can be collected to increase the accuracy of the machine learning model. 

The shape of the dataset 727 X 2.

The amount of data corresponing to each class is as follows:

1. Happy: 171
2. Sad: 212
3. Angry: 82
4. Sarcastic: 258

It is clear that the data is not even with very few data correspoding to the angry class. This dataset can be cleaned to make the data more even or more data can be collected. 

## DEPENDENCIES

1. nltk
2. pandas
3. matplotlib
