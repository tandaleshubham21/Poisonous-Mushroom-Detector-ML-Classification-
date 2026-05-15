# 🍄 Poisonous Mushroom Detector (ML Classification)

## 📌 Project Overview

The **Poisonous Mushroom Detector** is a Machine Learning classification project designed to identify whether a mushroom is **edible** or **poisonous** based on its physical characteristics.

This project uses the famous **Mushroom Dataset** from the UCI Machine Learning Repository and applies multiple supervised machine learning algorithms to compare performance and prediction accuracy.

The main goal of this project is to:

* Build a reliable mushroom classification system
* Compare different classification algorithms
* Identify the most influential mushroom features
* Analyze model performance using evaluation metrics

---

# 🎯 Problem Statement

Determining whether a mushroom is edible or poisonous is a critical real-world problem because many poisonous mushrooms visually resemble edible ones.

This project aims to solve this problem using Machine Learning classification techniques by analyzing mushroom characteristics such as:

* odor
* cap shape
* gill color
* ring type
* spore print color
* habitat
* population

---

# 📂 Dataset Information

### Dataset Name

Mushroom Classification Dataset

### Source

UCI Machine Learning Repository

### Dataset Description

The dataset contains hypothetical descriptions of mushroom samples corresponding to 23 species of gilled mushrooms in the *Agaricus* and *Lepiota* family.

Each mushroom is classified into:

* **Edible (e)**
* **Poisonous (p)**

Unknown edibility mushrooms are grouped into the poisonous category.

### Total Features

* 22 categorical features
* 1 target variable (`class`)

---

# 📖 Features Used

Some of the most predictive features identified during analysis include:

* Odor
* Spore Print Color
* Gill Color
* Gill Size
* Ring Type
* Stalk Root
* Bruises
* Population
* Stalk Surface Above Ring
* Stalk Surface Below Ring

---

# ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# 🧠 Machine Learning Algorithms Implemented

The following supervised learning models were trained and evaluated:

## 1. Logistic Regression

A statistical classification algorithm used for binary classification problems.

## 2. K-Nearest Neighbors (KNN)

A distance-based classification algorithm that classifies data points using nearest neighbors.

## 3. Random Forest Classifier

An ensemble learning algorithm that uses multiple decision trees for improved prediction accuracy.

## 4. Naive Bayes Classifier

A probabilistic classification algorithm based on Bayes’ theorem.

---

# 🔄 Project Workflow

## Step 1 — Data Collection

Loaded the Mushroom Dataset into a Pandas DataFrame.

## Step 2 — Data Cleaning

Checked for missing values and dataset consistency.

## Step 3 — Data Preprocessing

Applied Label Encoding to convert categorical values into numerical format.

## Step 4 — Exploratory Data Analysis

Performed feature importance analysis using Random Forest.

## Step 5 — Feature Selection

Selected top predictive features for model training.

## Step 6 — Model Training

Trained multiple classification models.

## Step 7 — Model Evaluation

Evaluated models using:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

# 📊 Evaluation Metrics

The following evaluation metrics were used to compare model performance:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

# 📈 Feature Importance Analysis

Feature importance analysis was performed using the Random Forest algorithm to identify which mushroom characteristics contribute most to poisonous mushroom prediction.

The analysis showed that:

* Odor
* Gill Color
* Spore Print Color
* Ring Type

are among the strongest predictors.

---

# 🏆 Model Performance

The implemented models achieved high classification accuracy on the dataset.

### Best Performing Model

✅ Random Forest Classifier

Reason:

* Handles categorical relationships effectively
* Reduces overfitting
* Provides feature importance analysis
* Achieves excellent prediction accuracy

---

# 📁 Project Structure

```bash
Poisonous-Mushroom-Detector-ML/
│
├── data/
│   └── mushrooms.csv
│
├── notebooks/
│   └── Best_Mushroom_Classification_Project.ipynb
│
├── images/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# 🚀 Future Improvements

Possible future enhancements:

* Deploying the model using Streamlit or Flask
* Building a web-based mushroom prediction application
* Hyperparameter tuning
* Adding more visualization dashboards
* Implementing advanced ensemble models

---

# 📚 Learning Outcomes

Through this project:

* Multiple ML classification techniques were explored
* Feature selection and preprocessing techniques were applied
* Model evaluation methods were practiced
* Real-world classification problem-solving skills were improved


# ⭐ Conclusion

This project demonstrates how Machine Learning can be effectively used for classification tasks involving categorical biological datasets. By comparing multiple classification algorithms and analyzing feature importance, the project successfully identifies poisonous mushrooms with high accuracy.
