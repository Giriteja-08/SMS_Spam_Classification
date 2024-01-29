# SMS Spam Classification

## by C Giri Teja

## About

The Spam Classification project aims to build a machine-learning model for accurately classifying emails as spam or non-spam. This project is motivated by the need to enhance email filtering systems and reduce the impact of unwanted communication.

## Features

- Machine learning-based spam classification
- Data cleaning and preprocessing techniques
- Visualizations to better understand the dataset
- Model analysis and techniques for improvement
- Best performance model with a precision value of 1

## Getting Started
Importing the libraries and choosing a dataset 

## Data Pre-processing
Cleaning text data involves removing the words that are used to form a sentence(eg: is, am, of, etc). You can also perform one hot encoding or Label encoding on data at this point. Libraries such as nltk(natural language tool kit) are handy while making these changes to text data.

## Data Visualizations
Visualizing data can provide us with useful insight into data. In this case, we observe that spam messages usually have a higher number of characters used in them. Also extracting the most used words and other visualizations would be useful to have as well.

## Model Building
Naive Bayer models are known for their comparatively higher performance with textual data. As we are sure about the data distributions at this point comparing all the models would be preferable.

## Model Evaluation and Improvements
Hyperparameter tuning or Fine-tuning helps us determine the best parameters for our model. Confusion Matrics and the precision and accuracy values are taken into consideration for selecting the best model. In this case, precision is the key value for determining the best model.
