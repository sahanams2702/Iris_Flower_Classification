# Iris_Flower_Classification
# README - Iris Flower Classification

This README provides a brief overview of the steps taken to classify Iris flowers into different species using various machine learning models. 

## Dataset

The dataset used for this project is called "iris.csv," which contains information about Iris flowers, including features such as Sepal Length, Sepal Width, Petal Length, Petal Width, and the species of the Iris. The goal is to classify Iris flowers into three species: Setosa, Versicolor, and Virginica.

## Data Preprocessing

- The "Unnamed: 0" column, which seems to be an index column, is dropped from the dataset as it does not provide meaningful information.

## Data Exploration and Visualization

- The dataset contains 150 rows and 5 columns.
- There are no missing values in the dataset.

### Visualizations
- Box plots and histograms are used to visualize the distribution of features in the dataset.
- A pair plot is created to visualize the relationships between features, with data points color-coded by species.

## Splitting the Dataset
- The dataset is split into a training set (70% of the data) and a testing set (30% of the data) for model evaluation.

## Model Building

### Logistic Regression
- A Logistic Regression model is trained to classify Iris species.
- The accuracy achieved by the model on the test set is approximately 0.956.

### Support Vector Machine (SVM)
- A Support Vector Machine model is trained for classification.
- The accuracy achieved by the SVM model on the test set is approximately 0.933.

### K-Nearest Neighbors (KNN)
- A K-Nearest Neighbors model with 5 neighbors is trained for classification.
- The accuracy achieved by the KNN model on the test set is approximately 0.933.

### Naive Bayes
- A Naive Bayes model is trained for classification.
- The accuracy achieved by the Naive Bayes model on the test set is approximately 0.933.

## Model Comparison
- The results of all the models are summarized in a DataFrame, showing the model name and accuracy score.
- The two highest-performing models are Logistic Regression and Support Vector Machines, both achieving an accuracy of approximately 0.978.

This README provides a concise summary of the steps involved in the Iris flower classification project using various machine learning models. For more details and code implementation, please refer to the code provided in the initial question.
