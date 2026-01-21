# ✈️ Customer Travel Data Analysis

## 📌 Project Overview
This project focuses on analyzing a customer travel dataset using **Data Science techniques**.  
The goal is to clean, manipulate, analyze, and visualize travel-related data to extract meaningful insights such as flight delay patterns, travel behavior, and service impact on customer experience.

---

## 🎯 Objectives
- Clean and preprocess raw travel data  
- Perform exploratory data analysis (EDA)  
- Identify relationships between flight distance and arrival delays  
- Visualize key patterns using charts and plots  
- Generate insights that can support decision-making in the travel industry  

---

## 🗂 Dataset Description
The dataset contains customer travel information, including:
- Flight Distance  
- Arrival Delay in Minutes  
- Type of Travel  
- Inflight WiFi Service Rating  
- Other customer and flight-related attributes  

> **Note:** The dataset was loaded from a CSV file and processed using Python.

---

## 🛠️ Technologies & Tools Used
- **Programming Language:** Python  
- **Libraries:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
- **Environment:** Jupyter Notebook / VS Code  

---

## 🔄 Project Workflow

### 1. Data Loading & Cleaning
- Loaded dataset from CSV file  
- Handled missing values using `fillna()` and row removal  
- Removed duplicate records for data consistency  

### 2. Data Manipulation
- Filtered flights with distance greater than 150  
- Grouped data by flight distance  
- Calculated mean values of numeric features  

### 3. Data Analysis
- Generated descriptive statistics using `describe()`  
- Performed correlation analysis on numerical columns  

### 4. Data Visualization
The following visualizations were created:
- 📊 Bar Plot – Arrival Delay vs Flight Distance  
- 📈 Line Plot – Flight Distance vs Arrival Delay  
- 📉 Histogram – Distribution of Flight Distance  
- 🔵 Scatter Plot – Relationship between Distance and Delay  
- 📦 Box Plot – Outlier detection in Flight Distance  
- 📶 Bar Plot – Inflight WiFi Service vs Type of Travel  

---

## 📊 Key Insights
- Longer flight distances may have a correlation with higher arrival delays  
- Service quality (Inflight WiFi) appears to vary by type of travel  
- Data visualization helped identify trends, patterns, and outliers  

---

## 🚀 Future Enhancements
- Apply statistical hypothesis testing for stronger conclusions  
- Build machine learning models to predict:
  - Arrival delays  
  - Customer satisfaction  
- Explore additional features for deeper insights  


