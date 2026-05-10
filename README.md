# Bank Marketing Classification

## Overview
This project focuses on building and evaluating machine learning models to predict whether a client will subscribe to a term deposit using the UCI Bank Marketing dataset.

The project includes:
- A custom implementation of the K-Nearest Neighbors (KNN) algorithm from scratch
- Training and comparison of multiple classification models
- Data preprocessing, feature selection, and dimensionality reduction techniques

---

## Dataset
- Source: UCI Machine Learning Repository - https://archive.ics.uci.edu/dataset/222/bank+marketing
- Dataset: Bank Marketing Dataset  
- Task: Binary classification (subscribe vs not subscribe)

---

## Models Implemented

### Custom Model
- K-Nearest Neighbors (KNN) implemented from scratch using NumPy

### Library-Based Models
- Decision Tree  
- AdaBoost  
- XGBoost  

---

## Data Preprocessing
- Handled missing values  
- Normalized numerical features  
- Encoded categorical variables  
- Split data into training and testing sets  

---

## Feature Engineering
- Applied feature selection techniques  
- Used dimensionality reduction to improve performance  
- Addressed class imbalance  

---

## Evaluation Metrics
Models were evaluated using:
- Precision  
- Recall  
- F1-score  

---

## Key Results
- XGBoost achieved the best overall performance across evaluation metrics  
- Custom KNN implementation provided a baseline comparison  
- Feature selection and preprocessing improved model performance  

---

## Project Structure
```
bank-marketing-classification/
│
├── notebooks/
│   ├── knn_from_scratch.ipynb
│   ├── model_comparison.ipynb
│
├── src/
│   └── knn.py (optional)
│
├── requirements.txt
└── README.md
```

---

## How to Run

### Option 1: Google Colab
- Open the notebooks directly in Google Colab

### Option 2: Local Setup
```bash
pip install -r requirements.txt
jupyter notebook
```

---

## Technologies Used
- Python  
- NumPy  
- Pandas  
- scikit-learn  
- XGBoost  
- Matplotlib  
- Google Colab  

---

## Author
Shelton Dmello
