# Agricultural-Yield-Prediction-using-Multiple-Linear-Regression
A machine learning project focused on predicting agricultural yield (Standardized Yield) using geographic, weather, and soil features through Multiple Linear Regression, feature engineering, and model evaluation techniques.
# Agricultural Yield Prediction Analysis

## Project Overview
This project involves a comprehensive analysis of an agricultural dataset to predict crop yields. By decoding the intricate connections between geographic, weather, soil, and farm management features, this analysis empowers farmers with actionable insights for improved productivity and informed decision-making.

## Learning Objectives
- Analyze predictor variables and their relationship with the target variable (`Standard_yield`).
- Perform feature engineering, including categorical encoding (Dummy variables) and scaling.
- Construct and evaluate Multiple Linear Regression models.
- Address multicollinearity using regularization techniques (LASSO and Ridge regression).
- Implement Decision Tree models for comparative prediction tasks.
- Evaluate performance using MSE (Mean Squared Error) and RMSE (Root Mean Squared Error).

## Dataset Information
The analysis uses a vast agricultural dataset including:
- **Geographic Features:** Elevation, Slope, Latitude, Longitude, and Location.
- **Weather Features:** Rainfall and Average Temperature.
- **Soil & Crop Features:** Soil fertility, Soil type, pH, and Chosen crop.
- **Farm Management:** Pollution level and Plot size.
- **Target Variable:** `Standard_yield` (Standardized yield expected from the field).

## Project Structure
- `Linear_regression_analysis.ipynb`: The main Jupyter Notebook containing the data analysis and modeling.
- `data_ingestion.py`: Module for importing and initial handling of the database.
- `field_data_processor.py`: Module for cleaning and processing field-specific data.
- `validate_data.py`: A testing suite using `pytest` to ensure data integrity and schema validity.

## Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/agricultural-yield-prediction.git](https://github.com/your-username/agricultural-yield-prediction.git)
