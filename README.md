# Heart Disease Prediction using Machine Learning

This project implements a complete End-to-End Machine Learning Pipeline for predicting heart disease using multiple classification algorithms and comparative analysis.

The project follows a real-world Machine Learning workflow including:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Model Training
- Hyperparameter Tuning
- Model Evaluation
- Comparative Analysis

---

# Machine Learning Algorithms Used

The following classification algorithms were implemented and compared:

- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest

---

# Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Dataset

The project uses the Heart Disease UCI Dataset for binary classification.

---

# Project Structure

```text
heart-disease-prediction-ml/
│
├── Heart_Disease_Project.ipynb
├── heart_disease_uci.csv
├── screenshots/
└── README.md
```

---

# Exploratory Data Analysis

## Heart Disease Distribution

![Heart Disease Distribution](heart_disease_distribution.png)

The dataset shows a relatively balanced distribution between patients with and without heart disease.

---

## Correlation Matrix

![Correlation Matrix](correlation_matrix.png)

The correlation matrix helps identify relationships between features and the target variable.

---

# Hyperparameter Tuning

## KNN Hyperparameter Tuning

![KNN Tuning](knn_tuning.png)

Different K values were tested to determine the optimal number of neighbors for the KNN model.

---

# Best Model Performance

## Random Forest Confusion Matrix

![Random Forest Confusion Matrix](random_forest_cm.png)

The Random Forest model achieved the best overall performance with high prediction accuracy and lower classification errors.

---

# Final Model Comparison

## Accuracy Comparison Between Models

![Model Comparison](model_comparison.png)

The comparison graph shows the performance difference between all implemented machine learning models.

Random Forest and SVM achieved the highest accuracy among all algorithms.

---

# How to Run

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Run Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
Heart_Disease_Project.ipynb
```

---

# Conclusion

This project successfully implemented a complete Machine Learning pipeline for heart disease prediction.

The results demonstrate that ensemble and advanced classification models such as Random Forest and SVM provide better predictive performance compared to simpler baseline models.

The project also highlights the importance of:
- Data preprocessing
- Feature scaling
- Hyperparameter tuning
- Comparative evaluation

in building accurate Machine Learning systems.
