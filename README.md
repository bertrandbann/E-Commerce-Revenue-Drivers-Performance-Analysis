#  E-Commerce Revenue Drivers & Performance Analysis

##  Project Overview

This project analyses e-commerce transactional data to identify the key drivers of revenue and understand how pricing, product mix, customer behaviour, and market conditions influence business performance.

The goal of the project is to move beyond descriptive dashboards and use statistical modelling to quantify what truly drives revenue.

---

##  Objectives

* Identify the most important factors influencing revenue performance
* Quantify the impact of pricing, product categories, and customer behaviour
* Understand the relationship between discounts, product mix, and revenue
* Use regression analysis to derive actionable business insights

---

##  Dataset Description

The dataset contains transactional-level e-commerce data including:

* Customer demographics (age, gender)
* Product categories and brand type
* Geographic regions (states)
* Pricing information (base price, discount, final price)
* Units sold and revenue
* Market conditions (competition intensity, inventory pressure)

---

## 🛠 Tools & Technologies

* **Python**

  * Pandas & NumPy (data manipulation)
  * Matplotlib & Seaborn (visualisation)
  * Statsmodels (regression modelling & diagnostics)
* Jupyter Notebook

---

##  Methodology

### 1️⃣ Data Preparation

* Cleaned and structured transactional data
* Encoded categorical variables using dummy variables
* Applied log transformation to revenue to stabilise variance and reduce skewness

### 2️⃣ Exploratory Data Analysis (EDA)

* Analysed distributions and relationships between key variables
* Used correlation analysis and visual exploration to understand data patterns

### 3️⃣ Regression Modelling

* Applied Ordinary Least Squares (OLS) regression to identify revenue drivers
* Interpreted coefficients to understand the impact of each factor

### 4️⃣ Model Diagnostics

* Residual analysis and Q-Q plots to check model assumptions
* Breusch–Pagan test for heteroskedasticity
* Variance Inflation Factor (VIF) to assess multicollinearity
* Cook’s distance to identify influential observations

---

## 💡 Key Insights

* Sales volume is the strongest driver of revenue
* Premium product categories significantly outperform lower-value categories
* Discounting does not necessarily lead to higher revenue and may negatively impact performance
* Product mix and operational factors have a meaningful impact on revenue outcomes

---

## ⚠️ Limitations

* The analysis assumes linear relationships between variables
* External factors such as macroeconomic conditions were not included
* Results are based on historical data and may not fully predict future performance

---

## 🚀 Future Improvements

* Explore non-linear models such as tree-based methods or machine learning models
* Incorporate additional external data sources
* Test interaction effects between key variables

---

## 📌 Key Takeaway

This project demonstrates that effective decision-making requires more than dashboards alone. By combining visual analytics with statistical modelling, it is possible to gain deeper, more actionable insights into business performance.

---

## 📁 Project Files

* `E-Commerce Revenue Drivers & Performance Analysis.ipynb` — main analysis notebook
