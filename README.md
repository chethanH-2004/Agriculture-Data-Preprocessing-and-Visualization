# 🌾 Agriculture Data Preprocessing and Exploratory Data Analysis

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-cyan?style=for-the-badge)

### 📊 Data Preprocessing • 📈 Visualization • 🔍 Exploratory Data Analysis

</div>

---

# 📌 Project Overview

This project focuses on preprocessing and analyzing an Indian agriculture dataset using Python. The dataset contains agricultural information such as crop production, cultivated area, yield, seasons, and states.

The project applies various preprocessing and exploratory data analysis (EDA) techniques to clean the dataset, handle skewness and outliers, and uncover meaningful agricultural insights.

---

# 🌱 Introduction

Agriculture is one of the most important sectors contributing to the Indian economy, employment generation, and food security. Agricultural productivity varies across different states, crops, seasons, and climatic conditions. Understanding these variations is essential for improving crop productivity, agricultural planning, and resource management.

With the increasing availability of agricultural data, data analytics and visualization techniques can help identify production trends, seasonal patterns, and regional differences in yield and production. These insights are valuable for farmers, agricultural businesses, policymakers, and researchers.

This project focuses on preprocessing and analyzing agricultural data to improve data quality and derive meaningful insights using Exploratory Data Analysis (EDA) techniques.

---

# 🎯 Problem Statement

Agricultural datasets often contain missing values, inconsistent records, skewed distributions, and extreme outliers, which make analysis and interpretation difficult.

From an agricultural and business perspective, understanding the relationship between cultivated area, crop production, and yield is important for improving productivity, planning agricultural activities, and supporting data-driven decision-making.

The objective of this project is to preprocess the agricultural dataset, handle inconsistencies and skewness, and perform exploratory data analysis to identify meaningful patterns and relationships among Area, Production, and Yield variables.

---

# 🛠️ Methodology

The project was carried out using the following methodology:

## 1️⃣ Data Collection and Loading
- Dataset imported using Pandas
- CSV file loaded into Jupyter Notebook

---

## 2️⃣ Data Preprocessing
- Missing value handling
- Duplicate verification
- Inconsistency correction
- Data type conversion
- Outlier detection using IQR method
- Clipping of extreme values
- Logarithmic transformation for skewness reduction

---

## 3️⃣ Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis
- Histogram
- Boxplot
- Countplot

### 🔹 Bivariate Analysis
- Scatter plots
- Bar plots
- Seasonal comparisons

### 🔹 Multivariate Analysis
- Pairplot
- Correlation heatmap

---

## 4️⃣ Feature Selection
- Removed low-information categorical column (`Production Units`)

---

## 5️⃣ Encoding
- Encoded categorical variables for preprocessing and analysis

---

## 6️⃣ Scaling
- Applied scaling techniques to numerical variables

---

# 📂 Dataset Description

The dataset contains agricultural information collected from different states and districts across multiple years and seasons in India.

| Feature | Description |
|---|---|
| State | Name of the state |
| District | Name of the district |
| Crop | Type of crop cultivated |
| Year | Agricultural year |
| Season | Crop growing season |
| Area | Cultivated land area |
| Production | Total crop production |
| Yield | Crop productivity |

---

# 📥 Data Acquisition Methods


The dataset used in this project was obtained from Kaggle and contains agricultural crop production information across different states, districts, crops, and seasons in India.

🔗 Dataset Source:  
https://www.kaggle.com/datasets/pyatakov/india-agriculture-crop-production

The dataset was downloaded in CSV format and imported into Python using the Pandas library for preprocessing and exploratory data analysis.

The dataset includes:
- crop production information
- cultivated area details
- agricultural yield values
- seasonal crop data
- state and district-wise records
  
---

# 📊 Analysis

# 🔹 Missing Value Handling

Missing values were identified and treated appropriately to maintain consistency and improve dataset quality.

### ✔ Key Findings
- Missing values were present in numerical and categorical variables.
- Appropriate preprocessing techniques were applied to handle missing records.

---

# 🔹 Duplicate Verification

The dataset was checked for duplicate records during preprocessing.

### ✔ Key Findings
- No duplicate records were found in the dataset.
- The dataset maintained good consistency and uniqueness.

---

# 🔹 Inconsistency Handling

Categorical inconsistencies in variables such as State, District, Crop, and Season were corrected.

### ✔ Key Findings
- Standardized categorical values improved data consistency.
- Data became easier to analyze and visualize.

---

# 🔹 Outlier Detection and Skewness Reduction

Outliers in numerical variables were identified using the Interquartile Range (IQR) method.

Clipping was initially applied to reduce the influence of extreme observations. However, the variables still exhibited positive skewness after clipping. Therefore, logarithmic transformation was applied to further reduce skewness and improve distribution balance.

### ✔ Key Findings
- Area and Production were initially highly skewed.
- Log transformation significantly improved distributions.
- Yield remained moderately skewed due to natural agricultural variability.

---

# 🔹 Univariate Analysis

Univariate analysis was performed to understand the distribution and spread of individual variables.

## 📈 Techniques Used
- Histogram
- Boxplot
- Countplot

### ✔ Key Findings
- Area and Production achieved near-normal distributions after preprocessing.
- Yield retained moderate skewness.
- Seasonal distributions highlighted dominant agricultural seasons.

---

# 🔹 Bivariate Analysis

Bivariate analysis was conducted to study relationships between variables.

## 📈 Visualizations Used
- Scatter plots
- Bar plots
- Seasonal comparisons

### ✔ Key Findings
- Area and Production exhibit positive correlation.
- Larger cultivation areas generally result in higher production.
- Seasonal variations in agricultural productivity were observed.

---

# 🔹 Multivariate Analysis

Multivariate analysis was performed using pairplots and correlation heatmaps.

## 📈 Visualizations Used
- Pairplot
- Correlation heatmap

### ✔ Key Findings
- Production showed moderate relationship with Yield.
- Area had weaker correlation with Yield.
- No strong multicollinearity was observed.

---

# 📷 Sample Visualizations

## 📌 Univariate Analysis
- Distribution plots
- Boxplots

## 📌 Bivariate Analysis
- Scatter plots
- Seasonal bar plots

## 📌 Multivariate Analysis
- Pairplot
- Correlation heatmap

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Preprocessing & Scaling |
| Jupyter Notebook | Development Environment |

---

# 📌 Conclusion

The agricultural dataset was successfully preprocessed and analyzed using various data preprocessing and visualization techniques.

Missing values and inconsistencies were handled effectively, while clipping and logarithmic transformation improved the distributions of numerical variables significantly.

The analysis revealed meaningful relationships among cultivated area, production, and yield, along with seasonal and regional agricultural variations. Overall, the project demonstrates the importance of preprocessing and exploratory data analysis in understanding agricultural trends and improving data quality for future analytical applications.

---

# 📚 References

1. Pandas Documentation  
   https://pandas.pydata.org/

2. NumPy Documentation  
   https://numpy.org/

3. Matplotlib Documentation  
   https://matplotlib.org/

4. Seaborn Documentation  
   https://seaborn.pydata.org/

5. Scikit-learn Documentation  
   https://scikit-learn.org/

---

# 👨‍💻 Author

### Chethan H

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star ⭐

</div>
