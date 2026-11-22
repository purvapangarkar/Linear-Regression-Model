# Sales Prediction Using Multiple Linear Regression

## 1. Introduction
This project is based on Multiple Linear Regression. The aim is to predict product sales using advertising expenditure on different platforms such as TV, Radio, and Newspaper.

This activity helps in understanding how multiple input features are used to predict a continuous output.

## 2. Objective
- To understand Multiple Linear Regression.
- To study the relationship between advertising expenditure and sales.
- To train a regression model using a dataset.
- To predict sales and evaluate the model's performance.

## 3. Dataset Information
- **Dataset Name:** Advertising Sales Dataset
- **Source:** Kaggle
- **Dataset Link:** https://www.kaggle.com/datasets/bumba5341/advertisingcsv
- **File Format:** CSV
- **Number of Records:** 200

The dataset contains the following columns:

| Column | Description |
|---|---|
| TV | Advertising cost on TV |
| Radio | Advertising cost on Radio |
| Newspaper | Advertising cost on Newspaper |
| Sales | Product sales |

## 4. Tools and Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## 5. Work Completed
The following steps were completed in this activity:

1. Selected and loaded the Advertising Sales dataset.
2. Checked the dataset shape, information, and statistical description.
3. Checked for missing values and duplicate records.
4. Created scatter plots to understand the relationship between advertising features and sales.
5. Created a correlation matrix and heatmap.
6. Performed manual calculations using selected dataset observations.
7. Implemented Simple Linear Regression using one input feature.
8. Implemented Multiple Linear Regression using TV, Radio, and Newspaper.
9. Studied the model coefficients and intercept.
10. Compared actual and predicted sales values.
11. Evaluated the model using MAE, MSE, RMSE, R-squared, and Adjusted R-squared.
12. Performed residual analysis and checked multicollinearity using VIF.
13. Used the trained model to predict sales for new input values.

## 6. Algorithm Used
**Multiple Linear Regression**

The model uses three input features to predict sales.

The general equation is:

Sales = b0 + b1(TV) + b2(Radio) + b3(Newspaper)

Where:
- b0 = Intercept
- b1, b2, b3 = Model coefficients

## 7. Key Results
The model was trained and tested using the dataset. Its performance was evaluated using different regression evaluation metrics.

- **MAE:** 1.4607567168117603
- **MSE:** 3.1740973539761033
- **RMSE:** 1.78159966153345
- **R-squared:** 0.89943802410091
- **Adjusted R-squared:** 0.8910578594426547

The actual and predicted sales values were also compared to understand the model's performance.

## 8. Conclusion
In this activity, I implemented Multiple Linear Regression to predict sales using advertising expenditure on TV, Radio, and Newspaper. I also performed data analysis, visualisation, model evaluation, and prediction.

Through this activity, I understood how Multiple Linear Regression works and how its performance can be evaluated.

## 9. Repository Contents
- `Sales_Prediction.ipynb` – Completed Google Colab notebook.
- `README.md` – Project information and description.
- `Advertising.csv` – Dataset used for the project, if redistribution is permitted by its source.

## 10. GitHub Submission Information
**Submission GitHub ID:** [complexiota](https://github.com/complexiota)

**Repository Name:** `Activity1_Multiple_Linear_Regression_[YourRollNumber]`

**Repository Visibility:** Public

**Student:** Purva Pangarkar  
**Activity:** Multiple Linear Regression


