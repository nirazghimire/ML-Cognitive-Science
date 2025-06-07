# Predicting Cognitive Patterns with Machine Learning

[cite_start]This repository contains the code and analysis for a research project exploring the predictive capabilities of various machine learning models on a cognitive science dataset. [cite_start]The primary goal was to determine if machine learning could effectively predict outcomes based on patterns identified in data collected from 121 participants.

<p align="center">
  </p>

## 🚀 Project Overview

[cite_start]This study provides a comprehensive comparison of multiple machine learning algorithms, from traditional classifiers to advanced deep learning architectures, to identify the most effective models for predicting patterns in a complex cognitive dataset. [cite_start]The project involved a full machine learning workflow, including data preprocessing, feature engineering, model training, and a rigorous evaluation of performance based on metrics like accuracy, precision, recall, and F1-score.

## ✨ Key Features

* [cite_start]**Data:** The models were trained and tested on a unique dataset meticulously compiled from 121 participants.
* [cite_start]**Preprocessing:** A custom Python script was developed to clean, transform, and normalize the raw data, ensuring it was optimized for machine learning analysis.
* [cite_start]**Model Comparison:** The project systematically evaluates and compares a diverse set of models:
    * [cite_start]Random Forest 
    * [cite_start]Support Vector Machine (SVM) 
    * [cite_start]GoogleNet 
    * [cite_start]ResNet 
    * [cite_start]DenseNet 
    * [cite_start]VGG 
* [cite_start]**Multi-Label Classification:** Utilized the `MultiOutputClassifier` wrapper to handle the multi-label nature of the prediction task.

## 🛠️ Tech Stack

* [cite_start]**Python:** Core language for data processing and model training.
* **Scikit-learn:** Used for implementing Random Forest and SVM models, data splitting, and performance evaluation.
* [cite_start]**Deep Learning Frameworks:** Implemented models such as GoogleNet, ResNet, DenseNet, and VGG.
* [cite_start]**Optimizers:** Employed Adam and SGD for training deep learning models.

## 📊 Results

After training and evaluation on the 20% test split, the models achieved the following accuracies:

| Model | Test Accuracy (%) |
| :--- | :---: |
| **Support Vector Machine (SVM)** | [cite_start]**47%**  |
| Random Forest | [cite_start]46%  |
| GoogleNet | [cite_start]46%  |
| VGG | [cite_start]44%  |
| DenseNet | [cite_start]44%  |
| ResNet | [cite_start]44%  |

[cite_start]The **Support Vector Machine (SVM)**, configured with an RBF kernel and a regularization parameter (C) of 10, emerged as the most effective model for this specific predictive task. [cite_start]The detailed performance metrics, including precision, recall, and F1-score for each model, are available in the full research paper.
