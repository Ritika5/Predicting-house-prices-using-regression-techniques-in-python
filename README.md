# Predicting-house-prices-using-regression-techniques-in-python
Predicted house prices for 1500 houses based on 79 features with an accuracy of 88% using XG-Boost model 

### Dataset Source: Kaggle

### Summary
If you ask a home buyer to describe their dream house, they probably won't begin with the height of the basement ceiling or 
the proximity to an east-west railroad. This project proves that much more influences price negotiations than the number of 
bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this project posed a challenge
to predict the final price of each home.

### Modeling Steps
1. Missing Value Treatment: missing values were imputed
2. Data Visualization: matplotlib and seaborn libraries in python were used to explore variables in the data and their correlation
3. Feature Encoding: was carried out using OneHotEncoder
4. Model Building: Random forest and XG-boost models were fit on the data
5. Hyperparameter Tuning: was carried out to find an optimal fit

#### Final Model Selected: XGBoost
#### Accuracy (train data): 88.28%
#### Accuracy (test data): 87.45%

#### Most important features as per the model:
1. Above ground living area square feet
2. Lot size in square feet
3. Basement finished square feet (type 1)
4. Total square feet of basement area
5. First floor square feet
6. Unfinished square feet of basement area
7. Size of garage in square feet
