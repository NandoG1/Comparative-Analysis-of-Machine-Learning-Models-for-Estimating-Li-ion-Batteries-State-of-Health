# Comparative Analysis of Machine Learning Models for Estimating Li-ion Batteries State of Health

## Research Methodology In Computer Science Paper

## Overview

This research project focuses on comparing various machine learning models to estimate the State of Health (SoH) of Lithium-ion batteries. The study evaluates different algorithms MAE, RMSE, and R^2^ in predicting battery degradation, which is crucial for battery management systems.

## Dataset

The dataset used in this study is the NASA Battery Dataset, obtained from Kaggle. This dataset originally was provided by the Prognostics Center of Excellence (PCoE) Data Set Repository under NASA’s Intelligent Systems Division. It was later converted from .mat to .csv format for easier analysis.

Link: https://www.kaggle.com/datasets/patrickfleith/nasa-battery-dataset/data

## Methodology

The research use the following machine learning models for comparison:

- XGBoost
- Random Forest
- Support Vector Machine (SVM)

Performance metrics evaluated include:

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- R² Score

## Project Structure

- `code.ipynb`: Jupyter notebook containing all the code for data preprocessing, model implementation, and analysis
- `battery_health_dataset.csv`: The dataset used for training and testing the models
- `metadata.csv`: Additional metadata for the battery samples

## Implementation

The implementation includes:

1. EDA
2. Data preprocessing and feature engineering
3. Model training
4. Hyperparameter tuning
5. Performance evaluation
6. Visualization of results

## Requirements

- Python 3.x (3.10>=)
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## How to Run

1. Clone this repository
2. Install the required dependencies in Requirement
3. Open and run the Jupyter notebook: `jupyter notebook code.ipynb`

## Author

This research was conducted as part of the Research Methodology In Computer Science course.

## License

This project is for academic and research purposes.
