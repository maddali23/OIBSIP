# 🍷 Task 6 — Wine Quality Prediction
### Oasis Infobyte | Data Analytics Internship | Level 2

![Task](https://img.shields.io/badge/Task-6-purple?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-2-pink?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Data%20Analytics-blueviolet?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 👩‍💻 Intern Details

| Field | Details |
|-------|---------|
| **Name** | Maddali Naga Durga Niharika |
| **College** | Vasireddy Venkatadri Institute of Technology (VVIT) |
| **Internship ID** | OIB/A2/IP5267 |
| **Organization** | Oasis Infobyte |
| **Domain** | Data Analytics |
| **GitHub** | [maddali23/OIBSIP](https://github.com/maddali23/OIBSIP) |

---

## 📌 Project Overview

| Field | Details |
|-------|---------|
| **Project Title** | Wine Quality Prediction |
| **Level** | Level 2 — Project 2 |
| **Dataset** | WineQT.csv — Kaggle (yasserh) |
| **Tools Used** | Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| **Platform** | Google Colab |

---

## 🎯 Objective

Wine Quality Prediction focuses on predicting the quality of wine based
on its chemical characteristics, offering a real-world application of
machine learning in the context of viticulture. The goal of this project
is to build and compare three classification models by:

- Performing exploratory data analysis on wine chemical properties
- Preprocessing data with binary labeling and feature scaling
- Training Random Forest, SGD, and SVC classifier models
- Evaluating and comparing model performance
- Identifying the most important features influencing wine quality

---

## 📂 Dataset Used

| # | Dataset | Source | Size |
|---|---------|--------|------|
| 1 | Wine Quality Dataset | [Kaggle](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset) | 1,143 rows |

### Key Features

| Feature | Description |
|---------|-------------|
| Fixed Acidity | Non-volatile acids contributing to wine taste |
| Volatile Acidity | High values cause vinegar taste |
| Citric Acid | Adds freshness and flavor |
| Residual Sugar | Sugar remaining after fermentation |
| Chlorides | Amount of salt in wine |
| Density | Related to alcohol and sugar content |
| pH | Acidity/basicity scale (0 to 14) |
| Sulphates | Acts as antimicrobial agent |
| Alcohol | Percentage of alcohol content |
| Quality | Target variable (score 3 to 8) |

---

## 🪜 Steps Performed

| Step | Task | Description |
|------|------|-------------|
| 1️⃣ | **Import Libraries** | Imported Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| 2️⃣ | **Load Dataset** | Uploaded WineQT.csv and loaded into Pandas DataFrame |
| 3️⃣ | **EDA** | Checked shape, missing values, quality distribution, correlation heatmap |
| 4️⃣ | **Preprocessing** | Binary labeling, dropped Id column, 80/20 split, StandardScaler |
| 5️⃣ | **Model Training** | Trained Random Forest, SGD Classifier, and SVC models |
| 6️⃣ | **Model Evaluation** | Confusion matrices, accuracy bar chart, classification report |
| 7️⃣ | **Feature Importance** | Random Forest feature importance plot and final insights |

---

## 🔑 Key Concepts Covered

| # | Concept | What I Did |
|---|---------|------------|
| 1 | **Binary Classification** | Converted quality scores into Good (>=7) and Not Good (<7) |
| 2 | **Feature Scaling** | Applied StandardScaler for SGD and SVC models |
| 3 | **Model Comparison** | Trained and compared 3 different classifier models |
| 4 | **Confusion Matrix** | Evaluated True Positives, False Positives for each model |
| 5 | **Feature Importance** | Identified top chemical predictors using Random Forest |

---

## 🤖 Models Used

| Model | Approach | Scaling Required | Performance |
|-------|----------|-----------------|-------------|
| Random Forest | Ensemble of Decision Trees | No | Highest Accuracy |
| SGD Classifier | Stochastic Gradient Descent | Yes | Good |
| SVC | Support Vector Machine (RBF) | Yes | Good |

---

## 📈 Key Findings

| # | Finding |
|---|---------|
| 1 | ✅ Random Forest achieved the highest accuracy among all 3 models |
| 2 | ✅ Alcohol content is the strongest predictor of wine quality |
| 3 | ✅ Sulphates were identified as the second most important feature |
| 4 | ✅ StandardScaler significantly improved SGD and SVC performance |
| 5 | ✅ Most wines scored between 5 and 6 — class imbalance observed |
| 6 | ✅ Density and alcohol showed strong negative correlation |

---

## 🧠 What I Learned

- Real-world ML projects require careful preprocessing before model training
- Binary classification simplifies prediction and improves model accuracy
- Feature scaling is **critical** for distance-based models like SVC and SGD
- Random Forest is robust and works well **without scaling**
- Confusion matrices give deeper insight than accuracy score alone
- Feature importance plots help understand **which variables drive predictions**
- Google Colab is an efficient cloud platform for running ML experiments

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

---

## 🔗 Links

| Resource | Link |
|----------|------|
| 📓 Project Notebook | [NiharikaMaddali_Task6.ipynb](https://github.com/maddali23/OIBSIP/tree/main/Task6) |
| 🐙 GitHub Repository | [maddali23/OIBSIP](https://github.com/maddali23/OIBSIP/blob/main/Task6) |
| 🎥 Demo Video | [Add your LinkedIn post link here](#) |

---

*Task 6 — Wine Quality Prediction | Oasis Infobyte Data Analytics Internship*
*Intern: Maddali Naga Durga Niharika | VVIT | June 2026*
