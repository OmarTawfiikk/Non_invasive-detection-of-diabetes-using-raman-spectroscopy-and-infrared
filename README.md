# Non-invasive-detection-of-diabetes-using-raman-spectroscopy-and-infrared

## Project Overview

This study compares two non-invasive techniques for detecting diabetes: Raman spectroscopy and infrared (IR) spectroscopy. The analysis covers data collection, preprocessing, augmentation techniques, and machine learning model performance. The findings indicate that Raman spectroscopy is a more effective non-invasive method for diabetes detection compared to infrared spectroscopy

## Key Features

-Comparison of Raman and IR Spectroscopy: Evaluates their effectiveness in non-invasive diabetes detection.

### Data Preprocessing:

-Raman data augmentation using SMOTE and noise addition.

-Infrared data enhancement using Principal Component Analysis (PCA) and feature selection.

### Machine Learning Approach:

-Random Forest classifier used for both datasets.

-Hyperparameter tuning and cross-validation applied.

### High Accuracy with Raman Spectroscopy:

-Inner arm: 97%

-Earlobe: 95%

-Thumbnail: 91.1%

-Vein: 91.1%

### Improved Accuracy for Infrared Spectroscopy:

-Initial accuracy: 50%

-After preprocessing: 70%

## Dataset Structure

the study used datasets structured as follows:

#### Raman Spectroscopy:

Data collected from the inner arm, earlobe, thumbnail, and vein.

Augmented with SMOTE and noise addition to enhance robustness.

#### Infrared Spectroscopy:

Initially 540 samples with 3,740 features.

Preprocessing included feature selection, PCA, and SMOTE resampling.

## Methodology

#### Data Augmentation & Preprocessing:

Raman data was balanced using SMOTE and noise addition.

Infrared data underwent PCA and feature selection to improve feature correlation.

#### Model Training & Evaluation:

Used Random Forest classifier for both datasets.

Hyperparameter tuning and 5-fold cross-validation applied.

Performance evaluated using accuracy, precision, recall, and F1-score.

## Results

#### Raman Spectroscopy:

Achieved high classification accuracy (91.1% to 97%) across different body regions.

Outperformed previous studies that used Support Vector Machines (SVM).

#### Infrared Spectroscopy:

Initial accuracy of 50% improved to 70% after feature selection and PCA.

Faced challenges with feature correlation and dataset variability.
