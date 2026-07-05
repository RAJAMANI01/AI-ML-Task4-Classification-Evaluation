# AI & Machine Learning – Task 4: Classification Models, Evaluation Metrics & Handling Imbalanced Data

## 📌 Project Overview

This project demonstrates the implementation of binary classification models using the Breast Cancer Wisconsin dataset from scikit-learn. The objective is to build, evaluate, and compare classification models using appropriate evaluation metrics while understanding the importance of handling class imbalance.

## 🎯 Objectives

* Understand binary classification problems.
* Train and evaluate classification models.
* Analyze model performance using a confusion matrix.
* Evaluate models using Precision, Recall, F1-Score, ROC Curve, and AUC Score.
* Handle class imbalance using class weights.
* Compare Logistic Regression and Decision Tree classifiers.

## 📂 Dataset

**Dataset:** Breast Cancer Wisconsin Dataset

* Source: scikit-learn (`load_breast_cancer`)
* Number of Samples: **569**
* Number of Features: **30**
* Target Classes:

  * **0 – Malignant**
  * **1 – Benign**

## 🛠 Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 🤖 Machine Learning Models

### 1. Logistic Regression

* Feature scaling using StandardScaler
* Baseline classification model
* Evaluated using multiple performance metrics

### 2. Logistic Regression (Balanced)

* Implemented using `class_weight="balanced"`
* Demonstrates handling of imbalanced datasets

### 3. Decision Tree Classifier

* Used for comparison with Logistic Regression
* Evaluated using the same classification metrics

## 📊 Evaluation Metrics

The following metrics were used to assess model performance:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-Score
* ROC Curve
* AUC Score

These metrics provide a comprehensive understanding of classification performance beyond accuracy.

## 📈 Results

The project includes:

* Confusion Matrix
* Classification Report
* ROC Curve
* AUC Score
* Comparison of Logistic Regression and Decision Tree models
* Discussion on handling class imbalance

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run all notebook cells in sequence to reproduce the results.

## 📚 Learning Outcomes

After completing this project, I learned to:

* Build binary classification models.
* Interpret confusion matrices.
* Evaluate models using Precision, Recall, F1-Score, ROC Curve, and AUC.
* Understand why accuracy alone is not sufficient.
* Handle class imbalance using class weights.
* Compare multiple classification algorithms and justify model selection.

## 👨‍💻 Author

RAJAMANI S
