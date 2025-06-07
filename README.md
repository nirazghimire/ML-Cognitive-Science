## 🚀 Project Overview

This repository documents an exploratory analysis into the predictability of cognitive outcomes using machine learning. The primary objective was to establish a performance baseline and determine the feasibility of using ML models to identify patterns in a complex dataset compiled from 121 participants. The project involved a full machine learning workflow, including data preprocessing, model training, and a rigorous comparison of multiple algorithms—from traditional classifiers to deep learning architectures—to identify the most effective approaches for this challenging problem.

## ✨ Key Features

* **Data:** The models were trained and tested on a unique dataset meticulously compiled from 121 participants.
* **Preprocessing:** A custom Python script was developed to clean, transform, and normalize the raw data, ensuring it was optimized for machine learning analysis.
* **Model Comparison:** The project systematically evaluates and compares a diverse set of models:
    * Random Forest 
    * Support Vector Machine (SVM) 
    * GoogleNet 
    * ResNet 
    * DenseNet 
    * VGG 
* **Multi-Label Classification:** Utilized the `MultiOutputClassifier` wrapper to handle the multi-label nature of the prediction task.

## 🛠️ Tech Stack

* **Python:** Core language for data processing and model training.
* **Scikit-learn:** Used for implementing Random Forest and SVM models, data splitting, and performance evaluation.
* **Deep Learning Frameworks:** Implemented models such as GoogleNet, ResNet, DenseNet, and VGG.
* **Optimizers:** Employed Adam and SGD for training deep learning models.

## 📊 Results

After training and evaluation on the 20% test split, the models achieved the following accuracies:

| Model | Test Accuracy (%) |
| :--- | :---: |
| **Support Vector Machine (SVM)** | **47%**  |
| Random Forest | 46%  |
| GoogleNet | 46%  |
| VGG | 44%  |
| DenseNet | 44%  |
| ResNet | 44%  |

The **Support Vector Machine (SVM)**, configured with an RBF kernel and a regularization parameter (C) of 10, emerged as the most effective model for this specific predictive task. 
