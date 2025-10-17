# Wisconsin Breast Cancer Classification

A machine learning project for classifying breast cancer tumors as benign or malignant using the Wisconsin Breast Cancer dataset.

## Project Overview

This project implements a logistic regression classifier to predict whether breast cancer tumors are benign or malignant based on cytology features. The analysis includes comprehensive data exploration, preprocessing, model training, and evaluation.

## Project Structure

```
BreastCancer/
├── README.md # Project documentation
├── breast_cancer.ipynb # Main Jupyter notebook with analysis
├── LICENSE # License file
├── .DS_Store # macOS system file (ignored)
└── BreastCancer/ # Dataset directory
└── breast_cancer_wisconsin.data # Original dataset
```

## Dataset Information

The project uses the **Wisconsin Breast Cancer Dataset** containing:

- **698 samples** with complete data (after removing missing values)
- **10 features** describing cell characteristics:
  - Clump Thickness
  - Uniformity of Cell Size
  - Uniformity of Cell Shape
  - Marginal Adhesion
  - Single Epithelial Cell Size
  - Bare Nuclei
  - Bland Chromatin
  - Normal Nucleoli
  - Mitoses
- **Target variable**: Class (0 = Benign, 1 = Malignant)

### Data Preprocessing
- Removed 16 samples with missing values in 'Bare_Nuclei' column
- Dropped irrelevant 'Code_number' identifier column
- Mapped class labels: 2→0 (Benign), 4→1 (Malignant)

## Installation & Setup

### Prerequisites
- Python 3.7+
- Jupyter Notebook

### Required Libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```
