# CIE 2 – Activity 2: Binary Classification

**College:** Zeal College of Engineering and Research, Narhe, Pune  
**Course:** Regression and Classification Algorithms  
**Activity:** Binary Classification Activity  
**Student:** Manas Giri  
**Roll Number:** AD3159

## Objective
Build a binary Logistic Regression classifier, evaluate it using a confusion matrix and classification metrics, plot the ROC curve, compare decision thresholds, and make a new prediction.

## Dataset
**Breast Cancer Wisconsin (Diagnostic) dataset**
- 569 observations
- 30 numerical input features
- Two classes: benign and malignant
- Positive class in this notebook: malignant (1)

Sources:
- UCI: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
- Scikit-learn documentation: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

## Files
- `activity2_binary_classification.ipynb` – completed notebook with code, outputs, graphs, metrics and decision log.
- `breast_cancer_wisconsin_dataset.csv` – dataset used in the activity.
- `README.md` – project information and references.

## Work included
- Dataset loading, data inspection, missing-value and duplicate checks.
- Class distribution and feature visualisations.
- Stratified 80:20 train-test split.
- StandardScaler and Logistic Regression in a Pipeline.
- Confusion matrix and classification report.
- Accuracy, precision, recall, F1-score and ROC-AUC.
- ROC curve.
- Threshold comparison at 0.30, 0.50 and 0.70.
- New prediction, coefficient interpretation, decision log and conclusion.

## How to run
Open the notebook in Google Colab or Jupyter Notebook and run all cells from top to bottom.

Required libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`.

## Responsible-use note
This is an educational dataset and model only. It is not a medical diagnostic tool and must not be used for clinical decisions.

## Faculty GitHub reference
https://github.com/complexiota
