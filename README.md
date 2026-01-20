Sampling Techniques on Imbalanced Credit Card Data :-

The aim of this assignment is to study how different sampling techniques affect the performance of machine learning models when working with highly imbalanced datasets. Credit card fraud detection is used as a case study to analyze this behavior.

## Dataset Description
The dataset contains credit card transaction records with a binary target variable named `Class`.

- Class 0: Legitimate transaction  
- Class 1: Fraudulent transaction 
The dataset is highly imbalanced, with fraudulent transactions 

## Sampling Techniques Used
5 different sampling strategies were applied:
1. Random Undersampling  
2. Random Oversampling  
3. SMOTE (Synthetic Minority Oversampling Technique)  
4. SMOTE combined with Tomek Links  
5. Stratified Sampling during train-test split  

## Machine Learning Models Implemented
5 classification models were trained and evaluated on each sampled dataset:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- K-Nearest Neighbors  
- Support Vector Machine 

## Evaluation Metric
Model performance was evaluated using **accuracy score** on the test dataset. The results were recorded in a comparative table

## Results and Analysis
The results show that no single sampling technique performs best for all models.
Oversampling-based techniques such as SMOTE generally improved the performance of ensemble models, while undersampling caused performance degradation in some cases.

## Conclusion
This study demonstrates the importance of selecting an appropriate sampling strategy when working with imbalanced datasets. The effectiveness of a sampling method depends on the machine learning model being used.
---

