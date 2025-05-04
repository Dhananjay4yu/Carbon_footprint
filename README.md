# Carbon Footprint Prediction - ML Contest

## Approach:
- Used a Random Forest Regressor model to predict carbon footprint based on numerical and categorical features.
- Handled mixed data types using a ColumnTransformer and pipeline.
- Evaluated model using RMSE, MAE, and R² score.
- Achieved R² = 0.98 on training/validation split.

## Feature Engineering:
- Converted object-type numeric fields to actual numeric.
- Filled missing values using median for numerical features.
- One-hot encoded categorical features using OneHotEncoder.

## Tools and Libraries Used:
- Python
- pandas, numpy
- scikit-learn (for modeling and preprocessing)
- joblib (for model saving)

## Files Included:
- main.py : Main Python script with model training and prediction
- submission.csv : Final output for test data
- carbon_footprint_model.pkl : Saved model
