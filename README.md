#  Cardiovascular-Risk-Analysis

## 🧠 Overview

Cardiovascular diseases remain a leading global health concern, making **early diagnosis and risk assessment** critical. This project aims to develop a robust predictive model that classifies whether a person is at risk of **heart disease** using a variety of machine learning classification algorithms.

## 🎯 Project Objective

To accurately **predict the presence of heart disease** in patients by comparing the performance of multiple classification algorithms. These include:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Support Vector Machine (SVM)  
- K-Means Clustering (used for exploratory analysis and grouping)

## 📁 Project Description

- This project uses the popular `heart_dataset` containing patient medical attributes such as cholesterol, blood pressure, chest pain type, age, and more.
- The dataset is preprocessed and used to **train and test each algorithm independently**.
- After evaluating model performance (accuracy, precision, recall, F1-score), the best-performing model is identified and discussed.


## 🛠️ Technologies Used

- **Language**: Python  
- **Libraries**:  
  - `pandas`, `numpy` – data handling  
  - `matplotlib`, `seaborn` – data visualization  
  - `scikit-learn` – ML models & evaluation  
  - `warnings`, `os`, `joblib` – utilities


## 🚀 How to Run the Program

1. **Download the Dataset**  
   - Use `heart.csv` or another standardized heart disease dataset (e.g., UCI).

2. **Clone or Download this Repository**

3. **Preprocessing and Execution**  
   - Run the script `data_preprocessing.py` to clean and prepare the data.
   - Open and run individual model files:  
     - `logistic_regression.py`  
     - `knn_model.py`  
     - `naive_bayes_model.py`  
     - `svm_model.py`  
     - `kmeans_exploration.py` *(for clustering-based insight)*

4. **Customize Path**  
   - Ensure dataset path inside the scripts matches your local machine location.

## 📊 Evaluation Metrics

Each classification algorithm is evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC-AUC (where applicable)

The results are compared to determine the most effective model for heart disease prediction based on this dataset.


