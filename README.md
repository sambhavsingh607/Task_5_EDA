# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover insights about passengers, their demographics, and survival patterns.  
Using **Python (Pandas, Matplotlib, Seaborn)**, the analysis explores relationships between features such as age, gender, passenger class, fare, and survival status.

---

## 🎯 Objectives
- Explore dataset structure and clean missing values.
- Perform **univariate, bivariate, and multivariate analysis**.
- Visualize patterns, relationships, and anomalies.
- Derive key insights about factors influencing survival.

---

## 🛠️ Tools & Libraries
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset
The dataset used is from the [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data).  
Files included:
- `train.csv` → Training dataset (with survival labels).
- `test.csv` → Test dataset (without survival labels).
- `gender_submission.csv` → Sample submission file.

---

## 🔍 EDA Workflow
1. **Data Loading & Inspection**
   - Used `.info()`, `.describe()`, `.isnull().sum()` to check structure & missing values.
2. **Univariate Analysis**
   - Countplots, histograms, and boxplots for categorical & numerical features.
3. **Bivariate Analysis**
   - Survival rates vs. Gender, Pclass, Age, Embarked.
4. **Multivariate Analysis**
   - Correlation heatmap & pairplots to study feature relationships.
5. **Handling Missing Data**
   - Filled `Age` with median, `Embarked` with mode, dropped `Cabin`.
6. **Insights & Findings**
   - Women and 1st-class passengers had higher survival rates.
   - Higher fares correlated with higher survival probability.
   - Most missing data was in the `Cabin` column.

---

## 📊 Key Visuals
- Survival by **Sex** (women had higher survival chances).
- Survival by **Pclass** (1st class > 3rd class).
- Age distribution of survivors vs non-survivors.
- Correlation heatmap showing relationships between numeric features.

---

## 📌 Deliverables
- **Jupyter Notebook** → Complete EDA process with code, plots, and observations.
- **PDF Report** → Summary of analysis and key findings (exported from notebook).

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/titanic-eda.git
   cd titanic-eda
<img width="803" height="535" alt="image" src="https://github.com/user-attachments/assets/2246621a-8010-43b4-8783-fa0dbf01f184" />
<img width="918" height="714" alt="image" src="https://github.com/user-attachments/assets/e8941914-31d0-46b3-b1a9-13bef66a1814" />

