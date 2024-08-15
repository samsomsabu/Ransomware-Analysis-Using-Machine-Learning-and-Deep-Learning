
# Ransomware Analysis Using Machine Learning and Deep Learning

This project focuses on the analysis of ransomware using both Machine Learning (ML) and Deep Learning (DL) techniques. The primary goal is to identify patterns and characteristics in ransomware data that can be used to detect and prevent such attacks.

## Project Overview

Ransomware is malicious software that encrypts a victim's files, demanding a ransom for the decryption key. This project uses machine learning and deep learning models to analyze ransomware behavior, detect potential threats, and classify them accurately.

## Table of Contents

Data Grabbing

Feature Selection

Data Transformation

Correlation Analysis

Machine Learning Analysis

Deep Learning Analysis

Results and Interpretation

Contributors

## Data Grabbing

The dataset used for this analysis includes various attributes related to ransomware activity. The first step in the analysis involves acquiring and loading the data into the environment.

## Feature Selection

The analysis begins with selecting specific features from the dataset, focusing on the columns most impacting the results. This step includes grabbing the object column and converting data types as necessary.

## Data Transformation

Data transformation involves cleaning the data, handling missing values, and performing outlier detection and removal. This ensures that the models work with high-quality data, leading to better accuracy and reliability in the results.

## Correlation Analysis

Correlation analysis is performed to identify the relationships between different features in the dataset. This step is crucial for understanding which features contribute most to the prediction models.

## Machine Learning Analysis

Various machine learning models are applied to the dataset to determine the optimal model for detecting ransomware. The models evaluated include:

LightGBM

Decision Tree

Logistic Regression

MLP Classifier

Linear SVC

The performance of these models is evaluated based on metrics such as Accuracy, Precision, Recall, F1 Score, and ROC AUC. LightGBM emerged as the top-performing model, making it the most suitable for this task.

## Deep Learning Analysis

In addition to machine learning, deep learning techniques are applied to specific features such as the Protocols column. This analysis helps capture complex patterns that may not be apparent through traditional machine learning methods.

## Results and Interpretation

The results indicate that LightGBM is the most effective model for anomaly detection in the dataset, particularly for zero-day attacks and ransomware. The deep learning analysis further enhances the detection capabilities, providing a robust solution for ransomware analysis.

## Contributors

Samson Sabu developed this project. Contributions are welcome; feel free to open issues or submit pull requests.
