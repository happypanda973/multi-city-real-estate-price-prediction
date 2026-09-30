# Multi-City Real Estate Price Prediction and Market Analysis

A machine learning project for analyzing residential real-estate data and predicting property prices across multiple Indian cities.

The project combines property datasets from Bengaluru and Mumbai into a common structure, performs data cleaning and feature engineering, explores market patterns through statistical and visual analysis, and develops regression models for property price prediction.

---

## Project Overview

Real-estate prices vary significantly depending on property characteristics, locality, area, and city.

The objective of this project is to build a data-driven pipeline that can:

- Integrate real-estate datasets from different cities
- Standardize different dataset structures
- Clean and preprocess real-estate data
- Handle missing values
- Extract useful features such as BHK
- Calculate price per square foot
- Analyze relationships between property features and price
- Compare real-estate characteristics across cities
- Perform statistical hypothesis testing
- Build machine learning regression models
- Predict residential property prices
- Provide a CLI-based property search and recommendation interface

---

## Cities Covered

Currently implemented:

- Bengaluru
- Mumbai

The preprocessing and integration pipeline is designed so that additional cities can be incorporated using the same standardized structure.

---

## Dataset

The project uses publicly available real-estate datasets.

### Bengaluru Dataset

The Bengaluru dataset contains:

- Area type
- Availability
- Location
- Size
- Society
- Total square feet
- Bathrooms
- Balconies
- Price

Original dataset size:

```text
13,320 rows × 9 columns
