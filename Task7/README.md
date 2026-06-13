# 💳 Task 7 — Fraud Detection
### Oasis Infobyte | Data Analytics Internship | Level 2

![Task](https://img.shields.io/badge/Task-7-purple?style=for-the-badge)
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
| **Project Title** | Fraud Detection |
| **Level** | Level 2 — Project 3 |
| **Dataset** | creditcard.csv — Kaggle (mlg-ulb) |
| **Tools Used** | Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| **Platform** | Google Colab |

---

## 🎯 Objective

Fraud Detection involves identifying and preventing deceptive activities
within financial transactions using machine learning techniques. The goal
of this project is to distinguish between legitimate and fraudulent
transactions by:

- Performing exploratory data analysis on credit card transaction data
- Handling highly imbalanced dataset using undersampling technique
- Training Logistic Regression, Decision Tree, and Neural Network models
- Evaluating and comparing model performance using multiple metrics
- Identifying the most important features for detecting fraud

---

## 📂 Dataset Used

| # | Dataset | Source | Size |
|---|---------|--------|------|
| 1 | Credit Card Fraud Detection | [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) | 284,807 rows |

### Key Features

| Feature | Description |
|---------|-------------|
| Time | Seconds elapsed between transaction and first transaction |
| V1 — V28 | PCA transformed features (anonymous for privacy) |
| Amount | Transaction amount in euros |
| Class | Target variable (0 = Legitimate, 1 = Fraud) |

---

## 🪜 Steps Performed

| Step | Task | Description |
|------|------|-------------|
| 1️⃣ | **Import Libraries** | Imported Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| 2️⃣ | **Load Dataset** | Downloaded creditcard.csv via Kaggle API into Colab |
| 3️⃣ | **EDA** | Checked class distribution, transaction amounts, correlation heatmap |
| 4️⃣ | **Preprocessing** | Scaled Amount & Time, undersampling to balance classes, 80/20 split |
| 5️⃣ | **Model Training** | Trained Logistic Regression, Decision Tree, Neural Network models |
| 6️⃣ | **Model Evaluation** | Confusion matrices, accuracy bar chart, classification report |
| 7️⃣ | **Feature Importance** | Decision Tree feature importance plot and final insights |

---

## 🔑 Key Concepts Covered

| # | Concept | What I Did |
|---|---------|------------|
| 1 | **Anomaly Detection** | Identified unusual patterns in financial transaction data |
| 2 | **Class Imbalance Handling** | Used undersampling to balance fraud vs legitimate records |
| 3 | **Feature Scaling** | Applied StandardScaler on Amount and Time columns |
| 4 | **Model Comparison** | Trained and compared 3 different classifier models |
| 5 | **Confusion Matrix** | Evaluated True Positives and False Negatives for each model |

---

## 🤖 Models Used

| Model | Approach | Key Parameter | Performance |
|-------|----------|--------------|-------------|
| Logistic Regression | Linear Decision Boundary | max_iter=1000 | Good Baseline |
| Decision Tree | Tree-based Splitting | random_state=42 | High Accuracy |
| Neural Network (MLP) | Multi-layer Perceptron | hidden_layers=(64,32) | Highest Accuracy |

---

## 📊 Dataset Statistics

| Metric | Value |
|--------|-------|
| Total Transactions | 284,807 |
| Legitimate Transactions | 284,315 (99.83%) |
| Fraudulent Transactions | 492 (0.17%) |
| Features | 31 columns |
| After Undersampling | 984 rows (492 fraud + 492 legit) |

---

## 📈 Key Findings

| # | Finding |
|---|---------|
| 1 | ✅ Dataset was highly imbalanced — only 0.17% were fraud cases |
| 2 | ✅ Undersampling helped models learn fraud patterns effectively |
| 3 | ✅ Neural Network achieved the highest accuracy among all 3 models |
| 4 | ✅ V14, V17 and V12 were the strongest predictors of fraud |
| 5 | ✅ High Recall is more critical than Accuracy in fraud detection |
| 6 | ✅ StandardScaler on Amount and Time improved model performance |

---

## 🧠 What I Learned

- Real-world fraud datasets are **highly imbalanced** — only 0.17% fraud
- Undersampling is an effective technique to handle **class imbalance**
- In fraud detection, **Recall matters more than Accuracy** to avoid
  missing actual fraud cases
- Neural Networks can learn **complex patterns** that linear models miss
- PCA-transformed features (V1–V28) protect **user privacy** in banking
- Feature importance plots help identify **which variables detect fraud**
- Google Colab with Kaggle API makes downloading large datasets fast

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
| 📓 Project Notebook | [NiharikaMaddali_Task7.ipynb](https://github.com/maddali23/OIBSIP/tree/main/Task7) |
| 🐙 GitHub Repository | [maddali23/OIBSIP](https://github.com/maddali23/OIBSIP) |
| 🎥 Demo Video | [Add your LinkedIn post link here](#) |

---

*Task 7 — Fraud Detection | Oasis Infobyte Data Analytics Internship*
*Intern: Maddali Naga Durga Niharika | VVIT | June 2026*
