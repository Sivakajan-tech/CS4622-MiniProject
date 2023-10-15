# CS4622-MiniProject


## Project Description
**Dataset**: AudioMNIST is the dataset used to create the features.

Wav2vec base is commonly used as a feature extraction model. There are 12 transformer layers in the wav2vec base model. For this project features are extracted from the last 6 transformer layers (transformer layer 7 to layer 12). For each layer separate kaggle competition is created. Each train.csv file provided in the competition contains layer features and corresponding speaker, age, gender, and accent labels.

* Label 1 - Speaker 
* Label 2 - Age
* Label 3 - Gender 
* Label 4 - Accent

The project is about building classifier models for predicting all 4 labels individually using features in both training and validation CSV files provided in the competitions.
Also consists of data pre-processing, feature engineering, hyper-parameter tuning, dimensionality reduction, cross-validation, and other techniques to improve the classifier accuracy. 
This repository consists of all the works for all 6 layers.

