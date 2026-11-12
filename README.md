# Metal Alloy Lifespan & Defect Prediction

A machine learning project built to predict the lifespan and defect risks of industrial metal alloy parts using comprehensive exploratory data analysis (EDA), regression, and classification techniques.

---

## 🚀 Project Overview
This repository contains the coursework implementation for COMP1801. It evaluates multiple machine learning models to predict part durability based on chemical composition (Nickel, Iron, Cobalt, Chromium), processing parameters (cooling rate, quench time, forge time), and defect counts.

* **Dataset:** 1,000 recorded alloy part instances with 16 features.
* **Target Variables:** Continuous lifespan prediction (Regression) and categorical defect/failure classification.

---

## 📊 Key Results & Performance
* **Regression Models:** Evaluated Linear Regression, Decision Trees, and Random Forest. The **Random Forest Regressor** achieved strong predictive accuracy with an $R^2$ score of approximately **0.94**.
* **Classification Models:** Successfully classified part failure risks with high precision, achieving a strong ROC-AUC score of approximately **0.97**.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 
* **Data Processing & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (Random Forest, Decision Trees, Linear Models)
* **Data Visualization:** Matplotlib, Seaborn

---

## 📂 Repository Structure
```text
├── Dataset.csv
├── Report.pdf
├── Source code.ipynb
└── README.md
