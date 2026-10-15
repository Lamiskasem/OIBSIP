
# Wine Quality Prediction

**OIBSIP Data Analytics Internship — Level 2, Task 2**

## Project Overview

This project analyzes physicochemical properties of red wine and develops machine learning models to predict wine quality scores.

## Objectives

- Inspect and clean the dataset.
- Perform exploratory data analysis.
- Explore relationships between wine measurements and quality.
- Train Linear Regression and Random Forest Regression models.
- Compare models using MAE, RMSE, and R-squared.
- Visualize predictions, residuals, and feature importance.

## Dataset

Source: UCI Machine Learning Repository — Wine Quality Dataset.

Dataset page:
https://archive.ics.uci.edu/dataset/186/wine+quality

File used: `winequality-red.csv`

The input features include acidity measurements, residual sugar, chlorides, sulfur dioxide, density, pH, sulphates, and alcohol. The target variable is `quality`.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
DataAnalytics-L2-WineQualityPrediction/
├── data/
│   └── winequality-red.csv
├── notebooks/
│   └── wine_quality_prediction.ipynb
├── images/
├── README.md
├── requirements.txt
├── model_evaluation.csv
└── test_predictions.csv
```

## How to Run

1. Clone or download this project.
2. Install the required packages:

   `pip install -r requirements.txt`

3. Place `winequality-red.csv` inside the `data/` folder.
4. Open `notebooks/wine_quality_prediction.ipynb`.
5. Run the notebook cells from top to bottom.

## Models

- Linear Regression
- Random Forest Regression

## Evaluation

Models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

Actual metric values and observations are documented in the notebook.

## Results

The notebook compares both models and includes visualizations of the quality distribution, feature correlations, actual versus predicted values, residuals, and Random Forest feature importance.

## Limitations

Wine quality scores are subjective, and the available dataset covers a limited set of samples. Model predictions are estimates rather than guaranteed quality ratings.

## Author

[Lamis Kasem]

## Internship

Oasis Infobyte (OIBSIP) — Data Analytics
