# 🚜 Bulldozer Price Prediction

A machine learning project that predicts the sale price of bulldozers using historical auction data. The project follows an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and model evaluation.

---

## 📌 Project Overview

The objective of this project is to build a regression model capable of accurately predicting the selling price of bulldozers based on their specifications, usage history, and auction details.

The project utilizes historical auction data from the Blue Book for Bulldozers dataset and applies various data preprocessing techniques before training a machine learning model.

---

## 🚀 Features

- Comprehensive Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Missing Value Handling
- Feature Engineering
- Date & Time Feature Extraction
- Categorical Feature Encoding
- Model Training and Evaluation
- Hyperparameter Tuning
- Price Prediction using Machine Learning

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Machine Learning Workflow

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Feature Engineering
5. Feature Selection
6. Model Training
7. Hyperparameter Optimization
8. Model Evaluation
9. Price Prediction

---

## 📈 Model

The project uses **Random Forest Regressor** as the primary prediction model due to its strong performance on tabular regression datasets.

### Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 📁 Project Structure

```
Bulldozer-price-prediction/
│
├── bluebook-for-bulldozers/
├── notebooks/
├── models/
├── bulldozer-price-prediction.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📂 Dataset

This project uses the **Blue Book for Bulldozers** dataset from the Kaggle competition.

**Dataset Link:**
https://www.kaggle.com/competitions/bluebook-for-bulldozers

> **Note:** The dataset is not included in this repository because it exceeds GitHub's file size limit. Please download it directly from Kaggle.

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Ayush-A-7505/Bulldozer-price-prediction.git
```

Move into the project directory

```bash
cd Bulldozer-price-prediction
```

Install the required packages

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📷 Results

The trained model successfully predicts bulldozer sale prices using historical auction data after preprocessing and feature engineering. Random Forest Regression achieved strong predictive performance on the validation dataset.

---

## 🎯 Future Improvements

- Deploy the model as a web application
- Experiment with XGBoost and LightGBM
- Build an interactive prediction interface
- Add model explainability using SHAP values

---

## 👨‍💻 Author

**Ayush Agrawal**

GitHub: https://github.com/Ayush-A-7505

---

## ⭐ If you found this project useful, consider giving it a star!
