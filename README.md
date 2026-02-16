# Logistic_Naive_kNN
Machine Learning classification project on the Iris dataset using K-Nearest Neighbors (KNN), Logistic Regression, and Naive Bayes.

# Iris Flower Classification using Multiple ML Algorithms

## 📌 Project Overview

A botanical research center wants to automate the identification of Iris flower species based on physical measurements. 

Instead of manually identifying species (which is time-consuming and error-prone), this project builds Machine Learning classification models to predict the species automatically.

We implement and compare:

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Naive Bayes

The goal is to evaluate model performance and identify the best algorithm.

---

## 📊 Dataset Description

We use the famous Iris dataset.

Features:
- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm

Target Classes:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

Dataset Characteristics:
- 150 total samples
- 3 balanced classes (50 each)
- Clean and well-structured dataset

---

## ⚙️ Experimental Setup

To make the problem slightly more challenging:

- Training Data: 50% of dataset
- Testing Data: 100% of dataset

This setup helps evaluate model generalization behavior.

---

## 🧠 Algorithms Used

### 1️⃣ K-Nearest Neighbors (KNN)
- Distance-based classification
- Sensitive to scaling
- Works well for small datasets

### 2️⃣ Logistic Regression
- Linear classification algorithm
- Uses sigmoid/softmax function
- Performs well when classes are linearly separable

### 3️⃣ Naive Bayes
- Probabilistic classifier
- Based on Bayes’ Theorem
- Assumes feature independence

---

## 📈 Model Evaluation Metrics

Models are compared using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 🏆 Results & Comparison

All three models achieve high accuracy due to:

- Clean dataset
- Balanced classes
- Small dataset size

The best performing model is selected based on:
- Highest accuracy
- Stability across predictions
- Simplicity and computational efficiency

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone <your-repo-link>
cd <repo-name>
