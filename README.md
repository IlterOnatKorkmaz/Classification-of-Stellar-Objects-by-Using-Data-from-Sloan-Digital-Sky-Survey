# Classification of Stellar Objects by Implementing Machine Learning Algorithms from Scratch (Using Numpy)

## Table of contents
* [General Information](#General-Information)
* [The Dataset](#The-Dataset)
* [Files Explained](#Files-Explained)
* [Libraries Used](#Libraries-Used)

## General Information
In this project, me (İlter Onat Korkmaz) and my friend Mustafa Yaşar implemented three machine learning algorithms from scratch: Fully Connected Neural Network, Multinomial Logistic Regression and Decision Tree. These algorithms were than trained with a classification dataset.

## The Dataset
The dataset consists of 100000 observations, each composed of 17 features. Each observation has a single class out of three classes (i.e., mutually exclusive). Because the dataset was large, numerical efficiency was a prime concern of ours while implementing the learning algorithms. The dataset can be found at [here](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17). 

## Files Explained

* star_classification.csv                    : The dataset file.
* Feature-Selection-Data-Visualization.ipynb : The implementation of data visualization steps.
* Preprocessing.ipynb                        : The preprocessing steps (feature selection, outlier removal etc.).
* NeuralNetwork.ipynb                        : The implementation of the Neural Network that allows any layer configuration (Similar to Tensorflow 2.0 Sequential Model style).
* LogisticRegression.ipynb                   : The implementation of the Multinomial Logistic Regression.
* Decision Tree.ipynb                        : The implementation of the Decision Tree Classifier.

## Libraries Used
* numpy 1.22.0     
* seaborn 0.11.2
* tqdm 4.62.3
* pandas 1.2.3
* matplotlib 3.4.3
