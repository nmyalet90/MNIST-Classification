# Handwritten Digit Classification with MNIST

This project uses the MNIST dataset to train a supervised classification model for handwritten digits from 0 to 9. It was developed as part of a Data Science diploma program and applies machine learning and data mining techniques.

## 📂 Contents

- `mnist_logistic_regression_classification.ipynb`: notebook with the full implementation of the project.
- Visualization of predictions and classification errors.
- Evaluation against a baseline model (`DummyClassifier`).

## 🧠 Algorithm Used

- **Multinomial Logistic Regression** (via `scikit-learn`)
- Baseline comparison using `DummyClassifier`

## ⚙️ Project Workflow

1. Load the MNIST dataset (`.idx` files)
2. Preprocessing: flattening and scaling
3. Model training
4. Evaluation with performance metrics (accuracy, classification report)
5. Visualization of predictions and classification errors

## 📊 Results

- The logistic regression model significantly outperformed the baseline.
- The model showed strong overall performance, with most errors occurring between visually similar digits (e.g., 4 and 9).
- Visualization helped identify model limitations and potential improvements.

## 🔧 Requirements

- Python 3
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `idx2numpy`

All dependencies can be installed directly from the notebook if using Google Colab.

## 👥 Authors

- Nahuel Moreno Yalet
- Juliana Macias

---

This project was developed for **Lesson 11 of the Data Science UADE's Diploma Program**.
