# Soil-Analysis-and-Prediction-Using-Machine-Learning-and-VNIR-Spectroscopy-Data

This project focuses on building predictive models to estimate Soil Organic Carbon (SOC) content using data from Visible Near Infrared (VNIR) spectroscopy.
SOC is a key indicator of soil fertility and quality, and accurate estimation of its content is critical for agricultural and environmental management.
We applied machine learning techniques to predict SOC based on spectroscopy data, leveraging various regression models and preprocessing techniques.



# Features of the Project:

Data Source: VNIR spectroscopy data was used to predict SOC content, offering a non-destructive and cost-effective way to analyze soil properties.


Algorithms Used:

Elastic Net Regression

Support Vector Regression (SVR)

Polynomial Regression



Preprocessing:

Feature scaling (standardization and normalization) was applied to improve model performance.

Various data preprocessing techniques were employed to clean and prepare the data for modeling.


Model Evaluation:

The performance of the predictive models was assessed using the following metrics:

Mean Squared Error (MSE): Measures the average squared difference between the predicted and actual SOC values.

R-Squared (R²): Indicates how well the model explains the variability of SOC content.

Mean Absolute Error (MAE): Measures the average magnitude of the errors between predictions and actual values.


# Results:

A comprehensive analysis was conducted using several regression models—Support Vector Regression (SVR), Polynomial Regression and Elastic Net—to predict Soil Organic Carbon (SOC) based on spectroscopy data. The performance of each model was evaluated using Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R²) Score.

SVR and Polynomial Regression yielded suboptimal results, with high RMSE and MAE values. Their negative R² Scores suggest poor ability to explain the variance in SOC content.

Elastic Net Regression outperformed all other models, achieving the lowest RMSE and MAE values and the highest R² Score. Elastic Net’s hybrid nature, combining Lasso and Ridge regression, allowed it to balance feature selection and regularization effectively.

Overall, Elastic Net was determined to be the most effective model for SOC prediction, successfully minimizing errors and capturing the variance in the data.


