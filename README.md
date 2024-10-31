Project Overview
This project contains two machine learning models built for classifying outcomes based on match history data. Each model uses a different approach:

Keras Model - A neural network built using Keras.
Random Forest Model - A traditional machine learning approach using a Random Forest classifier.
Files
Keras_Model.ipynb:

Purpose: Implements a deep learning model for multi-class classification using Keras. The model classifies match results into categories (e.g., win, loss, draw).
Contents:
Data preprocessing, including handling missing values, one-hot encoding, and feature scaling.
A neural network with two dense layers using ReLU activation and softmax for output.
Model training with accuracy metrics and visualization of training history.
Evaluation with a confusion matrix and classification report.
Dependencies:
Keras, pandas, scikit-learn, matplotlib
Random_Forest_Model.ipynb:

Purpose: Uses a Random Forest classifier for match result classification.
Contents:
Initial data exploration to understand match distributions.
Basic setup for preparing data for the Random Forest model (modeling section to be completed).
Dependencies:
pandas, scikit-learn
Requirements
Python 3.x
Required libraries: pandas, scikit-learn, keras, matplotlib
Usage
Clone the repository and navigate to the folder.
Open either .ipynb file in Jupyter Notebook or Jupyter Lab.
Run each cell sequentially to preprocess data, train the models, and evaluate performance.
