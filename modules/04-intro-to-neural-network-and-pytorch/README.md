# Introduction to Neural Networks with PyTorch

> Hands-on implementation of Neural Networks using **PyTorch** completed as part of the **IBM AI Engineering Professional Certificate** on **Coursera**.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![IBM AI Engineering](https://img.shields.io/badge/IBM-AI%20Engineering-blue)
![Coursera](https://img.shields.io/badge/Coursera-Learning-blueviolet)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

# 📖 Overview

This directory contains the hands-on labs and practice project completed during the **Introduction to Neural Networks with PyTorch** course from the **IBM AI Engineering Professional Certificate** on **Coursera**.

The course introduces the PyTorch deep learning framework through practical implementation of tensors, automatic differentiation, custom datasets, neural network training, optimization techniques, regression, classification, and model evaluation.

The module concludes with a comprehensive **League of Legends Match Predictor** project, where a logistic regression model is developed using PyTorch to predict match outcomes from real-world game statistics. The project covers the complete machine learning workflow from data preprocessing to model deployment preparation.
---

# 🎯 Skills Gained

During this course, I gained practical experience with:

- PyTorch Fundamentals
- Tensor Operations
- One-Dimensional & Two-Dimensional Tensors
- Automatic Differentiation (Autograd)
- Computational Graphs
- PyTorch Data Pipeline
- Custom Dataset Classes
- Dataset & DataLoader
- Torchvision
- Data Transformations
- Neural Network Fundamentals
- `nn.Module`
- Model Parameters & `state_dict`
- Linear Regression
- Multiple Linear Regression
- Multi-Target Regression
- Logistic Regression
- Loss Functions
- Gradient Descent
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent
- Model Optimization
- Training & Validation
- Cross Entropy Loss
- Weight Initialization
- Binary Classification
- End-to-End Machine Learning Pipeline
- Data Preprocessing
- Feature Scaling
- Logistic Regression with PyTorch
- Model Evaluation
- Confusion Matrix
- ROC Curve
- Model Persistence (Saving & Loading)
- Hyperparameter Tuning
- Feature Importance Analysis

---

# 🛠 Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

---

# 📂 Repository Structure

```text
intro-to-neural-network-using-pytorch/
│
├── README.md
└── notebooks/
└── datasets/ (Optional - only if required)
```
---

# 🔄 PyTorch Data Pipeline

One of the core concepts introduced in this course is the PyTorch data pipeline, which provides an efficient and scalable way to load and preprocess data for model training.

```text
Raw Data
    │
    ▼
Custom Dataset
    │
    ▼
Data Transformations
    │
    ▼
DataLoader
    │
    ▼
Mini-Batches
    │
    ▼
Model Training
```

### Pipeline Components

| Component | Purpose |
|-----------|---------|
| **Dataset** | Represents the data source and defines how samples are accessed. |
| **Transforms** | Applies preprocessing such as normalization, resizing, and tensor conversion. |
| **DataLoader** | Creates mini-batches, shuffles data, and efficiently loads samples during training. |

### Key Benefits

- Standardized data loading workflow
- Efficient mini-batch processing
- Automatic data shuffling
- Parallel data loading
- Easy integration with training loops
- Reusable preprocessing pipelines

This data pipeline forms the foundation of almost every PyTorch Deep Learning application, from simple regression models to large-scale Computer Vision and Natural Language Processing systems.

---

# 📚 Notebook Guide

## 🔹 PyTorch Fundamentals

| Notebook | Topic |
|-----------|----------------------------------------------|
| 01 | One-Dimensional Tensors |
| 02 | Two-Dimensional Tensors |
| 03 | Derivatives & Computational Graphs (Autograd) |

---

## 🔹 Dataset & Data Pipeline

| Notebook | Topic |
|-----------|----------------------------------------------|
| 04 | Building a Simple Dataset |
| 05 | Custom Datasets & Data Transforms |
| 06 | Torchvision Datasets & Transforms |

---

## 🔹 Linear Regression

| Notebook | Topic |
|-----------|----------------------------------------------|
| 07 | Prediction with 1D Linear Regression |
| 08 | One-Parameter Linear Regression |
| 09 | Training Slope & Bias |
| 14 | Multiple Linear Regression Training |
| 15 | Multiple Linear Regression Prediction |
| 16 | Multi-Target Linear Regression |
| 17 | Training Multiple Output Linear Regression |

---

## 🔹 Model Training & Optimization

| Notebook | Topic |
|-----------|----------------------------------------------|
| 10 | Stochastic Gradient Descent |
| 11 | Mini-Batch Gradient Descent |
| 12 | Optimization the PyTorch Way |
| 13 | Training & Validation |

---

## 🔹 Classification

| Notebook | Topic |
|-----------|----------------------------------------------|
| 18 | Logistic Regression Prediction |
| 19 | Weight Initialization & Loss Functions |
| 20 | Cross Entropy Logistic Regression |

---

## 🚀 Practice Project

| Notebook | Description |
|-----------|----------------------------------------------|
| ⭐ 21 | Neural Network for Breast Cancer Classification |

## 🚀 Final Project

| Notebook | Description |
|-----------|----------------------------------------------|
| ⭐ 22 | Final Project – League of Legends Match Predictor |

### Project Workflow

```text
League of Legends Dataset
        │
        ▼
Data Loading
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Scaling
        │
        ▼
Logistic Regression Model
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
ROC Curve & Confusion Matrix
        │
        ▼
Model Saving & Loading
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Feature Importance Analysis
```

---

# ⭐ Featured Notebooks

If you're exploring this module for the first time, I recommend starting with:

- ⭐ Derivatives & Computational Graphs (Autograd)
- ⭐ Custom Datasets & Data Transforms
- ⭐ Optimization the PyTorch Way
- ⭐ Training & Validation
- ⭐ Cross Entropy Logistic Regression
- ⭐ Neural Network for Breast Cancer Classification
- ⭐ Final Project – League of Legends Match Predictor

---

# 💡 Key Takeaways

By completing this course, I developed practical experience in:

- Understanding tensors as the foundation of PyTorch.
- Applying automatic differentiation using Autograd.
- Building reusable PyTorch data pipelines using Dataset, Transforms, and DataLoader.
- Working with Torchvision datasets and preprocessing transforms.
- Developing linear regression models using PyTorch.
- Understanding optimization techniques including SGD and Mini-Batch Gradient Descent.
- Implementing complete model training and validation workflows.
- Building multiple linear and multi-output regression models.
- Developing binary classification models using Logistic Regression.
- Understanding proper loss functions, weight initialization, and model optimization.
- Applying end-to-end PyTorch concepts in a practical Breast Cancer Classification project.
- Building an end-to-end binary classification pipeline using PyTorch.
- Performing feature preprocessing and normalization.
- Training a logistic regression model for match outcome prediction.
- Evaluating model performance using Confusion Matrix and ROC Curve.
- Applying L2 Regularization to reduce overfitting.
- Saving and loading trained PyTorch models.
- Performing hyperparameter tuning to improve model performance.
- Interpreting feature importance to understand model predictions.

---

# 🏆 Final Project Highlights

### 🎮 League of Legends Match Predictor

As the capstone project for this course, I developed a machine learning model to predict the outcome of **League of Legends** matches using real in-game statistics.

### Project Objectives

- Load and preprocess real-world game data.
- Train a Logistic Regression model using PyTorch.
- Optimize model performance using Gradient Descent and L2 Regularization.
- Evaluate predictions using Confusion Matrix and ROC Curve.
- Save and reload trained models.
- Perform hyperparameter tuning.
- Analyze feature importance to understand prediction behavior.

### Machine Learning Pipeline

```text
Game Statistics
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Scaling
        │
        ▼
Logistic Regression
        │
        ▼
Training
        │
        ▼
Evaluation
        │
        ▼
Model Persistence
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Feature Importance
```

### Skills Demonstrated

- Data Preparation
- Logistic Regression
- Binary Classification
- Model Training
- Model Optimization
- Model Evaluation
- Hyperparameter Tuning
- Feature Engineering
- Model Persistence

---

# 📖 Related Engineering Notes

For concise revision notes and interview-focused summaries, see:

- Neural Networks
- Deep Learning Fundamentals
- PyTorch
- Model-Training-Lifecycle

Located under:

```text
../../notes/
```

---

# 📌 About

This directory is part of my **IBM AI Engineering Journey**, where I document my hands-on learning through the **IBM AI Engineering Professional Certificate** on **Coursera**.

The objective of this repository is to:

- Document my learning journey.
- Showcase practical PyTorch implementations through hands-on labs and an end-to-end machine learning project.
- Build production-oriented AI engineering skills.
- Provide a structured reference for software engineers and AI practitioners.
- Share practical Deep Learning resources with the engineering community.