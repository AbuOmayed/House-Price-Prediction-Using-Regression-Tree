# House Price Prediction Using Regression Tree

## Description
This project uses a Regression Tree model to predict the median price of houses in different Boston areas based on multiple demographic and housing features. It demonstrates how decision tree regression can be applied to real estate pricing, offering interpretable insights for investment decisions.

---

## About the Dataset

Imagine you are a data scientist working for a real estate company planning to invest in Boston's real estate market. The dataset contains information about different areas (towns) in Boston—not individual houses. Your task is to build a model that predicts the median house price for each area to assist with investment decisions.

The dataset includes the following features:

- **CRIM:** Crime rate per capita by town  
- **ZN:** Proportion of residential land zoned for lots over 25,000 sq.ft.  
- **INDUS:** Proportion of non-retail business acres per town  
- **CHAS:** Charles River dummy variable (1 if tract bounds river, 0 otherwise)  
- **NOX:** Nitric oxides concentration (parts per 10 million)  
- **RM:** Average number of rooms per dwelling  
- **AGE:** Proportion of owner-occupied units built prior to 1940  
- **DIS:** Weighted distances to five Boston employment centers  
- **RAD:** Index of accessibility to radial highways  
- **TAX:** Property-tax rate per $10,000  
- **PTRATIO:** Pupil-teacher ratio by town  
- **LSTAT:** Percentage of lower status population  
- **MEDV:** Median value of owner-occupied homes in $1000s (target variable)

---

## Methodology
- Data preprocessing including handling missing values and scaling features  
- Splitting the dataset into training and testing subsets  
- Training a regression tree model to predict continuous house prices  
- Evaluating model performance using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²)  
- Visualizing the regression tree and analyzing feature importance  

---

## Results
The regression tree model provides reliable predictions of median house prices across Boston areas, highlighting key factors influencing housing values.

---

## Usage

Clone the repository and install dependencies:

```bash
git clone https://github.com/AbuOmayed/house-price-prediction-regression-tree.git
cd house-price-prediction-regression-tree
pip install -r requirements.txt
jupyter notebook notebooks/house_price_regression_tree.ipynb
