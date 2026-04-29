# Gurgaon Real Estate Price Prediction Project

A comprehensive machine learning project for predicting real estate prices in Gurgaon, India.

## 📊 Project Overview

This project analyzes Gurgaon property data to build predictive models for real estate prices. It includes data preprocessing, exploratory data analysis, feature engineering, and multiple machine learning models.

## 📁 Project Structure

```
Realesate/
├── Data Files
│   ├── gurgaon_properties.csv          # Raw property data
│   ├── gurgaon_properties_cleaned_v1.csv
│   ├── gurgaon_properties_cleaned_v2.csv
│   ├── gurgaon_properties_missing_value_imputation.csv
│   ├── gurgaon_properties_outlier_treated.csv
│   ├── gurgaon_properties_post_feature_selection.csv
│   ├── gurgaon_properties_post_feature_selection_v2.csv
│   ├── flats.csv / flats_cleaned.csv  # Flat-specific data
│   ├── houses.csv / house_cleaned.csv  # House-specific data
│   ├── appartments.csv
│   └── data_viz1.csv
│
├── Notebooks - Data Preprocessing
│   ├── Data_preprocessing_flat.ipynb
│   ├── data-preprocessing-houses.ipynb
│   ├── data-preprocessing-level-2.ipynb
│   ├── data-preprocessing(2)-flats.ipynb
│   ├── missing-value-imputation.ipynb
│   ├── outlier-treatment.ipynb / outlier_treatment.ipynb
│   └── merge-flats-and-house.ipynb
│
├── Notebooks - Exploratory Data Analysis (EDA)
│   ├── eda_pandas_profiling.ipynb
│   ├── eda_univariate-analysis.ipynb
│   ├── eda-multivariate-analysis.ipynb
│
├── Notebooks - Feature Engineering
│   ├── feature-engineering.ipynb
│   ├── feature-selection.ipynb
│   ├── feature-selection-and-feature-engineering.ipynb
│
├── Notebooks - Model Building
│   ├── baseline model.ipynb
│   ├── besline_model.ipynb
│   ├── model-selection.ipynb
│   └── model-selection_r.ipynb
│
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

### Installation

1. Clone or download this repository
2. Install required packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

## 📈 Workflow

### 1. Data Preprocessing
- Clean raw property data
- Handle missing values
- Treat outliers
- Merge flats and houses datasets

### 2. Exploratory Data Analysis (EDA)
- Univariate analysis of individual features
- Multivariate analysis of feature relationships
- Pandas profiling for comprehensive overview

### 3. Feature Engineering
- Create new features from existing data
- Feature selection to identify important variables
- Encode categorical variables

### 4. Model Building
- Build baseline models
- Try multiple algorithms (Linear Regression, SVR, etc.)
- Evaluate and select best model

## 📊 Key Features

- **Property Type**: Flat / House
- **Bedrooms**: Number of bedrooms
- **Bathrooms**: Number of bathrooms
- **Built-up Area**: Property area in sq ft
- **Sector**: Location in Gurgaon
- **Furnishing Type**: Furnished / Unfurnished
- **Luxury Category**: Property luxury level
- **Floor Category**: Floor type

## 🎯 Project Goals

1. Clean and preprocess raw real estate data
2. Perform exploratory data analysis
3. Engineer meaningful features
4. Build accurate price prediction models
5. Provide insights into Gurgaon property market

## 📝 Notebooks Description

| Notebook | Purpose |
|----------|---------|
| `Data_preprocessing_flat.ipynb` | Preprocess flat data |
| `data-preprocessing-houses.ipynb` | Preprocess house data |
| `missing-value-imputation.ipynb` | Handle missing values |
| `outlier-treatment.ipynb` | Treat outliers |
| `eda_univariate-analysis.ipynb` | Single variable analysis |
| `eda-multivariate-analysis.ipynb` | Multi-variable analysis |
| `feature-engineering.ipynb` | Create new features |
| `feature-selection.ipynb` | Select important features |
| `baseline model.ipynb` | Build baseline model |
| `model-selection.ipynb` | Compare different models |

## 🤝 Contributing

Feel free to fork this project and add improvements!

## 📄 License

This project is for educational purposes.

## 👤 Author

Created as a learning project for real estate data analysis and machine learning.