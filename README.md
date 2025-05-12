# Boston Housing Price Predictor

A simple machine learning project using Linear Regression to predict house prices (`MEDV`) based on various features from the Boston Housing dataset.

## Project Structure

- main.ipynb # Jupyter notebook with code and analysis
- BostonHousing.csv # Dataset (if included)
- .gitignore # Ignored files and folders


## Dataset

The dataset contains various attributes of houses in Boston suburbs, such as:

- `CRIM`: Crime rate per capita
- `RM`: Average number of rooms per dwelling
- `LSTAT`: % of lower status population
- `PTRATIO`, `TAX`, etc.

The target variable is:

- `MEDV`: Median value of owner-occupied homes (in $1000s)

## Features

- Exploratory Data Analysis (EDA) using Seaborn and Pandas
- Heatmap of correlation matrix
- Train/test split
- Linear Regression model using `scikit-learn`
- Model evaluation using R² and Mean Squared Error

## Getting Started

### Prerequisites

Make sure you have the following Python packages installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

Running the Notebook
Clone this repository

Open main.ipynb in Jupyter Notebook or JupyterLab

Run the cells to see the data analysis and predictions

from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)
predictions = model.predict(X_test)
```
### License

This project is for educational purposes only. The Boston Housing dataset is a public dataset originally from UCI.
