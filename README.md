# crop-price-prediction-using-ml-techniques
In this project, I analyzed a dataset (crop_price.csv) containing crop prices and associated agricultural metrics across various Indian states, with the goal of predicting annual crop prices using regression models. The dataset comprises 49 records and includes features such as cultivation cost, production yield, temperature, rainfall, and crop prices.

After ensuring the dataset was clean—confirming there were no missing values or duplicates—I performed exploratory data analysis (EDA). This involved using histograms, scatter plots, and box plots to understand feature distributions, examine linear relationships, and identify potential outliers. The EDA offered valuable insights into how environmental and economic factors impact crop pricing.

Two regression models were developed and evaluated:

Linear Regression:

MSE: ~4.10e-30

RMSE: ~1.68e-59

MAE: ~1.24e-15

R² Score: 1.0

These nearly perfect metrics suggest a very strong linear relationship. However, given the small dataset size, they could also indicate overfitting or potential data leakage.

Support Vector Regression (SVR):

MSE: ~0.0115

RMSE: ~0.0001

MAE: ~0.084

R² Score: ~0.97

The SVR model demonstrated robust performance with realistic error metrics, indicating a strong fit while reducing the likelihood of overfitting.
