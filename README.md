# Online-Retail-Data-Analysis
This project focuses on analyzing the UCI Online Retail dataset using Python. It covers data cleaning, exploratory data analysis (EDA), visualization with Matplotlib and Seaborn, and statistical testing using ANOVA. The goal is to uncover meaningful insights from retail sales data for better business decision-making.
# Online Retail Data Analysis with Python

This repository contains an **Online Retail Data Analysis project** using Python.  

The project demonstrates the full workflow of a data analyst:
- **Data cleaning and preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Visualization of trends and relationships**
- **Statistical testing (ANOVA)**

---

## Project Motivation
Retail businesses generate massive amounts of transactional data every day.  
However, raw data is often **messy and unstructured**.  

This project was created to:  
- Understand **customer behavior** through sales analysis  
- Identify **top-selling products and revenue trends**  
- Apply **statistical tests** to check if differences across groups (time, products, regions) are significant  
- Build a foundation for advanced applications such as customer segmentation and forecasting  

---

## Project File
- `Online_Retail_Data_Analysis.ipynb` → Jupyter Notebook containing the full analysis.  

---

## Project Workflow

### 1. Data Preprocessing
- Imported the dataset and inspected its structure.  
- Cleaned missing values and removed invalid or canceled transactions.  
- Converted `InvoiceDate` into datetime for time-based analysis.  
- Created a new feature:  
  - `TotalPrice = Quantity × UnitPrice` → Represents the revenue per transaction.  

### 2. Exploratory Data Analysis (EDA)
- Performed **descriptive statistics** (mean, median, variance, etc.).  
- Identified **high-value customers** and their purchase patterns.  
- Analyzed **seasonal sales trends** and product demand over time.  
- Compared sales across different **countries and regions**.  

### 3. Data Visualization
Created clear and interactive visualizations using **Matplotlib** and **Seaborn**:  
- **Time-series plots** → sales trends over months and quarters.  
- **Bar plots** → top-selling products and categories.  
- **Histograms** → purchase frequency distributions.  
- **Boxplots** → identifying outliers in sales transactions.  
- **Heatmaps** → correlation between numerical variables.  

### 4. Statistical Analysis (ANOVA)
- Applied **Analysis of Variance (ANOVA)** to test hypotheses such as:  
  - Are sales significantly different across countries?  
  - Do different product categories contribute unequally to revenue?  
  - Are seasonal differences in sales statistically meaningful?  
- Results provided evidence on whether observed differences are due to chance or actual business trends.  

---

## Tech Stack
- **Python 3.x**  
- **Libraries:**  
  - `pandas` – Data cleaning & manipulation  
  - `numpy` – Numerical computations  
  - `matplotlib` – Visualizations  
  - `seaborn` – Advanced plotting  
  - `statsmodels` – Statistical modeling and ANOVA  

---
