---
## Machine Learning Model Evaluation: Logistic Regression vs Random Forest
---

This project demonstrates how to evaluate and compare two popular classification algorithms — Logistic Regression and Random Forest — using scikit-learn. It includes performance analysis using accuracy, confusion matrix, and classification report, along with visualizations.

## Project Structure
---

```bash
.
├── __pycache__/           # Compiled Python cache files (ignore)
├── heart.csv              # Raw heart disease dataset
├── heart_cleaned.csv      # Cleaned/preprocessed dataset
├── proj.py                # Contains feature matrix `X` and target vector `y`
├── modeltrain.py          # Model training, prediction, evaluation, visualization
└── README.md              # This file
```

## Dependencies
---

Make sure you have the following libraries installed:

```bash
pip install scikit-learn matplotlib seaborn
```

## How to Run
---

Ensure your dataset is cleaned and available in heart_cleaned.csv.

Run the training script:

```bash
python modeltrain.py
```

Make sure proj.py defines the dataset as:

```python
# proj.py
# Must define:
# X - features
# y - target labels
```

## Models Trained
---

- Logistic Regression

- Random Forest Classifier

Each model is trained on a 70% training split and evaluated on 30% test data.

## Metrics & Visuals
---

- Accuracy Score

- Confusion Matrix (with Seaborn heatmap)

- Classification Report (Precision, Recall, F1-score)

## Sample Output
---

```text
Accuracy: 0.89

Confusion Matrix:
[[40  5]
 [ 3 52]]

Classification Report:
              precision    recall  f1-score   support

           0       0.93      0.89      0.91        45
           1       0.91      0.95      0.93        55
```

## Author
---

Anum Kousar
📧 anumkousar552@gmail.com
🔗 # IIUI Shell

[![Python](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
