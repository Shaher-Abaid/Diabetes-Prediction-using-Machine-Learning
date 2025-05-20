# Diabetes Prediction using Machine Learning

<img src="imagescover.png.jpg" alt="Diabetes-Prediction-using-Machine-Learning
" width="800"/>

## 📌 Project Overview

Diabetes is a chronic health condition affecting how your body processes glucose. This machine learning project aims to predict whether a patient is likely to develop diabetes based on clinical features.

---

## 🎯 Objectives

- Explore and visualize the dataset
- Build classification models like:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine
  - K-Nearest Neighbors
  - XGBoost / LGBM
- Compare model performance using Accuracy, F1, Recall
- Use confusion matrices and ROC curves for evaluation

---

## 📊 Technologies Used

- Python, Pandas, NumPy
- Scikit-learn, XGBoost, LightGBM etc...
- Seaborn, Matplotlib
- Jupyter Notebook

---

## 📁 Dataset

The dataset is based on the [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

---

## 🧠 Key Visualizations

- Pairplot of features
- Correlation heatmap
- Model comparison bar chart

---

## 📈 Results Summary
After evaluating multiple classification models, the top-performing model was:

✅ **LightGBM (LGBMClassifier)**
🎯 F1 Score: 0.841
📊 Test Accuracy: 89.6%
🔍 Precision: 83.3% | Recall: 84.9%
🧠 Generalization Gap: ~10.4

Other high-performing models included:

XGBoost (F1 Score: 0.839)

Random Forest (F1 Score: 0.842)

AdaBoost (F1 Score: 0.831)

While models like Decision Tree and KNN showed strong training accuracy, they exhibited larger generalization gaps, indicating a tendency to overfit.
---

## 🙌 Contributions

Feel free to fork this project and contribute by submitting issues or pull requests.
