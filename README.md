# 📊 Student Performance Prediction

An end-to-end Machine Learning project designed to analyze and predict student academic performance based on demographic, socioeconomic, and academic features. This project aims to help educational institutions identify students who need proactive support to improve their academic outcomes.

---

## 🚀 Project Overview

Predicting student performance is crucial for early intervention. This repository contains a complete data science workflow—from data cleaning and exploratory data analysis (EDA) to predictive modeling using advanced Machine Learning algorithms.

### Key Objectives:
* Identify the key factors (study hours, attendance, parental support, etc.) influencing student grades.
* Preprocess and engineer features for optimal model performance.
* Train and evaluate multiple ML models to predict final performance with high accuracy.

---

## 🛠️ Tech Stack & Tools

* **Language:** Python
* **Libraries:** * **Data Handling:** NumPy, Pandas
    * **Data Visualization:** Matplotlib, Seaborn
    * **Machine Learning:** Scikit-Learn
* **Environment:** Jupyter Notebook / VS Code

---

## 📊 Dataset Features

The model processes various features influencing a student's academic journey:

| Category | Features Included |
| :--- | :--- |
| **Demographic** | Gender, Age, Ethnicity |
| **Academic** | Attendance Rate, Study Hours per Week, Past Grades, Absence Count |
| **Socioeconomic** | Parental Education Level, Access to Resources, School Type |

---

## ⚙️ Machine Learning Workflow

### 1. Data Preprocessing & EDA
* Handled missing values and removed outliers to ensure data quality.
* Encoded categorical variables using **One-Hot Encoding** and **Label Encoding**.
* Applied **StandardScaler** to normalize numerical features for distance-based algorithms.
* Conducted correlation analysis to filter out redundant features.

### 2. Model Training
We implemented and compared multiple classification/regression models:
* **Logistic Regression / Linear Regression** (Baseline model)
* **Decision Trees & Random Forest** (To handle non-linear relationships)

### 3. Evaluation Metrics
Models were evaluated using industry-standard metrics to ensure robustness:
* **Classification:** Accuracy, Precision, Recall, and **F1-Score**.
* **Regression:** $R^2$ Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

---

## 📈 Key Insights & Results

* **Attendance Rate** and **Weekly Study Hours** showed the highest positive correlation with final grades.
* The **Random Forest Classifier** achieved the best performance with an overall **Accuracy of 82% (0.82)**.

---

## 💻 How to Run This Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)ZohaAsghar/student-performance-prediction.git
   cd student-performance-prediction
