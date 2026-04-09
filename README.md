# 🛒 Bivariate–Multivariate Hybrid Models for Purchase Intent Prediction

## 📌 Overview

This project focuses on predicting **user purchase intent** using e-commerce clickstream data. It explores and compares traditional machine learning models, deep learning models, and hybrid approaches.

The main contribution of this project is the development of a **Hybrid XGBoost Voting Model**, which combines multiple XGBoost models to achieve improved and balanced performance across evaluation metrics.

---

## 🎯 Objectives

* Analyze user behavior using clickstream data
* Handle class imbalance using SMOTE
* Compare multiple modeling approaches
* Develop a hybrid model for improved prediction performance
* Evaluate models using standard classification metrics

---

## 📊 Dataset

* **Dataset Name:** Online Shoppers Intention Dataset
* **Type:** E-commerce clickstream data
* **Instances:** ~12,330 sessions
* **Features:** 18 attributes
* **Target Variable:** `Revenue` (Purchase / No Purchase)

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Label Encoding for categorical features
* Standardization using StandardScaler
* Train-Test Split

### 2. Feature Engineering

* Feature Selection using Chi-Square (SelectKBest)
* Dimensionality Reduction using PCA

### 3. Handling Imbalance

* SMOTE (Synthetic Minority Over-sampling Technique)

### 4. Model Development

#### 🔹 Traditional ML Models

* Logistic Regression
* Random Forest
* XGBoost

#### 🔹 Deep Learning Models

* Artificial Neural Network (ANN)
* DeepFM
* xDeepFM
* AutoInt

#### 🔹 Proposed Model

* **Hybrid XGBoost Voting Model**

---

## 📈 Results Summary

| Model                     | Accuracy  | F1-Score  | AUC       |
| ------------------------- | --------- | --------- | --------- |
| Logistic Regression       | 0.864     | 0.615     | 0.882     |
| Random Forest             | 0.847     | 0.576     | 0.880     |
| XGBoost                   | 0.868     | 0.643     | 0.867     |
| ANN                       | 0.871     | 0.649     | 0.911     |
| DeepFM                    | 0.890     | 0.662     | 0.889     |
| Hybrid XGBoost (Proposed) | **0.874** | **0.650** | **0.910** |

📌 The Hybrid XGBoost model provides the most **balanced and reliable performance**.

---

## 🧠 Key Insights

* Hybrid models outperform standalone models
* XGBoost is highly effective for structured data
* Deep learning captures complex interactions but requires tuning
* Handling class imbalance significantly improves recall

---

## 🛠️ Technologies Used

* Python
* Scikit-learn
* XGBoost
* TensorFlow / Keras
* Pandas, NumPy
* Matplotlib, Seaborn

---

## 📂 Project Structure

```
├── data/
│   └── online_shoppers_intention.csv
├── notebooks/
│   └── Bivariate_Multivariate_Hybrid_Models.ipynb
├── docs/
│   ├── research_paper.pdf
│   ├── presentation.pptx
│   └── poster.pdf
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/purchase-intent-prediction.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## 📌 Future Work

* Hyperparameter tuning of deep models
* Integration of sequential models (LSTM, GRU)
* Real-time deployment
* Transformer-based approaches

---

## 📚 References

* Rendle (2010) – Factorization Machines
* Guo et al. (2017) – DeepFM
* Lian et al. (2018) – xDeepFM
* Song et al. (2019) – AutoInt
* Chawla et al. (2002) – SMOTE

---

## 👤 Author

**Dhairya Bharat Acharya**
Gujarat University

---

## ⭐ Acknowledgment

This project was developed as part of an academic research study in Artificial Intelligence and Machine Learning.

---
