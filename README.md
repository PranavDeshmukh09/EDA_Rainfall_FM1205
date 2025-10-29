# 🌦️ Exploratory Data Analysis on Indian Rainfall (1901–2017)

**Project Title:** EDA on Rainfall Dataset (1901–2017)  
**Student Name:** Pranav Deshmukh  
**Roll No:** FM1205  
**Repository Name:** EDA_Rainfall_FM1205  

---

## 📘 Overview

This project performs an **Exploratory Data Analysis (EDA)** on India's rainfall data from **1901 to 2017**.  
The goal is to understand rainfall distribution patterns across **months, years, and subdivisions**, detect anomalies, and uncover insights about long-term rainfall behavior in India.

---

## 📊 Dataset Details

- **Dataset Name:** Rainfall in India (1901–2017)  
- **Source:** Indian Meteorological Department (IMD) Open Data Portal  
- **File Name:** `rainfall_data.csv`  
- **Shape:** 4188 rows × 19 columns  
- **Subdivisions:** 36 regions across India  
- **Years Covered:** 1901–2017  

Each row represents a subdivision’s monthly, seasonal, and annual rainfall (in millimeters).

---

## 🎯 Project Objectives

- Understand regional and temporal rainfall variation across India.  
- Identify missing, inconsistent, or extreme rainfall data points.  
- Analyze patterns and relationships between months and annual totals.  
- Support predictive modeling and long-term climate trend analysis.

---

## 🧹 Data Cleaning Summary

| Step | Action Taken |
|------|---------------|
| Missing Values | Imputed using mean rainfall of each month |
| Duplicates | None found |
| Negative Values | None found |
| Formatting | Standardized subdivision names and structure |

---

## 📈 Descriptive Statistics

- Mean and median rainfall values calculated for all months and seasons.  
- Variance and standard deviation show high variability during monsoon months.  
- Skewness indicates slightly right-skewed rainfall distributions.  
- Kurtosis reveals a few heavy-tailed distributions during peak monsoon.

---

## 📊 Visual Analysis

### 🔹 Univariate Analysis
- **Histograms** and **Boxplots** show rainfall spread and outliers.  
- **Distribution plots** confirm seasonal rainfall concentration.

### 🔹 Bivariate Analysis
- **Pairplots** reveal strong links between monthly and annual rainfall.  
- **Scatter plots** show linear patterns between monsoon and yearly totals.

### 🔹 Multivariate Analysis
- **Correlation Heatmap** (Seaborn) highlights:
  - Strong positive correlations among monsoon months (JUN–SEP).  
  - High correlation between `JJAS` (monsoon total) and `ANNUAL`.  
  - Weak correlation among pre- and post-monsoon months.

---

## 🌦️ Insights & Interpretation

### 🔸 Key Findings
- Dataset is clean and complete after imputation.  
- Monsoon months (`JUN–SEP`) dominate India’s annual rainfall.  
- Southern and northeastern subdivisions show significantly higher rainfall.  
- Western and northwestern regions receive minimal rainfall annually.

### 🔸 Trends & Anomalies
- Long-term fluctuations reflect natural monsoon variability.  
- Few outliers in coastal zones represent heavy rainfall years.  
- Declining patterns in certain regions could indicate early climate change signals.

### 🔸 Relationships Between Features
- Strong correlation between `JJAS` (monsoon) and `ANNUAL` rainfall totals.  
- Subdivisions group naturally into high-, medium-, and low-rainfall zones.  
- Season-wise rainfall influences total yearly patterns significantly.

### 🔸 Implications for Modeling
- Ideal for **time-series forecasting** (ARIMA, LSTM, Prophet).  
- Useful for **regional rainfall clustering** or **trend classification**.  
- Data can support **climate research and drought prediction studies**.

---

## 💾 How to Use

1. Clone the repository or download ZIP.  
2. Open `EDA_Rainfall_FM1205.ipynb` in **Google Colab** or **Jupyter Notebook**.  
3. Upload or mount the dataset file `rainfall_data.csv`.  
4. Run all cells sequentially to reproduce the full EDA workflow.

---

## 📂 Repository Structure
<br>
EDA_Rainfall_FM1205<br>
&nbsp;│<br>
&nbsp;├── EDA_Rainfall_FM1205.ipynb<br>
&nbsp;├── LICENSE<br>
&nbsp;├── README.md<br>
&nbsp;└── rainfall_data.csv<br>


---

## 🔗 Dataset Source

[Rainfall Dataset - Google Drive Link](https://drive.google.com/file/d/1fuhjzhTQOqNE-xK3ccwIi4r6uF7EZvEd/view?usp=drive_link))

---

## 🧾 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and share with attribution.

---

## 👨‍💻 Author

**Pranav Deshmukh**  
📘 Roll No: FM1205  
📧 *deshmukhpranav100@gmail.com*  
📅 Submitted as part of the EDA Project – 2025  

---

⭐ *This project explores over a century of rainfall data, revealing patterns that help understand India’s changing climate and seasonal rainfall behavior.*
