# Multi-City Real Estate Price Prediction and Market Analysis

A machine learning project that analyzes residential real-estate data from **Bengaluru and Mumbai**, performs market analysis, and predicts property prices using property characteristics and geographical information.

## Overview

The project includes:

- Multi-city dataset integration
- Data cleaning and missing-value imputation
- Feature engineering
- Exploratory Data Analysis (EDA)
- Correlation and hypothesis testing
- Regression-based price prediction
- CLI-based property search and price estimation

## Machine Learning

The project evaluates:

- Linear Regression
- Ridge Regression
- Random Forest
- Gradient Boosting

**Random Forest** is used as the final prediction model.

### Linear Regression Baseline

| Metric | Result |
|---|---:|
| MAE | 47.46 lakhs |
| RMSE | 97.30 lakhs |
| R² Score | 0.72 |

- **MAE:** Average absolute prediction error.
- **RMSE:** Measures prediction error while giving more weight to larger errors.
- **R²:** Measures how much variation in property prices is explained by the model.

## CLI-Based Property Finder

The project includes an interactive CLI-based property finder where users can enter requirements such as:

- City
- BHK
- Maximum budget
- Preferred location
- Minimum area
- Bathrooms
- Property type

The system filters suitable properties based on the user's requirements and provides property suggestions along with ML-based price estimation.

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt 
```
2. Open Real_Estate_EDA_to_ML.ipynb.
3. Update the dataset paths in the notebook according to your local system:
bengaluru_path = "your/path/Bengaluru_House_Data.csv"
mumbai_path = "your/path/Mumbai_House_Data.xlsx"
4. Run the notebook cells sequentially.

### Note: The datasets are not included in the repository due to their large file size. Download them separately and update the file paths before running the notebook.

## Technologies Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy, Jupyter Notebook

Future Scope
Addition of more cities
Automated data acquisition
Web deployment
Periodic real-estate market updates

## Disclaimer

This project is developed for educational and analytical purposes using publicly available real-estate datasets. Predicted prices should not be considered professional property valuations.
