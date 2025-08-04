# 👩‍🔬Dermatology Dataset Classification (Multiclass Problem)🧴

## Overview

This project aims to classify *erythemato-squamous diseases* using clinical and histopathological features. These diseases share many similar symptoms, making differential diagnosis difficult. Using machine learning models, we predict disease types across six classes:

* Psoriasis
* Seborrheic dermatitis
* Lichen planus
* Pityriasis rosea
* Chronic dermatitis
* Pityriasis rubra pilaris

## Features

* Data exploration and cleaning (handling missing values, feature type corrections)
* Visualization of feature distributions and correlations
* Implementation of multiple classification models:

  * Naive Bayes
  * Support Vector Machine (SVM)
  * Decision Tree
  * Perceptron
  * Principal Component Analysis (PCA) for dimensionality reduction
* Performance evaluation using metrics such as accuracy, precision, recall, F1-score, and execution time
* Analysis on both the full dataset and on clinical features only, investigating if biopsy can be bypassed for diagnosis

## 🎯Results

* All models achieved over 83% accuracy on the full feature set
* The Perceptron model reached up to 97.7% accuracy
* PCA offered a good trade-off between accuracy (\~94.4%) and execution time
* Classification using only clinical features yielded lower accuracy (\~62.2%), reflecting clinical diagnosis challenges

## Repository Contents

* Jupyter notebooks with exploratory data analysis, model training, and evaluation
* Documentation available in both English and Spanish
* Dataset source and preprocessing scripts

## Dataset

The dataset is sourced from [UCI Machine Learning Repository - Dermatology Dataset](https://archive.ics.uci.edu/ml/datasets/Dermatology) and [Kaggle](https://www.kaggle.com/datasets/olcaybolat1/dermatology-dataset-classification).

## Usage

1. Clone the repository
2. Install dependencies (e.g., pandas, scikit-learn, matplotlib, seaborn)
3. Run notebooks step-by-step for data exploration and model training

## License

This project is for educational purposes. Please cite the original dataset authors when using the data.

