# music-mental-health-ml
Machine learning–based analysis of music listening behaviors and self-reported mental health using classification, feature selection, and model comparison on the MxMH dataset.

## Project Overview

This project explores the relationship between music listening behaviors and self-reported mental health outcomes using the MxMH (Music x Mental Health) dataset from Kaggle. The dataset consists of survey responses covering music listening habits, genre preferences, and psychological condition scores including anxiety, depression, insomnia, and OCD.

The project follows an end-to-end machine learning workflow, starting from data cleaning and feature engineering to exploratory data analysis and model evaluation. Several new features were engineered to better capture listening behaviors, such as indicators for frequent listening to favorite genres and whether preferred music types are considered loud.

Multiple classification models were implemented and compared, including K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machines (SVM), and Decision Trees. Model performance was evaluated using accuracy, precision, recall, F1-score, and confusion matrices. Logistic Regression achieved relatively better performance among the tested models, though overall predictive performance was limited by data imbalance and feature separability.

To improve model interpretability and performance, various feature selection and dimensionality reduction techniques were applied, including SelectKBest, Extra Trees feature importance, Information Gain, and Principal Component Analysis (PCA). Additional experiments were conducted to address class imbalance using under-sampling, over-sampling, and SMOTE, though these approaches did not yield significant improvements.

This project highlights the challenges of modeling subjective mental health survey data and provides insights into how music listening patterns may relate to perceived mental health effects, while also identifying limitations and directions for future improvement.
