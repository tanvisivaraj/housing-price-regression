# Housing Price Regression - California Census Data

This project predicts housing prices in California districts using data from the 1990 census. It serves as an introductory project for regression analysis, featuring preprocessing, exploratory data analysis (EDA), and model development using Scikit-learn.

## Project Overview

The aim is to develop regression models that estimate house prices based on features such as median income, number of rooms, and population. The project involves:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Modeling using Linear Regression and Decision Trees
- Model Evaluation and Performance Comparison

## Dataset

The dataset is sourced from the 1990 California census and includes the following features:

- **longitude**: Geographic coordinate, a higher value means further west.
- **latitude**: Geographic coordinate, a higher value means further north.
- **housing_median_age**: Median age of houses in a block.
- **total_rooms**: Total number of rooms in a block.
- **total_bedrooms**: Total number of bedrooms in a block.
- **population**: Total number of people in a block.
- **households**: Total number of households in a block.
- **median_income**: Median income of households in a block (in tens of thousands of USD).
- **median_house_value**: Target variable, median house value in a block (USD).
- **ocean_proximity**: Categorical feature indicating proximity to the ocean.

## Project Structure

- **Data Cleaning**: Handling missing values
- **Exploratory Data Analysis**:
  - Visualizing feature distributions.
  - Examining feature correlations with `median_house_value`.
- **Modeling**:
  - Linear Regression
  - Decision Tree Regression
- **Model Evaluation**:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - Visual comparison of actual vs. predicted values

## Code Requirements

- Python 3.11
- Libraries:
  - Pandas
  - Numpy
  - Seaborn
  - Matplotlib
  - Scikit-learn

Install dependencies using:

```bash
pip install -r requirements.txt
