# Crime Prediction Project – Los Angeles Data

A comprehensive data mining project focused on preprocessing, exploring, and analyzing Los Angeles crime data from 2020 to present to build predictive models for crime forecasting.

## Project Overview

This project implements a complete data mining pipeline for predicting crime patterns in Los Angeles. It includes extensive data preprocessing, exploratory data analysis (EDA), statistical analysis, and visualization to prepare the dataset for machine learning models.

## Dataset

- **Source**: Crime Data from 2020 to Present (Los Angeles)
- **Features**: Multiple crime attributes including crime type, location, date, weapon used, victim demographics, and more
- **Purpose**: Identifying patterns and building predictive models for crime forecasting

## Project Workflow

### 1. Data Preprocessing & Exploration
- Load and inspect the raw crime dataset
- Analyze dataset structure (rows, columns, data types)
- Remove redundant columns (e.g., coded versions when descriptions are available)
- Handle duplicate records
- Clean and validate data quality
- Generate summary statistics

### 2. Exploratory Data Analysis (EDA)
- Statistical summaries of key variables
- Visualization of crime distribution patterns
- Analysis of temporal trends
- Geographic analysis of crime hotspots
- Demographic analysis
- Correlation analysis between variables

### 3. Feature Engineering & Preparation
- Data normalization and standardization where needed
- Categorical encoding
- Train-test data splitting
- Feature scaling using StandardScaler

### 4. Predictive Modeling
- Logistic Regression for binary classification
- Model training and evaluation
- Performance metrics and validation

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn (optional, for enhanced visualizations)
- mglearn

## Installation

1. Clone or download this repository
2. Install required dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn mglearn
   ```

## Usage

Open the Jupyter notebook to execute the analysis:
```bash
jupyter notebook "Data Mining Project_ Data Preprocessing & Exploration  (1).ipynb"
```

The notebook runs sequentially through:
1. Library imports
2. Dataset loading
3. Data preprocessing steps
4. Exploratory visualizations
5. Statistical analysis
6. Model preparation and training

## Key Features

- **Data Cleaning**: Removal of redundant columns and duplicate records
- **Comprehensive EDA**: Multiple visualization types including:
  - Distribution plots
  - Heatmaps and correlation analysis
  - Time series analysis
  - Geographical crime mapping
- **Statistical Analysis**: Summary statistics and pattern identification
- **ML-Ready Dataset**: Properly formatted and preprocessed data for modeling

## File Structure

```
data_mining/
├── README.md
└── Data Mining Project_ Data Preprocessing & Exploration  (1).ipynb
```

## Project Learnings

This project demonstrates:
- Data preprocessing best practices
- Exploratory data analysis techniques
- Handling messy real-world crime data
- Preparing data for machine learning models
- Data visualization and interpretation

## Future Enhancements

- Additional machine learning models (Random Forest, SVM, Neural Networks)
- Hyperparameter tuning and model optimization
- Time series forecasting for crime trends
- Advanced feature engineering
- Deployment of predictive model

## Notes

- Raw data file location: `C:/Users/laryeama/OneDrive - Seton Hall University/Desktop/Fall-2025/Data Mining/project/`
- This is an educational/test project for data mining course work
- Results should be interpreted in the context of crime data patterns and limitations

---

**Author**: Laryea M.  
**Date**: March 2026  
**Course**: Data Mining  
**Institution**: Seton Hall University
