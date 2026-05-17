# Heart Disease Prediction using Machine Learning

This project implements a complete End-to-End Machine Learning Pipeline for predicting heart disease using multiple Machine Learning classification algorithms and comparative analysis.

The project follows a real-world machine learning workflow including:
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
├── Correlation Matrix.png
├── Final Model Comparison.png
├── Heart Disease Distribution.png
├── Hyperparameter Tuning.png
├── Random Forest Confusion Matrix.png
└── README.md
```

---

# Exploratory Data Analysis (EDA)

## Heart Disease Distribution

<img src="Heart%20Disease%20Distribution.png" width="800">

The dataset shows a relatively balanced distribution between patients with and without heart disease.

---

## Correlation Matrix

<img src="Correlation%20Matrix.png" width="800">

The correlation matrix helps identify relationships between features and the target variable.

Positive values indicate positive correlation while negative values indicate inverse correlation.

---

# Hyperparameter Tuning

## KNN Hyperparameter Tuning

<img src="Hyperparameter%20Tuning.png" width="800">

Different K values were tested to determine the optimal number of neighbors for the KNN model.

Hyperparameter tuning helps improve model performance and optimize classification accuracy.

---

# Best Model Performance

## Random Forest Confusion Matrix

<img src="Random%20Forest%20Confusion%20Matrix.png" width="700">

The Random Forest model achieved the best overall performance with:
- High Accuracy
- Better Classification Performance
- Lower Prediction Errors

The confusion matrix visualizes:
- True Positives
- True Negatives
- False Positives
- False Negatives

---

# Final Model Comparison

## Accuracy Comparison Between Models

<img src="Final%20Model%20Comparison.png" width="800">

The comparison graph shows the performance difference between all implemented machine learning algorithms.

Random Forest and SVM achieved the highest accuracy among all models.

---

# Best Performing Model

Random Forest achieved the highest performance among all models with the best overall accuracy and classification results.

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

The results demonstrate that advanced and ensemble classification models such as:
- Random Forest
- Support Vector Machine (SVM)

provide better predictive performance compared to baseline models.

The project also highlights the importance of:
- Data Preprocessing
- Feature Scaling
- Hyperparameter Tuning
- Comparative Evaluation

in building accurate and efficient Machine Learning systems.
