# 🛍️ Black Friday Sales EDA & Data Cleaning

This repository contains an exploratory data analysis (EDA) and data cleaning workflow for the **Black Friday Sales Dataset**, a popular dataset from a retail dataset challenge.

## 📊 Project Objective

Analyze customer purchase behavior on Black Friday based on demographics and product categories, clean the data, and prepare it for predictive modeling.

---

## 📁 Dataset Description

The dataset consists of transactional records including:

- **User demographics**: Gender, Age, Occupation, City Category, etc.
- **Product details**: Product_ID, Product_Category_1/2/3
- **Target variable**: `Purchase` (amount spent)

Source: [Black Friday Dataset on Kaggle](https://www.kaggle.com/datasets/sdolezel/black-friday)

---

## 🧹 Key Steps in This Project

### 1. 📥 Data Loading
- Load train and test CSV files using Pandas.

### 2. 🧼 Data Cleaning
- Handle missing values in `Product_Category_2` and `Product_Category_3`.
- Convert categorical columns using label encoding if needed.
- Ensure proper datatypes.

### 3. 📊 Exploratory Data Analysis (EDA)
- Visualize purchase trends based on:
  - Age, Gender, City Category
  - Occupation, Marital Status
  - Product Categories

### 4. 📦 Feature Engineering (Optional)
- Encoding categorical variables
- Aggregating features if needed for modeling

---

## 🖼️ Sample Visualizations

- Average Purchase by Gender
- Purchase Distribution by Age Group
- Count of Product Categories Purchased
- Heatmaps and Boxplots

---

## 🛠️ Tools Used

- Python 🐍
- Pandas 📊
- Matplotlib & Seaborn 📈
- Jupyter Notebook 📓

---

## 🔮 Future Scope

- Build predictive models to estimate purchase amounts
- Try classification of high vs. low spenders
- Deploy a Streamlit or Dash dashboard for interactive EDA

---

## 🚀 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/black-friday-sales-eda.git
   cd black-friday-sales-eda
