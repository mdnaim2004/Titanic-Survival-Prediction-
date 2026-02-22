<div align="center">

```text
██████╗ ███╗   ███╗███████╗    ████████╗██╗████████╗ █████╗ ███╗   ██╗██╗ ██████╗
██╔══██╗████╗ ████║██╔════╝    ╚══██╔══╝██║╚══██╔══╝██╔══██╗████╗  ██║██║██╔════╝
██████╔╝██╔████╔██║███████╗       ██║   ██║   ██║   ███████║██╔██╗ ██║██║██║     
██╔══██╗██║╚██╔╝██║╚════██║       ██║   ██║   ██║   ██╔══██║██║╚██╗██║██║██║     
██║  ██║██║ ╚═╝ ██║███████║       ██║   ██║   ██║   ██║  ██║██║ ╚████║██║╚██████╗
╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝       ╚═╝   ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝ ╚═════╝


## 🚢 RMS TITANIC — MACHINE LEARNING PROJECT

# 🚢 Titanic Survival Prediction using Machine Learning

A complete **end-to-end Machine Learning classification project** that predicts whether a passenger survived the Titanic disaster using demographic, social, and travel-related features.

This project demonstrates the full Data Science workflow — from **data preprocessing → exploratory analysis → feature engineering → model training → evaluation → prediction**.

---

## 📌 Project Overview

The objective of this project is to build a robust classification model that can accurately predict:

> **Survival Status**  
> `0 = Did Not Survive`  
> `1 = Survived`

The notebook covers the complete ML lifecycle:

- 📥 Data loading and initial exploration  
- 🧹 Data cleaning and preprocessing  
- 🔍 Exploratory Data Analysis (EDA)  
- 🧠 Feature engineering  
- 🤖 Model training with multiple algorithms  
- 📊 Model evaluation and comparison  
- 🎯 Final prediction pipeline  

This project is designed for **learning, experimentation, and Kaggle-style workflow practice**.

---

## 📂 Dataset Information

The dataset contains detailed passenger information from the Titanic.

### 🔑 Features Description

| Feature | Description |
|--------|------------|
| PassengerId | Unique passenger identifier |
| Pclass | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Name | Passenger full name |
| Sex | Gender of the passenger |
| Age | Age in years |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Ticket | Ticket number |
| Fare | Ticket fare paid |
| Cabin | Cabin number (many missing values) |
| Embarked | Port of embarkation (C, Q, S) |
| Survived | Target variable (0/1) |

---

## ⚙️ Machine Learning Workflow

### 1️⃣ Data Preprocessing

Key preprocessing steps:

- Handling missing values (Age, Cabin, Embarked)  
- Encoding categorical variables (Sex, Embarked)  
- Dropping irrelevant or high-missing columns  
- Converting data into model-friendly format  
- Train–test split  

---

### 2️⃣ Exploratory Data Analysis (EDA)

EDA helps uncover hidden patterns and relationships.

📊 Analyses performed:

- Survival rate by **gender**  
- Survival rate by **passenger class**  
- Age distribution of survivors vs non-survivors  
- Fare distribution analysis  
- Correlation heatmap for numeric features  

💡 Key insights:

- Female passengers had a significantly higher survival rate  
- 1st class passengers survived more than 3rd class  
- Younger passengers had slightly better survival probability  

---

### 3️⃣ Feature Engineering

New meaningful features were created to improve model performance:

- 👨‍👩‍👧 **FamilySize** = SibSp + Parch + 1  
- 🧍 **IsAlone** (binary feature)  
- 🏷️ **Title extraction** from passenger names (Mr, Mrs, Miss, etc.)  
- Age group binning (optional)  

Feature engineering helps the model learn **social patterns** rather than raw data.

---

### 4️⃣ Model Building

Multiple classification algorithms were trained and compared:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)  

Each model was trained on the same processed dataset to ensure fair comparison.

---

### 5️⃣ Model Evaluation

Models were evaluated using:

- ✅ Accuracy Score  
- 📉 Confusion Matrix  
- 📋 Classification Report  
  - Precision  
  - Recall  
  - F1-Score  

This helps identify:

- Overfitting vs underfitting  
- Class imbalance behavior  
- Best performing model  

---

## 🧠 Machine Learning Pipeline

```text
Raw Data
   ↓
Data Cleaning & Missing Value Handling
   ↓
Exploratory Data Analysis (EDA)
   ↓
Feature Engineering
   ↓
Encoding & Feature Selection
   ↓
Train–Test Split
   ↓
Model Training (Multiple Algorithms)
   ↓
Model Evaluation & Comparison
   ↓
Final Prediction
