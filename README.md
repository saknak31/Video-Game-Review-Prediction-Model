# Video-Game-Review-Prediction-Model
This project develops a machine learning model to predict user review scores for video games. Using a dataset of video game information, including release dates and platforms, we implemented a predictive model using XGBoost and scikit-learn.

## Key Features
- Data preprocessing and feature engineering
- Implementation of an XGBoost regression model
- Hyperparameter tuning using RandomizedSearchCV
- Feature importance analysis

## Technologies Used
- Python
- pandas for data manipulation
- scikit-learn for model building and evaluation
- XGBoost for the core predictive algorithm

## Model Performance
- Mean Squared Error: 1.4825
- R² Score: 0.1141

## Key Insights
The model identified the following as the most important features in predicting user review scores:
1. Nintendo 64 platform
2. PC platform
3. PlayStation 5 platform

## Future Improvements
- Explore additional feature engineering techniques
- Investigate more advanced ensemble methods
- Collect additional data points to improve prediction accuracy
