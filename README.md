# BBC News Classification Project

## Overview

This project addresses the task of **classifying BBC news articles** into five predefined categories:
- Business
- Entertainment
- Politics
- Sport
- Tech

We explore two different machine learning approaches:
- **Unsupervised Learning** using **Non-negative Matrix Factorization (NMF)**
- **Supervised Learning** using **Logistic Regression**

The project includes:
- Exploratory Data Analysis (EDA)
- Text Preprocessing and Cleaning
- Feature Extraction using TF-IDF
- Model Building and Training
- Performance Comparison between unsupervised and supervised methods
- Data Efficiency and Overfitting Analysis

---

## Files

| File | Description |
|:---|:---|
| `BBC_News_Classification_Final.ipynb` | Main Jupyter Notebook containing full project code, explanations, and results |
| `BBC News Train.csv` | Training dataset (text + labels) |
| `BBC News Test.csv` | Test dataset (text only) |
| `BBC News Sample Solution.csv` | Sample submission file for Kaggle competition |
| `submission_nmf.csv` | Kaggle submission file generated using NMF model |
| `submission_logreg.csv` | Kaggle submission file generated using Logistic Regression model |

---

## Running the Project

1. Install required Python libraries:
    ```bash
    pip install numpy pandas scikit-learn matplotlib seaborn
    ```
2. Open `BBC_News_Classification_Final.ipynb` in Jupyter Notebook.
3. Run each cell step-by-step:
   - Start with loading datasets
   - Perform EDA
   - Clean text data
   - Extract TF-IDF features
   - Train and evaluate NMF and Logistic Regression models
4. Submit generated predictions to Kaggle (optional).

---

## Results

- **Logistic Regression** achieved approximately **97% training accuracy** and **high validation/test accuracy**.
- **NMF** achieved moderate performance (~65%-75%) due to the unsupervised nature of the approach.
- Logistic Regression was found to be **highly data-efficient**, reaching strong performance even with 20%-50% of the labeled data.
- No significant overfitting observed in supervised models.

---

## Requirements

- Python 3.x
- Numpy
- Pandas
- scikit-learn
- Matplotlib
- Seaborn

---

## Author

- **Michel DOLA**
- Course Project: Kaggle Competition - BBC News Classification
- Year: 2025

---

## Acknowledgments

- Dataset sourced from Kaggle BBC News Classification Challenge.
- Inspired by lectures on supervised and unsupervised machine learning techniques.
