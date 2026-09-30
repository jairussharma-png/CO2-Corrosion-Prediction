# CO2 Corrosion Prediction

Machine-learning based prediction of internal CO2 corrosion rate in oil pipelines using XGBoost, Random Forest, and Gradient Boosting.

## Project Overview

This project uses machine-learning models to predict CO2 corrosion rates from operating conditions such as temperature, pressure, flow velocity, pH, and inhibitor efficiency.

## Dataset

The dataset contains 243 simulation-generated cases based on the NORSOK M-506 corrosion model and Monte Carlo simulation.

Variables include:

- Temperature
- Flow velocity
- CO2 pressure
- Internal pressure
- Inhibitor efficiency
- Shear stress
- pH
- Corrosion rate

**Source:** Mendeley Data  
**DOI:** 10.17632/4nydhxjymw.1

The dataset is simulation-generated and is not experimental or field data.

## Models

- XGBoost
- Random Forest
- Gradient Boosting
- Ensemble prediction

## Techniques

- Data preprocessing
- Exploratory data analysis
- Log-transformed regression
- Model evaluation
- Cross-validation
- SHAP explainability
- Remaining-life estimation

## Technologies

Python, Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn.

## Future Work

- Model deployment
- Improved uncertainty quantification
- Validation with experimental/field data
