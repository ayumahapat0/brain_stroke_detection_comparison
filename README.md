# Brain Stroke Prediction

## 📋 What This Project Does

This project compares KNN, Logistic Regression, Random Forest, SVM, XGB, and CatBoost models to see which one predictions Brain Stroke the best.

1. Exploratory Data Analysis: Class Imbalance, Summary Statistics, Feature Distribution, Correlations
2. Preprocessing Pipeline: Feature Scaing, One-hot Encoding, SMOTE
3. Hyperparameter Tuning on CatBoost
4. Model Training on non-smote and smote data
5. Model Evaluation and Feature Importance

This is the Kaggle Dataset used for this project: https://www.kaggle.com/datasets/zzettrkalpakbal/full-filled-brain-stroke-dataset?select=full_data.csv

---

## 🚀 Getting Started

### Prerequisites

- Python 3.12 or higher
- pip (Python package manager)
- A virtual environment in order install the libraries

### Clone the Repository

```bash
git clone https://github.com/ayumahapat0/brain_stroke_detection_comparison.git
cd brain_stroke_detection_comparison/
```
---

## Running Jupyter Notebook

### Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install Dependencies

```bash
pip install --upgrade pip
pip install jupyter
pip install -r requirements.txt
```

Or install manually:

```bash
pip install {module 1} {module 2} . . .
```


### Run jupyter notebook
```bash
jupyter execute notebook.ipynb
```

## Results 

Running this notebook will result in graphs and tables for class and feature distribution, correlations, feature importance, and evalution metrics such as precision, recall, accuracy, and F1 score. This will be PNG and CSV files.