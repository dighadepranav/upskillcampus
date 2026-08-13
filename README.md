# Prediction of Agricultural Crop Production in India

## Project Overview

This project focuses on predicting agricultural crop production in India using Machine Learning techniques.

The dataset contains information about different crops across five years (2006-07 to 2010-11), including:

- Production
- Area
- Yield

The project uses Area and Yield as input features to predict Crop Production.

## Dataset

- Number of crops: 55
- Number of observations after preprocessing: 275
- Years covered: 2006-07 to 2010-11
- Features used: Area and Yield
- Target variable: Production

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Linear Regression
- Random Forest Regression

## Machine Learning Models

Two regression models were implemented and evaluated:

1. Linear Regression
2. Random Forest Regression

### Model Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 7.856 | 11.725 | 0.960 |
| Random Forest | 4.970 | 8.711 | 0.978 |

Random Forest Regression achieved the better performance with an R² score of **0.978**.

## Feature Importance

The Random Forest model identified the following feature importance:

| Feature | Importance |
|---|---:|
| Yield | 0.90573 |
| Area | 0.09427 |

Yield was the most influential feature for predicting agricultural crop production in this dataset.

## Project Files

- `agriculture_crop_prediction.ipynb` — Jupyter Notebook containing the complete analysis and model implementation.
- `Data/datafile (2).csv` — Dataset used for the project.
- `agriculture_crop_production_model.pkl` — Trained Random Forest model.
- `AgriculturalCropPrediction_Pranav_USC_UCT.pdf` — Final internship project report.
- `REPORT.md` — Link to the final project report.

## Final Project Report

[View Final Project Report (PDF)](./AgriculturalCropPrediction_Pranav_USC_UCT.pdf)

## Internship

This project was completed as part of the Industrial Internship program conducted by upskill Campus, The IoT Academy and UniConverge Technologies Pvt Ltd.

## Author

**Pranav Dighade**