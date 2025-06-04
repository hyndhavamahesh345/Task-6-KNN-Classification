## 📌 Task 6: AI & ML Internship Assignment  
# 🌸 Iris Dataset – K-Nearest Neighbors (KNN) Classification  

This repository contains a classification project using the **K-Nearest Neighbors (KNN)** algorithm on the **Iris dataset**. This task is part of the **AI & ML Internship** program and focuses on instance-based learning, distance metrics, normalization, and decision boundary visualization.

---

## 🎯 Objective  

To implement and experiment with the **KNN classifier** to:  
- Understand instance-based learning and Euclidean distance  
- Normalize features to enhance distance-based model accuracy  
- Tune and select the optimal `K` value  
- Evaluate model performance using confusion matrix and classification report  
- Visualize decision boundaries using dimensionality reduction  

---

## 🧰 Tools and Libraries Used  

- Python  
- Jupyter Notebook / Google Colab  
- Pandas  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## 📂 Dataset  

The dataset used is the **Iris Dataset**, provided as `Iris.csv`.  
It contains measurements of iris flower parts to classify species into three categories:  
- Setosa  
- Versicolor  
- Virginica  

---

## 📊 What Was Done  

1. **Loaded and prepared the dataset**  
   - Removed ID column  
   - Encoded species labels into numerical classes  
   - Normalized features using `StandardScaler`  
   - Performed train-test split (80% train, 20% test)  

2. **Trained KNN Classifier**  
   - Used `KNeighborsClassifier` from Scikit-learn  
   - Tested values of `K` from 1 to 15  
   - Chose the best `K = 2` based on test accuracy  

3. **Evaluated the Model**  
   - Accuracy: **1.00**  
   - Confusion matrix showed perfect classification  
   - Classification report (precision, recall, F1-score) was flawless  

4. **Visualized Decision Boundaries**  
   - Applied PCA to reduce dimensionality to 2D  
   - Plotted decision boundaries for the best `K`  
   - Verified clear separation of the three flower classes  

---

## 🔍 Key Insights  

- 📈 **Best K = 2** gave **100% test accuracy (1.00)**  
- 🧼 **Normalization** was essential for accurate distance measurement  
- 🎯 **Perfect classification** on test set with no misclassified samples  
- 📊 **Confusion matrix and classification report** confirmed robustness  
- 🧠 PCA visualization revealed clear, clean class boundaries  
- ⚡️ KNN is simple yet highly effective for small-scale classification problems

---

## 🧪 Results Summary  

| Model           | Test Accuracy | Cross-Validation Accuracy |
|----------------|---------------|----------------------------|
| KNN (K = 2)     | **1.000**     | |

