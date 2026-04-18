<div align="center">
  
  # 📊 Data Explorer in R using DataExplorer

  [![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://www.r-project.org/)
  [![DataExplorer](https://img.shields.io/badge/DataExplorer-00BFC4?style=for-the-badge)](https://cran.r-project.org/package=DataExplorer)
  [![EDA](https://img.shields.io/badge/EDA-Analysis-blue?style=for-the-badge)]()
  [![Visualization](https://img.shields.io/badge/Data--Visualization-orange?style=for-the-badge)]()

  *An exploratory data analysis (EDA) project in R using automated visualization and reporting tools.*
</div>

---

## 📖 Overview
This project demonstrates how to perform **Exploratory Data Analysis (EDA)** in R using the `DataExplorer` package.  

It focuses on understanding dataset structure, identifying missing values, and generating meaningful visualizations and reports using minimal code.

---

## 🚀 Features
- 📋 Data structure and summary analysis  
- ❗ Missing value detection and visualization  
- 📈 Distribution analysis using histograms  
- 📦 Boxplots for grouped comparisons  
- 🔗 Correlation analysis for numerical features  
- 📄 Automated HTML report generation  

---

## 📊 Dataset
- **Dataset Used:** `penguins`  
- **Source:** `palmerpenguins` package  

### 🧾 Dataset Description
The dataset includes:
- Penguin species classification  
- Island location  
- Physical measurements (bill length, flipper length, body mass)  
- Gender information  

---

## ⚙️ Installation

Run the following commands in R:

```r
install.packages("DataExplorer")
install.packages("palmerpenguins")

library(DataExplorer)
library(palmerpenguins)
```
---

## 🚀 How to Use

1. Open the `Data_explorer_in_r.ipynb` notebook  
2. Execute all cells sequentially to reproduce the analysis  
3. Explore key outputs, including:
   - Data summary and structure  
   - Missing value analysis  
   - Distribution visualizations (histograms)  
   - Comparative visualizations (boxplots)  

4. Generate a comprehensive automated report using:
   ```r
   create_report(penguins)
   ```
