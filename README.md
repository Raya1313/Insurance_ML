# 🛡️ Insurance_ML

![Python](https://img.shields.io/badge/Python-ML-blue)
![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)

A machine learning project that analyzes an insurance dataset and builds regression models to predict insurance charges.

---

## 📌 Project Overview

This repository contains a machine learning workflow that:

1. Loads and explores the insurance dataset.
2. Handles missing data and preprocesses features.
3. Encodes categorical variables.
4. Scales numerical features when needed.
5. Trains regression models.
6. Evaluates performance using common regression metrics.

The goal is to build models that can **predict insurance costs** based on policyholder information such as age, gender, BMI, smoking status, and more.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `insurance.csv` | The dataset containing insurance records and target values |
| `main.ipynb` | Jupyter Notebook with the full machine learning pipeline |
| `README.md` | Project overview and instructions (this file) |

---

## 🧠 Dataset Description

The dataset contains information about insurance policy holders. Common fields include:

- `age` – Age of the insured person  
- `sex` – Gender  
- `bmi` – Body Mass Index  
- `children` – Number of dependents  
- `smoker` – Whether the person smokes  
- `region` – Geographical region  
- `charges` – Insurance costs (target variable)

This dataset allows us to understand how these features influence insurance costs and build models accordingly.

---

## 🛠 Project Steps

### 1. Exploratory Data Analysis (EDA)
- Visualize feature distributions  
- Check for missing values  
- Understand relationships between variables

### 2. Data Preprocessing
- Handle missing values  
- Encode categorical features (e.g., gender, smoker status, region)  
- Scale numeric features (optional for linear regression)

### 3. Feature Target Split
Separate data into:
- **X**: Features  
- **y**: Target variable (`charges`)

### 4. Train-Test Split
Divide data into training and testing sets for unbiased evaluation.

### 5. Model Training
Train regression models, such as:
- **Linear Regression**
- **Polynomial Regression**

### 6. Evaluation
Evaluate models using:
- RMSE (Root Mean Squared Error)  
- R² Score  
- Visual comparison of predictions vs. actual values

---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/Raya1313/Insurance_ML.git
cd Insurance_ML
