# Spotify Song Popularity Prediction
Machine learning model to predict whether a song will be popular using audio features and metadata

## Project Overview
This project uses different approaches to predict song popularity using machine learning algorithms based on analysis of Spotify's audio characteristics. After analyzing 4,829 songs from different genres and decades, a classification model was developed that predicts whether a song will be popular with an accuracy of 88%.

## Dataset
This project uses two datasets (high and low popularity) combined is from Spotify API which contains 4,829 songs with 28 original features.

## Results
| Model              | Accuracy | AUC      |
|:------------------ | :------- | :------- |
| Random Forest      |  88.47%  |  87.2%   |
| Logistic Regression|  87.03%  |  86.4%   |
| XGBoost            |  88.34%  |  86.5%   |
| Decision Tree      |  86.13%  |  82.5%   |

Among all evaluated models, the Random Forest algorithm demonstrated the best performance.

For the full project, check out the Jupyter notebook titled Spotify.ipynb.
