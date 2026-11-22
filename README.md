# Sales Prediction Using Multiple Linear Regression

## 1. Introduction

This project is based on predicting product sales using Multiple Linear Regression. It uses advertising expenditure on TV, Radio and Newspaper to predict sales.

The project is implemented using Python in Google Colab with a dataset downloaded from Kaggle.

## 2. Objective

The main objective of this project is to understand how multiple input features are used together to predict a continuous numerical value using Multiple Linear Regression.

## 3. Dataset Information

- **Dataset Name:** Advertising Sales Dataset
- **Source:** [Kaggle – Advertising Dataset](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)
- **File Format:** CSV
- **Number of Records:** 200
- **Number of Main Features:** 3
- **Target Variable:** Sales

### Dataset Features

| Feature | Description |
|---|---|
| TV | Advertising expenditure on TV |
| Radio | Advertising expenditure on Radio |
| Newspaper | Advertising expenditure on Newspaper |
| Sales | Product sales |

The three advertising features are used as independent variables, and Sales is used as the dependent variable.

## 4. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## 5. Project Steps

1. Importing the required libraries.
2. Loading and understanding the dataset.
3. Checking missing values and duplicate records.
4. Cleaning the dataset.
5. Visualizing relationships using scatter plots.
6. Creating a correlation matrix and heatmap.
7. Performing manual Multiple Linear Regression calculations using two features.
8. Building a Single Linear Regression model using one feature.
9. Building a Multiple Linear Regression model using three features.
10. Comparing both models.
11. Interpreting the regression equation, intercept and coefficients.
12. Comparing actual and predicted sales.
13. Evaluating the model using MAE, MSE, RMSE, R² and Adjusted R².
14. Performing residual analysis.
15. Checking multicollinearity using VIF.
16. Predicting sales using new input values.
17. Drawing conclusions from the results.

## 6. Machine Learning Algorithm

**Multiple Linear Regression**

Multiple Linear Regression is a supervised Machine Learning algorithm used to predict a continuous numerical value using two or more independent variables.

The general equation is:

Sales = b0 + b1(TV) + b2(Radio) + b3(Newspaper)

Where:
- b0 = Intercept
- b1, b2, b3 = Regression coefficients
- TV, Radio and Newspaper = Independent variables

## 7. Model Evaluation

The model is evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- Adjusted R² Score

These metrics help understand the prediction errors and performance of the model.

## 8. Results

The notebook includes:
- Manual calculation and verification using Scikit-learn.
- Single-feature and multiple-feature model comparison.
- Regression coefficients and intercept.
- Actual and predicted sales comparison.
- Residual plots and histogram.
- Correlation heatmap and VIF results.
- Prediction for a new advertising budget.

*Actual numerical results and observations are available in the completed Google Colab notebook.*

## 9. Conclusion

This project helped me understand how Multiple Linear Regression works and how different advertising features can be used to predict sales.

I learned how to load and inspect a dataset, perform data visualization, calculate regression coefficients, train a model, evaluate its performance and make predictions.

The project also helped me understand the importance of residual analysis, multicollinearity and comparing single-feature and multiple-feature models.

## 10. Repository Contents

```text
Sales_Prediction_MLR/
│
├── Advertising.csv
├── Sales_Prediction.ipynb
├── README.md
```


**Project Type:** Machine Learning

**Algorithm:** Multiple Linear Regression

**Level:** Beginner

**Platform:** Google Colab
