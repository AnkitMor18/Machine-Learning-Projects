# PUBG Finish Placement Prediction Project

This project focuses on predicting players' finishing placements in the game PUBG (PlayerUnknown's Battlegrounds) based on their final statistics.

## Dataset Source
The dataset used for this project is available at [Kaggle - PUBG Finish Placement Prediction](https://www.kaggle.com/competitions/pubg-finish-placement-prediction/data).

## Project Overview
The goal achieved in this project is to create a model that predicts players' finishing placement on a scale from 1 to the maximum placement in the game.

## Project Content - `PUBG Finish Placement Prediction.ipynb`
The notebook covers the following steps:

1. Preprocessing of Data
2. Outlier Detection and Removal
3. Standardization
4. One-Hot Encoding
5. Utilizing TensorFlow's Keras for Artificial Neural Network (ANN)
6. Implementation of Dropout and Earlystopping Techniques to Avoid Overfitting
7. Prediction on Test Data with an achieved Mean Absolute Error (MAE) of 0.0965

Additionally, a Google Colab notebook was used to employ PyCaret. PyCaret was utilized to compare several regression models, fine-tuning them, and achieving the lowest error possible.

The notebook contains an in-depth analysis of the models and their performance.
