# Ecommerce-Text-Classification
This repository contains a Python script for efficient text classification of e-commerce product labels. The code uses the TfidfVectorizer to convert text data into numerical vectors and employs both K-Nearest Neighbors (KNN) and Multinomial Naive Bayes (MNB) algorithms for classification.



E-commerce Text Classification
Overview
This repository focuses on text classification for e-commerce product labels. The provided Python script utilizes machine learning techniques such as TfidfVectorizer, K-Nearest Neighbors (KNN), and Multinomial Naive Bayes (MNB) to categorize product labels into distinct classes.

Getting Started
Prerequisites
Ensure you have the following libraries installed:

pandas
scikit-learn

Dataset
The script reads the "Ecommerce_data.csv" dataset, containing product text descriptions and corresponding labels.

Data Preprocessing
Labels are encoded into numerical values for training, facilitating the classification process.

Model Training and Evaluation
Two models, KNN and MNB, are trained and evaluated using the TfidfVectorizer. Classification reports are generated to assess model performance.

Model Predictions
Explore model predictions for sample test cases, providing insights into the script's effectiveness.

Acknowledgments
Scikit-learn
Pandas
License
This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to explore the script for a detailed understanding of the e-commerce text classification process.
