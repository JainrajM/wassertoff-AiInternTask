# AI Internship Task – Solar Flare Prediction

## Problem Statement
Predict the integrated flux of solar flares using GOES-16 X-ray satellite data.

## Dataset
- Source: Kaggle
- Features used: xrsb_flux, background_flux, flare_class, etc.

## Preprocessing
- Removed outliers using LOF
- log1p transformation on xrsb_flux
- Feature engineering (flux ratio)
- KNN imputation for missing values

## Models
- Random Forest Regressor
- XGBoost Regressor (R² = 0.8298)

## Evaluation
- XGBoost:
  - R² Score: 0.8298
  - MSE: 0.000008

## Tools
- Python, scikit-learn, XGBoost, Kaggle

## Author
Jainraj M
