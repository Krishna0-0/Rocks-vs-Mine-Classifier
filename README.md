# Rocks-vs-Mine-Classifier
This project predicts whether an underwater object is a Rock or a Mine  using sonar signal data and a Logistic Regression classifier. Built with Python and scikit-learn.

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3.0-orange)
![License](https://img.shields.io/badge/license-MIT-green)

## Overview

- Uses the SONAR dataset with 60 features per object
- Splits data into train/test using stratified sampling
- Applies Logistic Regression for classification
- Achieves decent accuracy despite limited data

## Dataset

The dataset has 60 features representing sonar signal strengths and a label:
- **R** = Rock
- **M** = Mine

## Technologies Used

- Python
- NumPy
- Pandas
- scikit-learn

## Results

Accuracy on training data:  83%
Accuracy on test data:  76%

## Credits

UCI ML Repository for dataset
Built using Google Collab initially

## Future Improvements

Hyperparameter Tuning
Use other classifiers like SVM, Random Forest
Visualize Feature importance


