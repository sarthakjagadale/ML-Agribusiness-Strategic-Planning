# Model Comparison

## Objective

The purpose of model comparison is to identify a machine learning algorithm that provides strong crop yield prediction while maintaining reasonable interpretability, computational efficiency and scalability.

| Model             | Type              | Main Advantage                       | Main Limitation                    |
| ----------------- | ----------------- | ------------------------------------ | ---------------------------------- |
| Mean Baseline     | Baseline          | Very simple reference                | Cannot learn relationships         |
| Linear Regression | Regression        | Easy to interpret                    | Limited nonlinear modelling        |
| Decision Tree     | Tree              | Captures nonlinear relationships     | Can overfit                        |
| Random Forest     | Ensemble          | Robust and powerful for tabular data | Less interpretable                 |
| Gradient Boosting | Ensemble          | Strong predictive performance        | Requires tuning                    |
| XGBoost/LightGBM  | Advanced Ensemble | High performance and scalability     | More complex                       |
| CNN/LSTM          | Deep Learning     | Useful for images/time series        | Requires more data and computation |

## Recommended Models

The primary candidates are:

1. Random Forest
2. Gradient Boosting

Linear Regression will be maintained as an interpretable baseline.

## Selection Criteria

Models will be compared using:

* RMSE
* MAE
* R²
* Training time
* Validation stability
* Generalization ability
* Interpretability
* Scalability
