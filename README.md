# RNA Sequence Classification

## Overview

This project focuses on RNA sequence classification and interaction prediction using Machine Learning and Deep Learning techniques. The work is based on RNA sequence data and includes both baseline models and advanced neural network architectures inspired by the TEC-LncMir research paper.

The main goal was to preprocess RNA sequences, extract meaningful features, train multiple models, and compare their performance using standard evaluation metrics.

## Work Done

* Loaded and explored RNA sequence datasets.
* Performed data preprocessing and sequence preparation.
* Applied k-mer based feature extraction.
* Split the dataset into training, validation, and testing sets.
* Trained and evaluated multiple Machine Learning and Deep Learning models.
* Compared model performance using Accuracy, Precision, Recall, F1-Score, MCC, ROC-AUC, and PR-AUC.
* Reproduced the TEC-LncMir architecture from the research paper.
* Implemented and tested improved versions of TEC-LncMir.

## Models Implemented

### Baseline Machine Learning Models

* Random Forest
* XGBoost

### Baseline Deep Learning Models

* CNN (Convolutional Neural Network)
* BiLSTM (Bidirectional Long Short-Term Memory)

### Ablation Study

* Transformer Only Model

### Research Reproduction

* TEC-LncMir (Paper Reproduction)

### Improved Models

* TEC-LncMir with 4 Attention Heads
* TEC-LncMir + BiGRU
* TEC-LncMir + Residual Blocks
* TEC-LncMir Ensemble Model

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* PyTorch
* XGBoost

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* Specificity
* F1-Score
* Matthews Correlation Coefficient (MCC)
* ROC-AUC
* PR-AUC
* Cohen Kappa Score

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Extraction using k-mers
4. Model Development
5. Model Training
6. Performance Evaluation
7. Model Comparison
8. Result Analysis

## Key Learning Outcomes

Through this project, I gained hands-on experience in:

* RNA sequence analysis
* Machine Learning model development
* Deep Learning architectures
* Transformer-based models
* Research paper reproduction
* Model evaluation and comparison
* Scientific computing using Python

## Author

P. Vishwanath

B.Tech Computer Science and Engineering (Core)

GITAM University, Hyderabad

Batch: 2023–2027
