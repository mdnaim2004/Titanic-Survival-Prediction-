# █████╗ ██╗      ██████╗  ██████╗ ██████╗ ██╗████████╗██╗  ██╗███╗   ███╗
# ██╔══██╗██║     ██╔════╝ ██╔═══██╗██╔══██╗██║╚══██╔══╝██║  ██║████╗ ████║
# ███████║██║     ██║  ███╗██║   ██║██████╔╝██║   ██║   ███████║██╔████╔██║
# ██╔══██║██║     ██║   ██║██║   ██║██╔══██╗██║   ██║   ██╔══██║██║╚██╔╝██║
# ██║  ██║███████╗╚██████╔╝╚██████╔╝██║  ██║██║   ██║   ██║  ██║██║ ╚═╝ ██║
# ╚═╝  ╚═╝╚══════╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝     ╚═╝

# 🚢 Titanic Survival Prediction using Machine Learning

A complete end-to-end Machine Learning project that predicts whether a passenger survived the Titanic disaster based on demographic and travel features.

---

## 📌 Project Overview

This project performs:

- Data loading & exploration  
- Data cleaning & preprocessing  
- Feature engineering  
- Model training  
- Model evaluation  
- Prediction  

The goal is to build a classification model that can accurately predict **Survival (0 = No, 1 = Yes)**.

---

## 📂 Dataset Information

The dataset contains passenger details such as:

| Feature      | Description |
|-------------|------------|
| PassengerId | Unique ID |
| Pclass      | Ticket class (1st, 2nd, 3rd) |
| Name        | Passenger name |
| Sex         | Gender |
| Age         | Age in years |
| SibSp       | # of siblings/spouses aboard |
| Parch       | # of parents/children aboard |
| Ticket      | Ticket number |
| Fare        | Passenger fare |
| Cabin       | Cabin number |
| Embarked    | Port of Embarkation |
| Survived    | Target variable |

---

## ⚙️ Workflow

### 1️⃣ Data Preprocessing

✔ Missing value handling  
✔ Encoding categorical variables  
✔ Feature selection  
✔ Dropping irrelevant columns  

### 2️⃣ Exploratory Data Analysis (EDA)

- Survival by gender  
- Survival by class  
- Age distribution  
- Correlation analysis  

### 3️⃣ Feature Engineering

Examples:

- Family size  
- IsAlone feature  
- Title extraction from name  

### 4️⃣ Model Building

The following models can be used:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  

### 5️⃣ Model Evaluation

Metrics:

- Accuracy  
- Confusion Matrix  
- Classification Report  

---

## 🧠 Machine Learning Pipeline
