# COMP 5630 – Final Project

## Group Members
- Cindy Jiang  
- Hillary Lopez  
- Trisha Balamurugan  

---

## Project Overview
This project focuses on multi-class music genre classification using the Spotify Tracks dataset. The goal is to evaluate how well machine learning models can predict a song’s genre based on numerical audio features such as danceability, energy, and tempo.

We implement and compare multiple models, including Logistic Regression, Random Forest, and Support Vector Machines (SVM). Our approach includes data preprocessing, feature scaling, and model tuning. Performance is evaluated using metrics such as accuracy and F1-score to determine the most effective model.

---

## Dataset
- Source: Spotify Tracks Genre Dataset (Kaggle)  
- ~114,000 tracks across 125 genres  
- Features include:
  - danceability
  - energy
  - loudness
  - speechiness
  - acousticness
  - instrumentalness
  - liveness
  - valence
  - tempo  

- Target: Genre label  

---

## Methods

We implemented and compared the following models:

- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  

### Workflow:
1. Data preprocessing (cleaning, encoding, scaling)
2. Train/test split
3. Model training
4. Hyperparameter tuning
5. Evaluation and comparison

---

## Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-score (macro average)  
- Confusion Matrix  

---

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook  
2. Upload the dataset if needed  
3. Run all cells in order  

---

## Results Summary

- Random Forest provided strong performance and interpretability  
- SVM performed well after feature scaling  
- Logistic Regression served as a baseline  

---

## Notes

- Feature scaling was applied where necessary (especially for SVM)  
- Macro F1-score was used due to class imbalance across genres  
- Hyperparameter tuning was performed using cross-validation  

---

## Report

The full project report is written in NeurIPS format using Overleaf and is included in the final submission.

---

## Acknowledgments

- Dataset from Kaggle  
- Built using Python, pandas, scikit-learn, and matplotlib  
