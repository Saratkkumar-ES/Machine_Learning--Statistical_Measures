# Machine_Learning--Statistical_Measures
This project analyzes real estate prices in Bangalore using a dataset (house_price.csv). 
Bangalore House Price Analysis

This project involves data cleaning, outlier detection, and visualization on Bangalore house pricing data. The aim is to examine the `price_per_sqft` column using statistical techniques and graphical representations to better understand the distribution and patterns in the data.

---

## 📂 Dataset
- **File:** `house_price.csv`
- **Source:** Provided via Google Drive
- **Key Column:** `price_per_sqft`

---

## 📌 Objectives

### Basic EDA (Exploratory Data Analysis)
- Overview of data
- Handling null values
- Basic statistics

### Outlier Detection and Removal
Methods used:
- Mean and Standard Deviation
- Percentile Method
- IQR (Interquartile Range)
- Z-Score Method

Each method is applied and compared using box plots to evaluate their performance.

### Box Plot Comparison
- Compare results from each outlier method using box plots
- Identify the method that removes outliers most effectively

### Normality Check & Transformation
- Use `histplot` to check distribution
- Apply log transformation
- Check skewness and kurtosis before and after transformation

### Correlation Analysis
- Correlation matrix
- Heatmap for visual inspection

### Scatter Plot
- Visualize relationships between variables using scatter plots

---

## 🛠️ Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy.stats`

---

## 📈 Key Insights
- The **IQR method** provided the cleanest result in removing outliers.
- The `price_per_sqft` column was highly skewed and benefited from log transformation.
- Visualizations helped in understanding the distribution and relationships among variables.

---
