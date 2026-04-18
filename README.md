# 📊 Data Explorer in R using DataExplorer

This repository demonstrates how to perform **Exploratory Data Analysis (EDA)** in R using the `DataExplorer` package. It includes a hands-on notebook, an example HTML report, and a structured workflow using the `penguins` dataset.

---

## 📁 Repository Structure
```text
.
├── Data_explorer_in_r.ipynb # R Notebook with step-by-step EDA
├── report_example.html # Auto-generated EDA report
├── README.md # Project documentation
```

---

## 🔍 Overview

Exploratory Data Analysis (EDA) is a foundational step in any data science workflow. This project focuses on:

- Understanding dataset structure  
- Identifying missing values  
- Visualizing distributions  
- Detecting outliers  
- Generating automated reports  

---

## 🐧 Dataset

The dataset used is the **`penguins` dataset** from the `palmerpenguins` package.

It includes:
- Species classification  
- Island information  
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
