# Phishing Website Detection

## Project Overview
Machine-learning classification project for distinguishing phishing and legitimate websites using website and URL-related features.

## Dataset
**Source:** Kaggle — Phishing Website Detector  
https://www.kaggle.com/datasets/eswarchandt/phishing-website-detector

Expected file:
`data/phishing.csv`

Public descriptions of this dataset report approximately **11,054 records** and around **30 website-related predictor features**, with a phishing/legitimate target.

## Repository Structure
```text
Phishing-Website-Detection/
├── 01_Phishing_Website_Classification.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── data/
    └── README.md
```

## Workflow
- Data understanding
- Identifier cleanup
- Target detection and mapping
- Missing-value handling
- Train/test split
- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- Random Forest
- Gradient Boosting
- Accuracy / Precision / Recall / F1 / ROC-AUC comparison
- Confusion matrix
- Random Forest feature importance

## Tools
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook

## How to Run
1. Download `phishing.csv` from the Kaggle dataset.
2. Place it inside the `data/` folder.
3. Install packages from `requirements.txt`.
4. Run `01_Phishing_Website_Classification.ipynb`.

## Responsible Use
This notebook is an educational ML portfolio project. A phishing classifier should not be treated as a complete security control without current threat data, monitoring, testing, and additional security safeguards.

## Attribution
The dataset is sourced from Kaggle. The notebook in this repository is an original portfolio workflow.
