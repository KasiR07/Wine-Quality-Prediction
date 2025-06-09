# 🍷 Wine Quality Prediction

This project uses **machine learning algorithms** to predict the quality of wine based on physicochemical tests. Built with Python, the model helps in identifying wine quality on a scale of 0–10 using features such as alcohol content, acidity, sugar levels, and more.

---

## 📌 Objective

To build a predictive model that classifies wine as **high or low quality** based on measurable chemical attributes. This project leverages classification techniques to help winemakers and analysts better understand factors influencing wine quality.

---

## 📊 Dataset Information

- **Source:** UCI Machine Learning Repository  
  [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

- **Features Include:**
  - Fixed acidity
  - Volatile acidity
  - Citric acid
  - Residual sugar
  - Chlorides
  - Free sulfur dioxide
  - Total sulfur dioxide
  - Density
  - pH
  - Sulphates
  - Alcohol
  - Quality (target)

---

## 🧰 Tech Stack

- **Language:** Python 3.x  
- **Libraries:**
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`
  - `xgboost` *(if used)*
  - `joblib` *(for model saving)*

---

## 📁 Project Structure

Wine-Quality-Prediction/
├── wine_quality.ipynb # Main analysis and modeling notebook
├── winequality-red.csv # Dataset used
├── requirements.txt # Python dependencies
└── README.md


---

## 📈 Model Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Feature normalization
   - Label encoding (if applicable)

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmaps
   - Pairplots
   - Distribution analysis

3. **Modeling**
   - Logistic Regression
   - Random Forest Classifier
   - Gradient Boosting / XGBoost
   - Evaluation using Accuracy, Precision, Recall, F1 Score

4. **Model Selection**
   - Based on best cross-validation performance
   - Final model persisted using `joblib`

---
## Visualizations
![image](https://github.com/user-attachments/assets/96885804-aaa5-4031-8dca-006e012b2d6a)

![image](https://github.com/user-attachments/assets/45fb74bb-e30a-47bc-9437-10026a251e2c)

