# 🛍️ Black Friday Sales EDA, Visualization & Feature Selection

This project provides a comprehensive analysis of the **Black Friday Sales Dataset**, including data cleaning, exploratory data analysis (EDA), visualizations, and feature selection. It's a perfect hands-on example for anyone looking to understand retail consumer behavior and build predictive models using real-world data.

---

## 📌 Project Objective

Analyze purchase behavior based on customer demographics and product categories, clean the dataset, explore key trends using visualization, and prepare the data with selected features for machine learning models.

---

## 📁 Dataset Description

The dataset contains the following:

- **User Demographics**:  
  - `User_ID`, `Gender`, `Age`, `Occupation`, `City_Category`, `Stay_In_Current_City_Years`, `Marital_Status`

- **Product Information**:  
  - `Product_ID`, `Product_Category_1`, `Product_Category_2`, `Product_Category_3`

- **Target Variable**:  
  - `Purchase` — amount spent by the customer

📦 **Source**: [Black Friday Dataset on Kaggle](https://www.kaggle.com/datasets/sdolezel/black-friday)

---

## 🔍 Project Workflow

### 1. 📥 Data Loading
- Loaded `train.csv` and `test.csv` using Pandas.

### 2. 🧼 Data Cleaning
- Checked for missing values.
- Handled nulls in `Product_Category_2` and `Product_Category_3` using imputation.
- Verified column types and converted where needed.
- Removed redundant or unnecessary columns.

### 3. 📊 Exploratory Data Analysis (EDA)
- Summary statistics and data types
- Purchase patterns grouped by:
  - Gender
  - Age group
  - Marital status
  - Occupation
  - City category

### 4. 📈 Data Visualization

#### 🧍 Demographics vs Purchase:
- **Bar plots**: Average purchase by gender, age, occupation
- **Box plots**: Purchase distribution across city categories and age groups

#### 📦 Product Insights:
- Most popular product categories (1, 2, 3)
- Product category frequency charts

#### 📉 Correlations:
- Heatmap of feature correlations
- Distribution of purchase amounts

### 5. 🧠 Feature Engineering
- Label encoding of categorical variables: Gender, Age, City_Category, Stay_In_Current_City_Years
- Derived new features (optional): e.g., total number of product categories interacted with

### 6. 🔍 Feature Selection
- Used:
  - Correlation matrix
  - Univariate feature importance
  - Tree-based model feature importance (optional)
- Selected most relevant predictors for modeling

---


---

## 🛠️ Tools & Libraries Used

- Python 3.x  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🚀 How to Run This Project

 **Clone the repository**
```bash
git clone https://github.com/yourusername/black-friday-sales-eda.git
cd black-friday-sales-eda
