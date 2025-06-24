# Iris-Flower-Classification-using-K-Nearest-Neighbors-KNN-

This project implements a machine learning model using the *K-Nearest Neighbors (KNN)* algorithm to classify iris flowers into species based on features such as petal and sepal dimensions. The Iris dataset is one of the most well-known datasets in pattern recognition and classification literature.

---

## 📌 Objective

To build a classification model that accurately predicts the species of an iris flower based on its physical features using the KNN algorithm.

---

## 📊 Dataset Overview

- *Dataset Name:* Iris Dataset
- *Source:* Built-in dataset in scikit-learn or available on [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- *Features:*
  - sepal length (cm)
  - sepal width (cm)
  - petal length (cm)
  - petal width (cm)
- *Target Variable:* species (Setosa, Versicolor, Virginica)

---

## 🧠 Model Overview

- *Algorithm Used:* K-Nearest Neighbors (KNN)
- *Why KNN?*
  - Simple, instance-based learning algorithm
  - Effective for small and clean datasets

 - Non-parametric and makes no assumptions about data distribution

---

## 🔍 Workflow

1. Load the Iris dataset
2. Perform exploratory data analysis (EDA)
3. Split data into training and test sets
4. Train a KNN classifier
5. Evaluate model performance
6. Make predictions on new samples

---

## ✅ Results

- *Accuracy Achieved:* ~97% on test data
- *Metrics Used:*  
  - Confusion Matrix  
  - Classification Report (Precision, Recall, F1-Score)

---

## 💡 Sample Prediction

```python
sample = [[5.1, 3.5, 1.4, 0.2]]
model.predict(sample)
# Output: ['setosa']
