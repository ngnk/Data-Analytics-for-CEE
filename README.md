# Data Analytics for Civil Engineering: Machine Learning for Seismically Induced Landslides and Sea Level Rise

## Overview
This project applies **machine learning techniques** to predict **seismically induced landslides** and **sea level rise**, leveraging **data analytics** to assess risks and model future scenarios. It is divided into two key sections:

1. **Seismically Induced Landslides** - Using **logistic regression, multilinear regression, and LASSO feature selection** to predict landslide displacement after an earthquake.
2. **Sea Level Change Analysis** - Utilizing **Gaussian processes and regression models** to analyze and forecast sea level rise based on tidal gauge data.

---

## Seismically Induced Landslides
### Objective
- Understand the relationship between **earthquake parameters** and **landslide displacement**.
- Develop **predictive models** to estimate displacement based on earthquake characteristics.

### Data & Features
The dataset includes:
- **Slope Properties**: Shear-wave velocity (Vs30), yield coefficient (Ky), fundamental period (T)
- **Ground Motion**: Peak ground acceleration (PGA), Peak ground velocity (PGV), Spectral acceleration (Sa)
- **Earthquake Data**: Magnitude (M), Closest distance (ClstD), and Displacement (Disp)

### Model Development
- **Feature Selection**: Stepwise regression, LASSO.
- **Classification Model**: **Logistic regression** to classify displacement occurrence.
- **Prediction Model**: **Multilinear regression** to estimate displacement.
- **Alternative Model**: **Nonlinear regression** to capture better patterns.

### Key Insights
- **PGV (Peak Ground Velocity)** was the best predictor for displacement.
- **Linear models underperformed**, as landslide displacement exhibits **nonlinear** trends.
- **Machine learning can improve risk assessment**, but over-simplified models can lead to underestimation of hazards.

---

## Sea Level Change Analysis
### Objective
- Analyze **50 years of tidal gauge data** and assess **long-term sea level trends**.
- Develop **machine learning models** to predict future sea levels.

### Data & Features
- **Cities analyzed**: San Francisco, Los Angeles, New York, and Savannah.
- **Data Sources**: NOAA tidal gauge records (monthly and hourly data).
- **Key Factors**: Seasonal fluctuations, thermal expansion, tidal variations.

### Model Development
- **Baseline Models**: Ridge, LASSO, Random Forest Regression.
- **Gaussian Process Models**:
  - **Single Kernel** (Exponential)
  - **Compound Kernel** (Periodic + Exponential)

### Key Insights
- **Sea levels are rising across all locations**, with more pronounced changes post-2015.
- **West Coast sea levels** are higher due to regional oceanic and geological factors.
- **Seasonal variations** affect tides, with peaks in summer and troughs in winter.
- **Machine learning can forecast trends** but must account for **periodic fluctuations** for better accuracy.

---
## Authors
- **TN**
- **HL**
- **SR**
- **MS**
