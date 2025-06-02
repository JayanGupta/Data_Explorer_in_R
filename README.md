# Data Explorer in R using DataExplorer Package

This repository contains an R notebook demonstrating how to perform exploratory data analysis (EDA) using the `DataExplorer` package in R. The example dataset used here is the famous `penguins` dataset from the `palmerpenguins` package.

## Overview

Exploratory Data Analysis (EDA) is a critical step in understanding the structure, patterns, and quality of data before building any models. This project showcases various EDA techniques including:

- Data summary and structure overview
- Handling missing values
- Visualizing data distribution with histograms
- Visualizing data with boxplots grouped by categorical variables
- Inspecting missing data patterns

## Dataset

The dataset used in this analysis is `penguins` from the `palmerpenguins` package. It contains measurements for penguins across different species and islands.

## Usage

1. Install and load required packages:

```r
install.packages("DataExplorer")
install.packages("palmerpenguins")

library(DataExplorer)
library(palmerpenguins)
