# Multi-City Real Estate Price Prediction and Market Analysis

A machine learning project that analyzes residential real-estate data from multiple Indian cities and predicts property prices using property characteristics and geographical information.

The project integrates publicly available datasets from **Bengaluru and Mumbai**, standardizes their structures, performs data cleaning and feature engineering, explores market patterns through statistical analysis and visualization, and develops regression models for property price prediction.

---

## Overview

Real-estate prices are influenced by several factors such as property size, number of bedrooms, bathrooms, location, property type, and the city in which the property is located.

This project aims to build a complete data-driven pipeline that transforms heterogeneous real-estate datasets into a unified dataset and uses it for both **market analysis and machine learning-based price prediction**.

The project covers:

- Multi-city dataset integration
- Data cleaning and preprocessing
- Missing-value analysis and imputation
- Feature engineering
- Exploratory Data Analysis (EDA)
- Outlier analysis
- Correlation analysis
- Statistical hypothesis testing
- Regression-based price prediction
- Comparison of different feature configurations
- CLI-based property search and price estimation

---

## Cities Covered

The current implementation covers:

- **Bengaluru**
- **Mumbai**

The data processing pipeline follows a common schema, allowing additional cities to be incorporated using the same approach.

---

## Dataset

The project uses publicly available real-estate datasets.

### Bengaluru

The Bengaluru dataset contains **13,320 properties** with the following attributes:

| Feature | Description |
|---|---|
| `area_type` | Type of area measurement |
| `availability` | Property availability status |
| `location` | Property locality |
| `size` | BHK / bedroom information |
| `society` | Society or project name |
| `total_sqft` | Total property area |
| `bath` | Number of bathrooms |
| `balcony` | Number of balconies |
| `price` | Property price in lakhs |

### Mumbai

The Mumbai dataset contains **11,146 records** with property information including:

| Feature | Description |
|---|---|
| `area_type` | Type of area measurement |
| `location` | Property locality |
| `size` | BHK / bedroom information |
| `total_sqft` | Total property area |
| `bath` | Number of bathrooms |
| `balcony` | Number of balconies |
| `price` | Property price in lakhs |

The original Mumbai spreadsheet contained additional unused columns, which were removed during preprocessing.

### Unified Dataset

Before integration, the datasets were standardized into a common structure:

```text
city
area_type
location
size
total_sqft
bath
balcony
price
