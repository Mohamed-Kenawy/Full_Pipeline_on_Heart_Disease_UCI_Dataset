# ❤ Heart Disease Prediction
![WhatsApp Image 2025-08-15 at 20 28 49_36d7a283](https://github.com/user-attachments/assets/6cb2762f-c76c-4115-b1bc-099b0f550710)


## 📌 Overview
This project analyzes the *UCI Heart Disease dataset* and builds multiple machine learning models to predict the presence of heart disease.  
It includes *data preprocessing, feature selection, dimensionality reduction, model training, evaluation, visualization, clustering, and model saving for deployment*.

## 📂 Dataset
- *File:* heart_disease_uci.csv
- *Source:* UCI Machine Learning Repository
- *Description:* Contains patient health metrics such as:
  - Age
  - Sex
  - Chest pain type (cp)
  - Resting blood pressure (trestbps)
  - Cholesterol (chol)
  - ECG results (restecg)
  - Maximum heart rate (thalach)
  - Exercise-induced angina (exang)
  - ST depression (oldpeak)
  - Number of major vessels (ca)
  - Thalassemia (thal)
- *Target Variable:* num  
  - 0 = No heart disease  
  - 1-4 = Presence of heart disease (severity levels)

---

## 🚀 Features
- *Data Cleaning* – Handling missing values and removing irrelevant columns.
- *Encoding* – One-hot encoding for categorical features.
- *Scaling* – Standardization of numerical features.
- *Dimensionality Reduction* – PCA to retain 95% variance.
- *Model Training* – Logistic Regression, Decision Tree, Random Forest, SVM, and XGBoost.
- *Model Comparison* – Accuracy, Precision, Recall, F1-score comparison.
- *Feature Selection* – Using RFE, Chi-Square, and Feature Importance.
- *ROC & AUC Analysis* – Multi-class One-vs-Rest plots for all models.
- *Clustering* – K-Means and Hierarchical clustering with visualization.
- *Hyperparameter Tuning* – GridSearchCV & RandomizedSearchCV for best parameters.
- *Visualization* – Correlation heatmaps, distributions, PCA variance plots.
- *Model Saving* – Trained model, scaler, and PCA saved as .pkl for deployment.

---

## 📊 Results
After comparing all models, the project identifies the *best performing model* based on accuracy and evaluation metrics.  
The best model is saved for future predictions.

---

## 🛠 Installation
```bash
git clone https://github.com/Mohamed-Kenawy/Full_Pipeline_on_Heart_Disease_UCI_Dataset.git
cd Full_Pipeline_on_Heart_Disease_UCI_Dataset
pip install -r requirements.txt
