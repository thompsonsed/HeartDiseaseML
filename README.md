# HeartDiseaseML
Data exploration and analysis using machine learning of the Heart Disease dataset, available as a Kaggle competition.

## Input data

The *data* directory contains the Heart Disease dataset, available from https://www.kaggle.com/ronitf/heart-disease-uci

## Exploring a few different models for understanding causes of heart disease

- Linear classifier
    + A basic example intended as a baseline, using `LinearClassifier`  object from `tensorflow`.
- Boosted tree
    + A boosted decision tree, using `BoostedTreesClassifier` from `tensorflow`.
- Random forest
    + A standard decision tree, using the `RandomForestClassifier` from `sklearn`.

## Visualising the important factors
The *figures* directory contains the visualisations of the different models, including the different decision trees and the importance of different factors under the models.
