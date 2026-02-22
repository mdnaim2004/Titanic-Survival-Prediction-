```text
██████╗ ███╗   ███╗███████╗    ████████╗██╗████████╗ █████╗ ███╗   ██╗██╗ ██████╗
██╔══██╗████╗ ████║██╔════╝    ╚══██╔══╝██║╚══██╔══╝██╔══██╗████╗  ██║██║██╔════╝
██████╔╝██╔████╔██║███████╗       ██║   ██║   ██║   ███████║██╔██╗ ██║██║██║     
██╔══██╗██║╚██╔╝██║╚════██║       ██║   ██║   ██║   ██╔══██║██║╚██╗██║██║██║     
██║  ██║██║ ╚═╝ ██║███████║       ██║   ██║   ██║   ██║  ██║██║ ╚████║██║╚██████╗
╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝       ╚═╝   ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝ ╚═════╝

```
<div align="center">

<h1>🚢 RMS TITANIC — MACHINE LEARNING PROJECT 🚢</h1>

<h3>Titanic Survival Prediction using Machine Learning</h3>

<p>
An end-to-end <b>Machine Learning classification project</b> that predicts whether a passenger survived the Titanic disaster using demographic and travel features.
</p>

</div>

---

<div align="center">

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/scikit--learn-ML-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
<img src="https://img.shields.io/badge/Type-Classification-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Dataset-Titanic-informational?style=for-the-badge">

</div>

---

## 📌 Project Overview

This project demonstrates the **complete Data Science workflow**:

- 📥 Data loading & exploration  
- 🧹 Data cleaning & preprocessing  
- 🔍 Exploratory Data Analysis (EDA)  
- 🧠 Feature engineering  
- 🤖 Model training (multiple algorithms)  
- 📊 Model evaluation & comparison  
- 🎯 Final prediction pipeline  

### 🎯 Objective

To build a robust classification model that predicts:

| Value | Meaning |
|-------|--------|
| 0 | Did Not Survive |
| 1 | Survived |

---

## 📂 Dataset Information

The dataset contains detailed passenger information.

### 🔑 Features

| Feature | Description |
|--------|------------|
| Pclass | Ticket class |
| Sex | Gender |
| Age | Passenger age |
| SibSp | Siblings/spouses aboard |
| Parch | Parents/children aboard |
| Fare | Ticket fare |
| Embarked | Port of embarkation |
| Survived | Target variable |

---

## ⚙️ Machine Learning Workflow

### 🧹 Data Preprocessing

- Missing value handling (Age, Embarked, Cabin)  
- Categorical encoding (Sex, Embarked)  
- Feature selection  
- Train–test split  

---

### 🔍 Exploratory Data Analysis (EDA)

Key insights:

- 👩 Females had higher survival rate  
- 🥇 1st class passengers survived more  
- 👶 Younger passengers had slightly better survival chances  

Visualizations included:

- Survival by gender  
- Survival by class  
- Age distribution  
- Correlation heatmap  

---

### 🧠 Feature Engineering

New features created:

- **FamilySize** = SibSp + Parch + 1  
- **IsAlone** feature  
- **Title extraction** from Name  

These features improved model learning of social patterns.

---

## 🤖 Models Used

| Model | Description |
|-------|------------|
Logistic Regression | Baseline linear model |
Decision Tree | Rule-based model |
Random Forest | Ensemble model |
K-Nearest Neighbors | Distance-based model |

---

## 📊 Model Performance Comparison

| Model | Accuracy |
|-------|----------|
Logistic Regression | 0.79 |
Decision Tree | 0.78 |
Random Forest | 0.83 ⭐ |
KNN | 0.80 |

🏆 **Best Model: Random Forest Classifier**

---

## 📋 Evaluation Metrics

- Accuracy Score  
- Confusion Matrix  
- Precision  
- Recall  
- F1-score  

---

## 🧪 Train vs Test Performance

| Dataset | Accuracy |
|---------|----------|
Train Set | 0.86 |
Test Set | 0.83 |

➡️ Model shows good generalization with minimal overfitting.

---

## 📈 Sample Prediction

| Passenger Features | Prediction |
|-------------------|------------|
Female, 1st Class, Age 25 | Survived ✅ |
Male, 3rd Class, Age 30 | Did Not Survive ❌ |

---

## 🧠 Machine Learning Pipeline

The complete pipeline followed in this project is shown below:

```text
Raw Data
   ↓
Data Cleaning & Missing Value Handling
   ↓
Exploratory Data Analysis (EDA)
   ↓
Feature Engineering
   ↓
Categorical Encoding & Feature Selection
   ↓
Train–Test Split
   ↓
Model Training (Logistic Regression, Decision Tree, Random Forest, KNN)
   ↓
Model Evaluation (Accuracy, Precision, Recall, F1-score)
   ↓
Best Model Selection
   ↓
Final Prediction
```

---

## 📊 Key Findings

Through detailed analysis and model training, the following important patterns were discovered:

- 👩 **Gender was the strongest predictor** of survival  
- 🥇 **1st class passengers** had a significantly higher survival rate  
- 👨‍👩‍👧 **Smaller families** had better survival chances  
- 💰 Higher fare passengers were more likely to survive  
- 👶 Children had slightly better survival probability than adults  

These insights align with the historical “**women and children first**” evacuation policy.

---

## 🏆 Best Model Selection

After training and evaluating multiple models, the performance comparison showed:

| Model | Accuracy | Remarks |
|-------|----------|---------|
Random Forest | **0.83** | Best overall performance ⭐ |
KNN | 0.80 | Good but sensitive to scaling |
Logistic Regression | 0.79 | Strong baseline model |
Decision Tree | 0.78 | Slight overfitting observed |

✅ **Random Forest** was selected as the final model due to:

- Higher accuracy  
- Better generalization  
- Robustness to noise  
- Ability to capture non-linear relationships  

---

## 📉 Overfitting Analysis

| Metric | Observation |
|--------|------------|
Train Accuracy | 0.86 |
Test Accuracy | 0.83 |

➡️ Small gap between train and test accuracy indicates **low overfitting** and good generalization.

---

## 📋 Confusion Matrix Interpretation

The confusion matrix helps us understand:

- True Positives → Correctly predicted survivors  
- True Negatives → Correctly predicted non-survivors  
- False Positives → Predicted survived but did not  
- False Negatives → Predicted did not survive but survived  

This analysis ensures the model is not biased toward one class.

---

## 🎯 Real-World Learning Outcomes

This project helped in understanding:

- End-to-end ML workflow  
- Data preprocessing techniques  
- Feature engineering impact  
- Model comparison strategy  
- Evaluation metrics interpretation  
- Overfitting vs underfitting  

---

## 📚 Skills Demonstrated

- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Supervised Machine Learning  
- Model Evaluation  
- Python (pandas, numpy, scikit-learn, seaborn, matplotlib)  

---

## 🚀 How This Project Can Be Extended

Future enhancements:

- 🔧 Hyperparameter tuning using GridSearchCV  
- 🔁 K-Fold Cross Validation  
- ⚖️ Feature scaling comparison  
- 🧪 Advanced models (XGBoost, LightGBM)  
- 🌐 Deploy using Streamlit  
- 📤 Kaggle submission automation  

---

## 🌟 Why This Project Matters

This project is a **strong foundation ML portfolio project** because it demonstrates:

✔ Data understanding  
✔ Feature engineering  
✔ Multiple model training  
✔ Proper evaluation  
✔ Clear insights and storytelling  

It is suitable for:

- Data Science beginners  
- Machine Learning practice  
- Kaggle workflow learning  
- Portfolio showcase  

---

<div align="center">

### 🚢 Data tells the story — Machine Learning reveals the outcome. 🚢

</div>
