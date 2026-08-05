# 🩺 Breast Cancer Prediction using Machine Learning

## 📌 Overview

This project is an end-to-end machine learning application that predicts whether a breast tumor is **Benign** or **Malignant** using the Breast Cancer Wisconsin Diagnostic Dataset. The project follows a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and feature importance analysis.

The objective is to demonstrate how machine learning can assist in the early detection of breast cancer by analyzing diagnostic measurements of breast cell nuclei.

---

## 🎯 Project Objectives

- Understand and explore the Breast Cancer dataset.
- Perform Exploratory Data Analysis (EDA).
- Prepare the dataset for machine learning.
- Train a Random Forest Classifier.
- Evaluate the model using multiple classification metrics.
- Identify the most important features affecting predictions.
- Save the trained model for future deployment.

---

## 📂 Dataset

**Dataset:** Breast Cancer Wisconsin (Diagnostic) Dataset

**Features:** 30 numerical features describing characteristics of cell nuclei.

Examples include:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry

**Target Variable**

- **0 → Malignant**
- **1 → Benign**

Dataset Size:

- 569 Samples
- 30 Features

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset overview
- Statistical summary
- Missing value analysis
- Duplicate value analysis
- Target class distribution
- Correlation heatmap
- Feature relationship analysis

---

## 🤖 Machine Learning Model

Algorithm Used:

- Random Forest Classifier

Steps followed:

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature & Target Separation
5. Train-Test Split
6. Feature Scaling
7. Model Training
8. Prediction
9. Model Evaluation
10. Feature Importance Analysis

---

## 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

These metrics provide a comprehensive understanding of the model's classification performance.

---

## 📌 Feature Importance

Random Forest provides feature importance scores that indicate which tumor characteristics contribute the most to predicting whether a tumor is benign or malignant.

A bar chart was generated to visualize the top important features.

---


## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/Breast-Cancer-Prediction.git
```

### Navigate to the project folder

```bash
cd Breast-Cancer-Prediction
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open:

```
Breast_Cancer_Prediction.ipynb
```

using Jupyter Notebook or Google Colab.

---

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Compare multiple ML algorithms
- Build a FastAPI prediction API
- Develop a Streamlit web application
- Deploy the model on Render or Railway

---

## 👨‍💻 Author

**Swastik Saha**

AI/ML Enthusiast | Data Analytics | Machine Learning

GitHub: https://github.com/Swastik0407

LinkedIn: https://linkedin.com/in/swastik-saha-aot

---

## ⭐ If you found this project helpful, consider giving the repository a star!
