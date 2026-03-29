# Hybrid-Bivariate-Multivariate-Purchase-Intent-Prediction
Hybrid deep learning model for purchase intent prediction combining Factorization Machines (FM) and Deep Neural Networks (DeepFM). Captures low- and high-order feature interactions to improve prediction accuracy using behavioral and demographic data.

This project implements a hybrid deep learning architecture to predict consumer purchase intent by combining both bivariate (low-order) and multivariate (high-order) feature interactions. The model leverages Factorization Machines (FM) and deep neural networks (DeepFM) to improve prediction performance.

---

## 📌 Overview

Understanding customer purchase intent is critical in marketing analytics and recommendation systems. Traditional models struggle to capture complex feature interactions. This project addresses this by combining shallow and deep models to learn both simple and complex relationships in the data.

---

## 🎯 Objective

* Predict whether a user will make a purchase
* Capture both low-order and high-order feature interactions
* Improve prediction accuracy using hybrid modeling

---

## 📊 Dataset

The dataset contains behavioral and demographic features such as:

* User activity data
* Product interactions
* Demographic attributes
* Historical engagement patterns

Target variable:

* Purchase Intent (0/1)

Due to dataset size limitations, the dataset is not included in this repository.

---

## ⚙️ Tech Stack

* Python
* TensorFlow / Keras (for deep learning)
* Scikit-learn
* Pandas, NumPy
* Matplotlib / Seaborn

---

## 🧩 Model Architecture

### 🔹 Factorization Machines (FM)

* Captures **low-order (pairwise) feature interactions**
* Efficient for sparse and high-dimensional data

### 🔹 Deep Neural Network (DeepFM)

* Learns **high-order feature interactions**
* Captures complex nonlinear relationships

### 🔹 Hybrid Approach

* Combines FM + Deep Neural Network
* Enables learning of both simple and complex patterns

---

## 🔍 Methodology

### 1. Data Preprocessing

* Handled missing values
* Encoded categorical variables
* Normalized numerical features

### 2. Feature Engineering

* Created meaningful input representations
* Selected relevant features for interaction modeling

### 3. Model Training

* Loss Function: Binary Cross-Entropy
* Optimizer: Adam
* Activation: ReLU / Sigmoid

### 4. Model Evaluation

* Accuracy
* Precision, Recall
* ROC-AUC

---

## 📈 Results

* Achieved strong prediction performance using hybrid modeling
* Improved accuracy compared to traditional models
* Successfully captured complex feature interactions

---

## 💡 Key Insights

* Combining FM and deep learning significantly improves prediction performance
* Feature interactions play a critical role in purchase intent modeling
* Hybrid architectures outperform single-model approaches

---

## 🚀 Future Improvements

* Implement advanced architectures like xDeepFM or AutoInt
* Apply hyperparameter tuning for further optimization
* Deploy model as a recommendation system API
