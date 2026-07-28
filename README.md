# H&S Revenue Forecasting

A Python-based revenue forecasting project that builds and compares two multiple linear regression models to predict company revenue using operational and seasonal data. The project evaluates model performance using Mean Absolute Percentage Error (MAPE) and visualizes forecast accuracy.

## Project Overview

This notebook develops two forecasting models for H&S:

- **Model 1:** Production + Summer seasonal effects
- **Model 2:** Cooling Degree Days (coolDD) + Spring seasonal effects

Both models are trained on historical data, tested on unseen observations, and compared using MAPE to determine which provides the most accurate revenue forecasts.

## Features

- Data cleaning and preprocessing with Pandas
- Seasonal dummy variable creation
- Interaction term engineering
- Multiple Linear Regression using Statsmodels
- Model evaluation using MAPE
- Forecast visualizations with Matplotlib
- Side-by-side model comparison

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels

## Project Workflow

1. Import and clean the dataset
2. Create seasonal dummy variables
3. Generate interaction variables
4. Split data into training and testing sets
5. Train two regression models
6. Generate revenue predictions
7. Evaluate forecasting accuracy using MAPE
8. Compare model performance
9. Visualize actual vs. predicted revenue

## Model Comparison

### Model 1
**Variables**
- Production
- Summer Dummy Variable
- Production × Summer Interaction

### Model 2
**Variables**
- Cooling Degree Days (coolDD)
- Spring Dummy Variable
- coolDD × Spring Interaction

The notebook compares both models and recommends the one with the lower MAPE as the preferred forecasting model.

## Repository Structure

```
H_and_S_Revenue_Forecasting_Class_Style_Final.ipynb
README.md
```

## Learning Outcomes

This project demonstrates:

- Feature engineering for regression models
- Seasonal demand modeling
- Predictive analytics
- Forecast evaluation techniques
- Business-focused data analysis
- Data visualization

## Future Improvements

- Test additional machine learning models
- Include more external economic variables
- Perform cross-validation
- Automate forecasting for future periods
- Build an interactive dashboard

## Author

**Fatima**

University of Waterloo  
Sustainability and Financial Management (SFM)
````
