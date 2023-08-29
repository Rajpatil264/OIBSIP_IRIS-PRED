# OIBSIP_IRIS-PRED
This code is a Streamlit app that uses a RandomForestClassifier to predict Iris flower species based on user-inputted measurements. It displays model accuracy, scatter plots of actual vs. predicted classes, and allows users to input measurements for real-time predictions.
# Iris Flower Species Classifier

This repository contains a Streamlit app that utilizes a Random Forest model to classify Iris flowers into three distinct species: Setosa, Versicolor, and Virginica. The application also provides insights into the dataset and allows users to make predictions based on sepal and petal measurements.

## Table of Contents

1. [Introduction](#introduction)
2. [Analysis Section](#analysis-section)
3. [Streamlit App Section](#streamlit-app-section)
4. [Conclusion](#conclusion)

## Introduction
This Streamlit app employs a Random Forest model to classify Iris flowers based on their sepal and petal measurements. The Iris dataset consists of sepal length, sepal width, petal length, and petal width features for 150 samples, each belonging to one of the three species: Setosa, Versicolor, and Virginica.

## Analysis Section
The script begins by importing necessary libraries and loading the Iris dataset using the `load_iris` function from the `sklearn.datasets` module. The dataset is preprocessed, scaled using `MinMaxScaler`, and split into training and testing sets. A Random Forest classifier is trained using the training data.

## Streamlit App Section
The Streamlit app showcases information about the Iris dataset, including its significance and the distinct species it contains. It displays an image related to Iris flowers and provides an introduction to the app's functionality. The app includes the following sections:

- **Model Accuracy:** Displays the accuracy of the Random Forest model on the testing data.
- **Graph Section:** Visualizes the actual and predicted classes using scatter plots.
- **Prediction Section:** Allows users to input sepal and petal measurements and predicts the corresponding Iris species. It also provides a bar chart showing the probabilities of each species prediction.

## Conclusion
This Streamlit app offers a user-friendly interface to predict Iris flower species using a Random Forest model. It provides insights into the Iris dataset and enhances understanding of machine learning classification tasks.

Created with expertise by Rajvardhan 

For any inquiries or feedback, please feel free to reach out to me at raj2003patil@gmail.com.

**Note:** Ensure you have the required libraries, Streamlit, and a compatible Python environment to run this app successfully.
