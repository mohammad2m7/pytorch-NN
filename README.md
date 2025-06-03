# Customer Churn Prediction with PyTorch and Optuna

This project builds a deep learning model using PyTorch to predict customer churn. Hyperparameter optimization is performed using **Optuna**, and class imbalance is handled using **RandomOverSampler** from imbalanced-learn.

## 🧾 Files

- `Mohammad.ipynb`: Jupyter Notebook containing all the preprocessing, modeling, training, and evaluation.
- `requirements.txt`: Python dependencies to run the notebook.

## 📊 Dataset

The dataset used is `Churn_Modelling.csv` (originally from Kaggle).  
It includes features like credit score, geography, gender, tenure, balance, and more.

> Make sure the dataset is placed in the same directory as the notebook before running.

## ⚙️ Main Tools & Libraries

- Python 3.x
- PyTorch
- Optuna (for hyperparameter optimization)
- Scikit-learn
- imbalanced-learn
- seaborn, matplotlib
- pandas, numpy

## 🧪 Evaluation Metrics

- Accuracy
- F1 Score
- ROC AUC
- Mean Squared Error (MSE)
- Classification Report

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mohammad2m7/pytorch-NN.git
