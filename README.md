# Spam-Message-Classification
This project focuses on detecting and classifying text messages as spam or ham (non-spam) using machine learning models. The objective is to preprocess text messages, train multiple classifiers, and evaluate their performance on unseen data.

Key Features:
Dataset Overview:
The dataset contains text messages labeled as spam or ham with additional attributes like message length and punctuation count.
Classes are balanced to ensure fairness during model training.

Data Visualization:
Histograms of message length and punctuation distribution for spam and ham classes provide insights into their differences.

Machine Learning Pipelines:
Two models are implemented for comparison:
Random Forest Classifier (RF)
Support Vector Machine (SVM)

Prediction:
Both models are tested on unseen data and sample text messages, providing classification results for real-world cases.

Project Workflow:
1.Data Preparation:
Reads a .tsv file containing the spam dataset.
Balances the dataset by equalizing the number of ham and spam samples.

2.Exploratory Data Analysis (EDA):
Visualizes message length and punctuation frequency for both classes.

3.Feature Engineering:
Converts textual data into numerical form using TF-IDF Vectorization.

4.Train-Test Split:
Splits the data into training (70%) and testing (30%) subsets.

5.Model Training:
Trains two pipelines using Random Forest and SVM classifiers with TF-IDF.

6.Evaluation:
Evaluates the performance using metrics such as:
Accuracy
Confusion Matrix
Classification Report

7.Prediction on Custom Messages:
Tests the models on sample messages to determine whether they are spam or ham.
