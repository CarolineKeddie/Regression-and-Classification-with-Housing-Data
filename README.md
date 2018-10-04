# Regression-and-Classification-with-Housing-Data
Using Data Science to determine the best properties to buy and sell


There are three components to the project:

1. Estimate the sale price of properties based on their "fixed" characteristics, such as neighborhood, lot size, number of stories, etc.
2. Estimate the value of possible changes and renovations to properties from the variation in sale price not explained by the fixed characteristics. Your goal is to estimate the potential return on investment (and how much you should be willing to pay contractors) when making specific improvements to properties.
3. Determine the features in the housing data that best predict "abnormal" sales (forclosures, etc.).

This project uses the [Ames housing data recently made available on kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

Though the housing data for this project is very rich, it is not trivial to clean and prepare for modeling. Good EDA, cleaning, and feature engineering will be critical to the success of your models. Always remember to think critically about the data before modeling. The computer can't be the researcher for you!

The first two parts of the project are regression problems. There are potentially hundreds of features and plenty of multicollinearity, so regularization is definitely recommended.

The second question involves fitting a regression on the residuals of the first model. This is a practice that "covaries out" any effects of the predictors in the first model before investigating the effects of predictors in the second model.

The third section of the project is more challenging and involves dealing with significant class imbalance. This is a common and tricky problem in real-world classification tasks.

