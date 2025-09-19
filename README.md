# Logistic Regression on UCI Heart Disease Dataset

This project demonstrates the use of **Logistic Regression** on the [UCI Cleveland Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease).

The goal is to build a simple pipeline:
- Load the dataset
- Clean and preprocess data
- Train a Logistic Regression model
- Evaluate performance (accuracy, ROC AUC, confusion matrix, ROC curve)

---

## 📂 Files
- `heart_logistic_regression.ipynb` – Google Colab / Jupyter notebook with full code.

---

## 🚀 How to Run
1. Open the notebook in **Google Colab** (recommended).
2. Run all cells in order:
   - Download dataset
   - Inspect data
   - Preprocess (binary target, drop missing rows, encode categorical variables)
   - Train Logistic Regression
   - Evaluate results

---

## 📊 Example Output
- **Accuracy**: ~0.7 (varies with random split)
- **ROC AUC**: ~0.75  
- Confusion matrix and ROC curve plotted for evaluation.

---

## 🛠️ Dependencies
- Python 3
- pandas
- numpy
- scikit-learn
- matplotlib

(Colab has all of these pre-installed.)

---

## 🎯 Purpose
This assignment is purely for **learning Logistic Regression** on a real-world dataset.  
The model is not tuned or optimized — it’s meant to show the basics of:
- Data preprocessing
- Binary classification
- Model evaluation
