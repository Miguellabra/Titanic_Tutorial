# Titanic_Tutorial
This project uses one of Kaggle's most popular datasets to implement and compare various machine learning algorithms. The goal is to select the algorithm with the highest accuracy and then fine-tune the model.
The project consists of the following sections:
* Load libraries.
* Read the data.
* Explore the data.
* Visualization.
* Data preprocessing.
* Feature engineering.
* Model Selection.
## Problem Description
The main objective in this problem is to predict whether a passenger will survive to the titanic catastrophe based on some features like sex, age, cabin, embarked, among others. In this problem the submission file should most be a two column dataset, one containing the passenger ID and the other must have 1 or 0, depending on if the passenger didn´t survived 0 and 1 if the passenger survived.
## The approach
This project considers two ways to tackle the problem. The first, data focused aproach, meaning that I ensure the quality of data, reason why I consider 4 data categories. And the model focused approach; after creating 4 different data categories, these data sets are proccesed by different algorithms.
## Results
In the image below, accuracies corresponding to each of the machine learning models are shown, by data categories. In this first image, I consider splitting the data using the common function "train_test_split()" included in scikit-learn library. As we can see, the accuracies are good, with data category 1 appearing to be the most model-friendly, as it has the highest mean accuracy (with no great difference). However, as an individual model, the best performance was achivied by the Naive-Bayes algorithm in all four data categories. It is important to highlight that in data categories where features were normalized, algorithms like k-neighbohrs classifier improved their accuracy due to their sensitivity to feature scaling.

![Accuracy for each data category, considering normal splitting](images/models_ss.png)
