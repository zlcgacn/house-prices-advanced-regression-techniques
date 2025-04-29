# House Price Prediction Project

## Project Overview
This project uses machine learning methods to predict house prices, based on the "House Prices - Advanced Regression Techniques" competition dataset from Kaggle. By analyzing various features of houses, we build predictive models to estimate the final sale price.

## Dataset Description
The dataset comes from a Kaggle competition and includes training and test sets:
- Training set: Contains house features and corresponding sale prices
- Test set: Contains house features, with sale prices to be predicted

## Model Used
The project uses a Random Forest Regression model (RandomForestRegressor) for prediction, which offers good performance and lower risk of overfitting.

## Feature Selection
The model uses the following features for training:
- LotArea: Lot size in square feet
- YearBuilt: Original construction date
- 1stFlrSF: First floor square feet
- 2ndFlrSF: Second floor square feet
- FullBath: Number of full bathrooms
- BedroomAbvGr: Number of bedrooms above ground
- TotRmsAbvGrd: Total rooms above ground (excluding bathrooms)

## Implementation Steps
1. Data loading and preprocessing
2. Feature selection
3. Model training and validation
4. Training the final model on the complete training set
5. Making predictions on the test set
6. Generating the submission file

## How to Run
1. Ensure the required Python libraries are installed: pandas, numpy, scikit-learn
2. Download the Kaggle competition dataset
3. Run the Jupyter notebook file `house-prices-advanced-regression-techniques.ipynb`

## Validation Results
The Random Forest model achieves a Mean Absolute Error (MAE) of 21,857 on the validation set.

## Future Improvements
The following directions can be considered to further improve model performance:
1. Feature engineering: Create more meaningful features
2. Handle missing values and outliers
3. Try other models such as gradient boosting trees, neural networks, etc.
4. Model parameter tuning
5. Ensemble multiple models 
