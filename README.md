# Breast Cancer Classifier using SVM

This project implements a **Breast Cancer Classification Model** using the **Support Vector Machine (SVM)** algorithm. The goal of this project is to classify tumors as **benign** or **malignant** based on medical features from a breast cancer dataset.

The dataset used in this project is the **Breast Cancer Wisconsin Dataset**, which was obtained from Kaggle and loaded from a CSV file.

## 📌 Project Overview

This notebook demonstrates how SVM can be used for classification problems in Machine Learning. It includes data preprocessing, model training, kernel selection, parameter tuning, and accuracy evaluation.

## 📊 Dataset

* **Dataset Name:** Breast Cancer Wisconsin Dataset
* **Source:** Kaggle
* **Format:** CSV file
* The dataset contains various features of cell nuclei that help classify tumors as malignant or benign.

## 🤖 Algorithm Used

### Support Vector Machine (SVM)

Support Vector Machine is a supervised machine learning algorithm used for classification and regression tasks. It works by finding the best **hyperplane** that separates data points into different classes with the maximum margin.

## 🔍 Kernels Used

Different kernels were used to analyze model performance:

* **Linear Kernel** – Used for linearly separable data
* **Polynomial Kernel** – Used for more complex relationships
* **RBF (Gaussian) Kernel** – Used for non-linear classification

## ⚙️ Parameter Tuning

The performance of the SVM model was improved by tuning the following parameters:

* **C Parameter** – Controls the trade-off between margin size and classification error
* **Gamma Parameter** – Controls how far the influence of a single training example reaches

## 📈 Model Accuracy

The model was evaluated using accuracy score to measure performance.

* **Accuracy:** (Write your accuracy here, e.g., 96%)

## 📚 Topics Covered

This project covers:

* Introduction to Support Vector Machine (SVM)
* Types of Kernels (Linear, Polynomial, RBF)
* Hyperplane Concept
* SVM Properties
* Issues in SVM
* Parameter Tuning (C and Gamma)
* Model Accuracy Evaluation

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 📂 Project Structure

```
BreastCancerClassifier-SVM/
│── dataset.csv
│── svm_classifier.ipynb
│── README.md
```

## 🎯 Conclusion

This project demonstrates how Support Vector Machine can be effectively used for medical data classification. By selecting appropriate kernels and tuning parameters, the model achieves good accuracy in predicting breast cancer diagnosis.

## 🔗 Dataset Source

Dataset was taken from Kaggle:
https://www.kaggle.com/

---

**Author:** Shruti Aggarwal
