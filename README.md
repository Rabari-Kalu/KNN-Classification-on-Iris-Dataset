# KNN-Classification-on-Iris-Dataset
This project demonstrates how to build, train, and evaluate a K-Nearest Neighbors (KNN) classifier using the Iris flower dataset — a classic dataset used for classification problems.

### 🎯 Objective
To build and evaluate a **K-Nearest Neighbors (KNN)** classifier using normalized features from the **Iris dataset**.  
This project demonstrates fundamental steps in a machine learning classification pipeline, including preprocessing, training, evaluation, and visualization.

---

## 🧩 Features Covered
- Importing and exploring dataset
- Feature normalization with `StandardScaler`
- Splitting dataset into training and testing sets
- Model training using `KNeighborsClassifier`
- Experimenting with multiple K values
- Evaluating model using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
- Visualizing decision boundaries using Matplotlib and Seaborn

---

## 📊 Dataset Information
**Dataset:** Iris  
**Features:**  
- SepalLengthCm  
- SepalWidthCm  
- PetalLengthCm  
- PetalWidthCm  

**Target Variable:** `Species`  
Classes: `Iris-setosa`, `Iris-versicolor`, `Iris-virginica`

---

## 🧠 Algorithm Overview
**K-Nearest Neighbors (KNN)** is a simple, non-parametric, instance-based algorithm.  
It classifies a new observation based on the **majority vote of its K nearest neighbors** in the feature space.

### 🔍 How KNN Works
1. Compute the distance between the test sample and all training samples.
2. Choose the K nearest points.
3. Assign the label that is most common among these K neighbors.

### 🧮 Choosing the Right K
- Small K → sensitive to noise, overfitting  
- Large K → smoother boundary, underfitting  
- Common approach: Try several K values and pick the one with highest validation accuracy.


