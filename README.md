# Student Scores Project Using Machine Learning

An end-to-end Data Science project aimed at predicting student scores based on various demographic, socioeconomic, and academic features. This project heavily utilizes Exploratory Data Analysis (EDA) and predictive modeling to identify key factors influencing student success.

---

## Project Overview
Predicting student scores is crucial for educational institutions to provide timely interventions for students. This project implements a full machine learning pipeline—from raw data preprocessing to model evaluation—to accurately forecast scores.

## Technical Skills & Tools
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

---

## Data Pipeline & Methodology

### 1. Exploratory Data Analysis (EDA)
* Analyzed data distributions, missing values, and feature types.
* Visualized correlations between features and final student scores.
* Handled outliers and verified data integrity.

### 2. Data Preprocessing & Feature Engineering
* Handled categorical variables using appropriate encoding techniques.
* Scaled numerical features to ensure optimal model performance.
* Split the dataset into Training and Testing sets.

### 3. Predictive Modeling
Implemented and fine-tuned robust Machine Learning algorithms to compare performance:
* **Decision Trees:** To establish an interpretable, rule-based baseline model.
* **Random Forests:** An ensemble method used to reduce overfitting and improve predictive accuracy.

### 4. Evaluation Metrics
Models were evaluated using standard metrics to ensure reliability:
* Mean Absolute Error (MAE) / Mean Squared Error (MSE)
* R² Score / Accuracy Score

---

## Repository Structure
```text
├── Student scores project.ipynb   # Main Jupyter Notebook with full code and analysis
└── README.md                      # Project documentation (This file)
