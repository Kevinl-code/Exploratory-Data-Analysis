# Exploratory-Data-Analysis
Exploratory Data Analysis of the Titanic Survival Dataset using Python, Pandas, Seaborn, and Matplotlib.
# 🚢 Titanic Survival Dataset - Exploratory Data Analysis (EDA)

## 📘 Overview

This repository contains an Exploratory Data Analysis (EDA) of the famous **Titanic Survival Dataset** from Kaggle. The objective is to extract insights using statistical and visual techniques to understand which factors influenced passenger survival.

---

## 🎯 Objective

To explore and analyze the Titanic dataset using Python to uncover patterns, handle missing data, and identify key variables that contributed to passenger survival.

---

## 🧰 Tools & Technologies

- **Language**: Python 3
- **Libraries**:
  - `pandas`
  - `matplotlib`
  - `seaborn`
- **Platform**: Jupyter Notebook

---

## 📂 Dataset Description

| Column Name  | Description |
|--------------|-------------|
| PassengerId  | Unique identifier for each passenger |
| Survived     | Survival (0 = No, 1 = Yes) |
| Pclass       | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Name, Sex, Age | Basic personal information |
| SibSp, Parch | Family aboard |
| Ticket, Fare | Travel details |
| Cabin        | Cabin number (many missing values) |
| Embarked     | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

---

## 📊 Key Visualizations

- Survival distribution by **Sex**, **Class**, and **Embarked**
- **Age** and **Fare** histograms
- **Boxplots** showing survival vs age/fare
- **Correlation Heatmap** to observe feature relationships
- **Missing value handling**

---

## ✅ Key Findings

- **Females** had a higher chance of survival.
- **First-class passengers** survived more than third-class passengers.
- **Children** (age < 10) were prioritized during rescue.
- High **Fare** had a positive correlation with survival.
- Most passengers embarked from **Southampton**, but highest survival rate was from **Cherbourg**.

---

## 📄 Files

| File | Description |
|------|-------------|
| `EDA.ipynb` | Full Jupyter Notebook with code and visuals |
| `EDA_Titanic_Report.pdf` | PDF report version (optional) |
| `train.csv` | Titanic dataset used for analysis |

---

## 🔚 Conclusion

This project provides a comprehensive look at the Titanic dataset. The next step would be to apply machine learning techniques to predict survival based on the identified key features.

---
