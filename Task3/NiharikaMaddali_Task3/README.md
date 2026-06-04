# 🧹 Task 3 — Data Cleaning
### Oasis Infobyte | Data Analytics Internship | Level 1

![Task](https://img.shields.io/badge/Task-3-purple?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-1-pink?style=for-the-badge)
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
| **Project Title** | Data Cleaning on Real-World Datasets |
| **Level** | Level 1 — Task 3 |
| **Dataset 1** | New York City Airbnb Open Data (Kaggle) |
| **Dataset 2** | Trending YouTube Video Statistics (Kaggle) |
| **Tools Used** | Python, Pandas, NumPy, Matplotlib, Seaborn |
| **Platform** | Google Colab |

---

## 🎯 Objective

Data cleaning is the process of fixing or removing incorrect, corrupted, duplicate, or incomplete data within a dataset. Messy data leads to unreliable outcomes. The goal of this project is to clean and preprocess two real-world datasets by:

- Handling missing values
- Removing duplicate records
- Standardizing data formats
- Detecting and analyzing outliers

---

## 📂 Datasets Used

| # | Dataset | Source | Size |
|---|---------|--------|------|
| 1 | New York City Airbnb Open Data | [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) | ~48,895 rows |
| 2 | Trending YouTube Video Statistics | [Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new) | ~40,949 rows |

---

## 🪜 Steps Performed

| Step | Task | Description |
|------|------|-------------|
| 1️⃣ | **Data Loading** | Loaded both datasets into Pandas DataFrames using Google Colab |
| 2️⃣ | **Data Exploration** | Checked shape, data types, missing values, and duplicate rows |
| 3️⃣ | **Missing Value Handling** | Filled null values with appropriate defaults (Unknown, 0, No Review, No Description) |
| 4️⃣ | **Duplicate Removal** | Identified and removed duplicate records using `drop_duplicates()` |
| 5️⃣ | **Standardization** | Standardized text columns using `.str.strip()`, `.str.lower()`, `.str.title()` |
| 6️⃣ | **Data Type Fixing** | Converted date columns to datetime and numeric columns to proper types |
| 7️⃣ | **Outlier Detection** | Visualized outliers using Boxplots for price, nights, views, and likes |
| 8️⃣ | **Saving Results** | Saved cleaned datasets as new CSV files |

---

## 🔑 Key Concepts Covered

| # | Concept | What I Did |
|---|---------|------------|
| 1 | **Data Integrity** | Ensured accuracy and consistency throughout the cleaning process |
| 2 | **Missing Data Handling** | Used `fillna()` to impute missing values intelligently |
| 3 | **Duplicate Removal** | Used `drop_duplicates()` to maintain data uniqueness |
| 4 | **Standardization** | Applied consistent formatting across text and date columns |
| 5 | **Outlier Detection** | Used Seaborn Boxplots to identify abnormal values visually |

---

## 📊 Cleaning Summary

| Dataset | Original Rows | After Cleaning | Duplicates Removed | Missing Values Fixed |
|---------|--------------|----------------|--------------------|---------------------|
| NYC Airbnb | 48,895 | 48,895 | ✅ | ✅ |
| YouTube Trending | 40,949 | 40,949 | ✅ | ✅ |

---

## 📈 Outlier Detection Results

Boxplot analysis was performed on the following columns:

| Dataset | Column | Observation |
|---------|--------|-------------|
| Airbnb | Price | High-priced listings ($1000+) detected as outliers |
| Airbnb | Minimum Nights | Some listings required 1000+ nights — extreme outliers |
| YouTube | Views | Viral videos with billion+ views detected as outliers |
| YouTube | Likes | Few videos with extremely high likes — positive outliers |

---

## 🧠 What I Learned

- Real-world datasets are always messy — cleaning is the **most critical step** before analysis
- Missing values must be handled carefully based on column type (numeric vs text)
- `drop_duplicates()` helps maintain **data uniqueness** and prevents skewed results
- Standardizing text columns ensures **consistency** across the dataset
- **Boxplots** are the most effective way to visually identify outliers
- Working with large datasets (40K+ rows) requires efficient Pandas operations
- Google Colab is a powerful cloud-based environment for data analysis

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

---

## 🔗 Links

| Resource | Link |
|----------|------|
| 📓 Project Notebook | [NiharikaMaddali_Task3.ipynb](https://github.com/maddali23/OIBSIP/tree/main/Task3/NiharikaMaddali_Task3) |
| 🐙 GitHub Repository | [maddali23/OIBSIP](https://github.com/maddali23/OIBSIP) |
| 🎥 Demo Video | [Add your LinkedIn post link here](#) |

---

*Task 3 — Data Cleaning | Oasis Infobyte Data Analytics Internship*
*Intern: Maddali Naga Durga Niharika | VVIT | May 2026*
