# Co2 Emissions Prediction

This project aims to predict Co2 emissions of vehicles using machine learning techniques. This model utilizes Supervise Machine Learning using Regression Model. 

## Features

- **Data Preprocessing**: Handles missing values, scales numerical features, and encodes categorical variables.
- **Data Visualization**: Provides insightful visualizations to explore relationships and distributions in the data.
- **Machine Learning**: Utilizes a linear regression model to predict CO2 emissions.
- **Evaluation**: Measures model performance using metrics like Mean Squared Error, R² Score, and Root Mean Squared Error.

## Dataset

The dataset is assumed to contain details about vehicles, including:
- Vehicle brand and model
- Engine specifications
- Fuel consumption
- CO2 emissions (target variable)

## Visualizations

- **Distribution of Brands, Vehicle Classes, and Fuel Types**: Count plots to understand the dataset composition.
- **CO2 Emissions by Features**: Boxplots showing variations in emissions by brand, vehicle class, and fuel type.
- **Scatter Plots**: Relationships between CO2 emissions and engine size or fuel consumption.

## Implementation

### Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`


### Steps

1. Load and clean the dataset.
2. Analyze data using descriptive statistics and visualizations.
3. Split the data into training and testing sets.
4. Preprocess the data using pipelines.
5. Train a linear regression model.
6. Evaluate the model using performance metrics.
7. Visualize actual vs predicted emissions and residuals.

