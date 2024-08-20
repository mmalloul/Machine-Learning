# Machine Learning Project

## Introduction
This repository contains a series of machine learning assignments that explore various aspects and techniques of ML. Each assignment focuses on different algorithms and real-world applications, demonstrating the versatility and power of machine learning across different domains.

## Contents
1. [Spam Detection Using Support Vector Machine (SVM)](ml_assignment1.ipynb)
2. [Heart Disease Prediction](ml_assignment2.ipynb)
3. [Linear Regression Analysis on World Happiness Report Data](ml_assignment3.ipynb)
4. [Iris Species Prediction and Clustering](ml_assignment4.ipynb)

## Project Highlights

### 1. Spam Detection Using Support Vector Machine (SVM)
- **Goal**: Classify text messages as spam or ham
- **Techniques**: Text preprocessing, TF-IDF vectorization, SVM
- **Key Findings**: 
- High accuracy on test data
- Potential overfitting issues addressed
- Simplified model training process for better performance

### 2. Heart Disease Prediction
- **Goal**: Predict heart disease presence from patient data
- **Techniques**: Data cleaning, feature engineering, logistic regression, decision tree, random forest, voting classifiers
- **Performance**: 
- Random Forest achieved highest accuracy (88.04%)
- All models showed good discrimination ability (ROC AUC 0.86-0.94)

### 3. Linear Regression Analysis on World Happiness Report Data
- **Goal**: Predict country happiness scores based on socio-economic factors
- **Techniques**: Data cleaning, correlation analysis, linear regression
- **Performance**: 
- R-squared value of 0.83
- MSE of 0.19, indicating good predictive power

### 4. Iris Species Prediction and Clustering
- **Goal**: Predict iris flower species and perform clustering
- **Techniques**: Random Forest classification, KMeans clustering, PCA visualization
- **Performance**: 
- Random Forest achieved 98% cross-validation accuracy
- KMeans clustering revealed 3 distinct clusters aligning with species

## Setup and Installation

1. Clone this repository:
```bash
git clone https://github.com/mmalloul/Machine-Learning.git
```
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
## Usage

Each Jupyter notebook (`.ipynb` file) contains a self-contained analysis. To run a notebook:

1. Start Jupyter Lab or Jupyter Notebook:
```bash
jupyter lab
```
or
```bash
jupyter notebook
```
2. Navigate to the desired notebook and run the cells in order.

## Requirements

See `requirements.txt` for a list of required Python packages.

## Conclusion

This project showcases the application of various machine learning techniques across different domains, ensuring high-quality AI implementations and demonstrating their practical utility in solving real-world problems. From text classification to regression analysis and clustering, these assignments cover a wide range of ML applications.

## Future Work

- Explore more advanced techniques like deep learning for complex datasets
- Implement ensemble methods to potentially boost performance
- Investigate interpretability techniques for better model understanding
- Expand datasets or incorporate additional features for improved predictions

## Contributors

- Mohammed Malloul - [Linkedin](https://www.linkedin.com/in/mohammedmalloul/)
