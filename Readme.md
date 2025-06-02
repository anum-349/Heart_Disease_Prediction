###Machine Learning Model Evaluation: Logistic Regression vs Random Forest


This project demonstrates how to evaluate and compare two popular classification algorithms — Logistic Regression and Random Forest — using scikit-learn. It includes performance analysis using accuracy, confusion matrix, and classification report, along with visualizations.

## Project Structure


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


Make sure you have the following libraries installed:

```bash
pip install scikit-learn matplotlib seaborn
```

## How to Run


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


- Logistic Regression

= Random Forest Classifier

Each model is trained on a 70% training split and evaluated on 30% test data.

## Metrics & Visuals


- Accuracy Score

= Confusion Matrix (with Seaborn heatmap)

= Classification Report (Precision, Recall, F1-score)

## Sample Output


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


Anum Kousar
📧 anumkousar552@gmail.com
🔗 # IIUI Shell

[![Python](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

---

## Overview

IIUI Shell is a custom interactive shell built with Python, featuring core file and directory operations, system information, process management, utilities, and advanced features like tab completion, piping, background execution, and redirection. It provides a colorful, user-friendly shell experience with comprehensive error handling.

---

## Features

### Core Features

- **Interactive Shell:** Custom prompt with `username@hostname IIUIShell ~/current/directory $`, command history, tab completion.
- **File Operations:** `cat`, `cp`, `mv`, `rm`, `touch`, `open` (Windows), `nano`.
- **Directory Operations:** `cd`, `ls`, `mkdir`, `rmdir`, `pwd`, `tree`.
- **System Information:** `date`, `whoami`, `hostname`, `ram`, `disk`.
- **Process Management:** `top`, `kill`, `ps aux`.
- **Utilities:** `echo`, `clear`, `help`, `history`.

### Advanced Features

- Tab completion for filenames and directories.
- Piping (`|`) to chain commands.
- Background execution (`&`).
- Input/output redirection (`>`, `>>`, `<`).
- Color-coded error messages and UI.
- ASCII art welcome banner.
- Graceful error handling and permission checks.

---

## Installation & Usage

### Prerequisites

- Python 3.x
- Python packages:

```bash
pip install psutil
pip install readline      # For Linux/macOS
pip install pyreadline3   # For Windows
```
## Setup
- Save the script as miniShell.py.
- Open terminal and navigate to the script folder.

## Run the Shell
```bash
# Linux/macOS
python3 miniShell.py

# Windows
python miniShell.py
```
## Exit the Shell
- Type exit
- Or press (Ctrl + C) then Enter
- Or press (Ctrl + D)

## Troubleshooting
- On Windows, if readline causes issues, install pyreadline3.
- Missing psutil? Install it with pip install psutil.
- nano may not work natively on Windows; use another editor or install GNU nano.

## Limitations
- Best experience on Linux or WSL.
- Native Windows terminals may have subprocess and command compatibility issues.

## Recommendation
Run the shell on Linux or WSL for full functionality.

## Author
 **Anum Kousar**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Anum%20Kousar-blue?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/anum-kousar-984406294/)
[![Email](https://img.shields.io/badge/Email-anumkousar552@gmail.com-red?logo=gmail&logoColor=white&style=flat-square)](mailto:anumkousar552@gmail.com)
