---
title: "Machine Learning Projects"
date: 2022-07-22T11:25:05-04:00
description: "My Collection of Projects of Machine Learning Classes"
menu:
  sidebar:
    name: Machine Learning Projects
    identifier: project-9
    weight: 10
tags: ["Data Manipulation", "Data Visualization", "Importing & Cleaning Data", "Programming", "Probability & Statistics", "Machine Learning"]
categories: ["Basic"]
---

My Collection of Projects teaching Machine Learning subject.

Here's a brief description of every project:

### Supervised Classification and Introduction to the Sklearn Tool

The objective of this project is to solve a problem using the algorithms given in the lecture.

* There are positive and negative movie reviews. 1000 of each.
* The goal is, given the text of the review, to determine whether the review is positive or negative.
* For this, KNN and Naive Bayes will be used and compared.

#### Habilities:

- Data Preprocessing
- KNN
- Naive Bayes
- Feature Extraction
- Model Training
- Sentiment Analysis

### Decision Trees and Random Forest

To demonstrate the use of Decision Trees and Random Forests, we use the Iris dataset.

* The characteristics of the Iris data set are analyzed, visualizing the most important characteristics.
* The behavior of each algorithm is analyzed, visualizing its decision space.
* The depth of the trees is adjusted to avoid overfitting.
* Then, with the Decision Tree and Random Forest algorithms, the dataset used in the previous project, *Rotten Tomatoes*, is analyzed, where the sentiment analysis is performed.

#### Habilities:

- Data Preprocessing
- Decision Trees
- Random Forest
- Feature Analysis
- Model Tuning
- Model Training
- Sentiment Analysis

### Logistic Regression

We continue to use the _Rotten Tomatoes_ dataset to rank positive and negative reviews. 

* As in the previous projects, we extract the content of the files, get a bag of words representation of the dataset, and begin to train the model.
* This time, we visualize the Confusion Matrix to assess the performance of the algorithm and show how to test the prediction of the algorithm in a specific example.
* In addition, we use the coefficient of the Logistic Regression model to check the most important features.
* We plot the most important positive and negative words.
* We check different techniques that would make the model better: add bigrams and decrease the probability threshold of Logistic Regression.

#### Habilities:

- Data Preprocessing
- Logistic Regression
- Feature Analysis
- Model Tuning
- Model Training
- Sentiment Analysis
- Natural Language Processing

### Support Vector Machine and Cross Validation

We work with a dataset that contains information about patients (*gender, marital status, smoking status, age, etc.*) with the aim of predicting whether they are likely to have a heart attack (*stroke*). In addition, the *doctor* characteristic is artificially incorporated, which represents the doctor who collected the data, which will later be used to group the data.

* We clean our data encoding some categorical variables and checking for NaN values.
* We use Support Vector Machine with this dataset to classify patients that could have a heart attack.
* AUC metric is introduced, good for the imbalanced datasets, like the one we were using.
* The concept of *Baseline* is used, to efficiently compare models and different partition methods to use with Cross Validation are visualized.
* Different algorithms are compared using correct evaluation techniques.

#### Habilities:

- Data Cleaning
- Support Vector Machines
- Model Training
- Model Evaluation
- Cross Validation

### Clustering Algorithms: K-Means y DBSCAN

In this project, we explore how *K-means* and *DBSCAN* work.

* We show various *K-means* issues and provide solutions to address those issues, including cluster quality analysis.
* We study how to artificially generate datasets with Sklearn, visualizing the data distribution to apply clustering.
* K-means algorithm is explained, and the predictions of the training data and clusters centers are shown.
* We show how to make new predictions.
* A few problems and possible solutions to K-means are explained.
* Different clusters metrics are used to check the efficiency of K-means, outlier detection is done, and data transformations are used.
* Finally, DBSCAN is introduced as a solution to most K-means problems.

#### Habilities:

- K-Means
- DBSCAN
- Model Training
- Model Evaluation

### Dimension Reduction Algorithms

High-dimensional data present a challenge for statistical models. Fortunately, much of the data is redundant and can be reduced to a smaller number of variables without losing much information. Typically, we use dimensionality reduction in machine learning and data exploration. In machine learning, we use it to reduce the number of features. This will decrease computational power and possibly lead to better model performance. Similarly, we can use dimensionality reduction to project data into two dimensions. Such visualization can help us detect outliers or data clusters.

In this project, we will compare four different methods to accomplish such a task: (1) Principal Component Analysis (PCA), (2) Kernel Principal Component Analysis (kPCA), (3) Linear Discriminant Analysis (LDA), and (4) t-distributed Stochastic Neighboring Entities (t-SNE). For this, we will use the Iris dataset provided within `scikit-learn`, which consists of 150 samples, each with 4 features.

* First, the distribution of the elements in the datasets is analyzed.
* We begin using PCA, defining when this algorithm is a good idea to use.
* Then, the same is done with Kernel PCA, LDA, and t-SNE.
* Finally, PCA and LDA are compared and used as preprocessing steps of KNN.

#### Habilities:

- Principal Component Analysis (PCA)
- Kernel Principal Component Analysis (kPCA)
- Linear Discriminant Analysis (LDA)
- t-distributed Stochastic Neighboring Entities (t-SNE)
- Model Training
- Model Preprocessing

### Neural Networks

* This notebook starts with the visualization of several activation functions.
* Then, the `fashion_mnist` Keras dataset is loaded, a dataset containing 15000 images, every pixel is represented with 255 pixels, and there is a total of 9 classes.
* Several techniques are used to unzip the manually downloaded files.
* Afterward, the distribution of the dataset is analyzed, and the images are processed to show them.
* A Multi-Layer Perceptron (MLP) is created to classify the images of this dataset using Keras.
* Different properties of this model are shown.
* Then, the model is trained, and information related to the training process is plotted.
* Finally, we evaluate this image classifier, and some images and its prediction are plotted it.
* Afterward, MLP is used in a Regression Problem, predicting the prices of houses in the dataset *California housing*.
* More complex models are created using the Functional API of Keras, and different tools to save and load Keras models are used.

#### Habilities:

- Deep Learning
- MLP
- Keras
- Data Visualization
- Model Training
- Image Classification
- Price Prediction

### Resources
[GitHub Link](https://github.com/lorainemg/cp-ml)