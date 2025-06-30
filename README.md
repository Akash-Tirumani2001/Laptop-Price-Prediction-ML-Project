# Laptop-Price-Prediction-ML-Project
This project uses machine learning to predict the price of laptops based on key specifications such as RAM, storage type, processor, screen size, and brand. It includes data cleaning, exploratory data analysis, feature engineering, model training (Linear Regression, Random Forest), and performance evaluation.
Tools used include Python, Pandas, Scikit-learn, and Matplotlib, making it a great showcase for data science and regression modeling skills.
#  Laptop Price Prediction using Machine Learning

This project focuses on predicting the prices of laptops based on various hardware specifications using supervised machine learning algorithms. It includes data preprocessing, exploratory data analysis, model training, and evaluation.

---

##  Problem Statement

As laptop prices vary based on numerous specifications, it's helpful to predict the price range based on available configuration data. This model aims to assist sellers and buyers in estimating a fair price for a laptop based on features like brand, processor, RAM, storage, and display resolution.

---

##  Dataset Description

The dataset includes the following features:

- **Brand**  
- **Processor**  
- **RAM (in GB)**  
- **Storage (HDD/SSD)**  
- **Screen Size**  
- **Operating System**  
- **Display Resolution**  
- **Touchscreen (Yes/No)**  
- **Weight**  
- **Price (Target)**

---

##  Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Linear Regression, Random Forest Regressor)
- Jupyter Notebook

---

##  Model Building

The project includes:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature encoding (OneHotEncoder)
- Model training using:
  - Linear Regression
  - Random Forest Regressor
- Evaluation metrics:
  - R² Score
  - Mean Absolute Error (MAE)

---

## Results

| Model                  | R² Score | Mean Absolute Error |
|------------------------|----------|---------------------|
| Linear Regression      | ~0.51    | ~₹12,000            |
| Random Forest Regressor| ~0.63    | ~₹9,092             |

---
