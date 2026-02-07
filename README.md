# 📊 Credit Score Classification – Machine Learning Project

This project was developed as part of the **Machine Learning** course at the Faculty of Electrical Engineering, University of Sarajevo.  
The main goal of the project is to build and evaluate machine learning models for **credit score classification** using a real-world financial dataset.

---

## 🔍 Project Overview

The project covers the **complete machine learning pipeline**, starting from data preprocessing to model training, evaluation, and comparison of different classification approaches.

The task focuses on predicting credit score categories based on financial and behavioral client data, with an emphasis on model performance, data imbalance handling, and evaluation metrics.

---

## 🔧 Key Features

### Data Preprocessing
- Handling missing values for numerical and categorical features
- Encoding categorical variables using **Label Encoding** and **One-Hot Encoding**
- Feature scaling and standardization
- Handling class imbalance using **oversampling techniques (SMOTE, resampling)**

### Implemented Models
- **Decision Tree** (with extensive hyperparameter tuning)
- **K-Nearest Neighbors (KNN)**
- **Neural Network (Multi-layer Perceptron)**
- **Support Vector Machine (SVM)**
- **Ensemble Models**:
  - AdaBoost
  - Random Forest
  - Bagging

### Model Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- ROC Curves and AUC
- k-fold Cross-Validation
- Comparative analysis of balanced vs. imbalanced datasets

---

## 📈 Results

Among all evaluated models, **Decision Tree classifiers trained on balanced data achieved the best overall performance**, demonstrating strong generalization capabilities and high classification accuracy.  
Ensemble methods further highlighted the importance of proper data balancing and model selection when working with real-world financial datasets.

---

## 🛠 Technologies & Tools

- Python
- Scikit-learn
- Pandas, NumPy
- SMOTE
- Matplotlib
- Google Colab

---

## 🎓 Learning Outcomes

This project strengthened my understanding of:
- Supervised learning algorithms
- Data preprocessing and feature engineering
- Model evaluation and comparison
- Handling imbalanced datasets
- Practical application of machine learning in real-world scenarios
